# cmsc312-project-1-operating-system-simulator-solved
**TO GET THIS SOLUTION VISIT:** [CMSC312 Project 1-Operating system simulator Solved](https://www.ankitcodinghub.com/product/cmsc312-project-1-operating-system-simulator-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91373&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMSC312 Project 1-Operating system simulator Solved&nbsp;&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

1. Summary

This project aims at designing and implementing a simulator of an operating system. Students are expected to prepare a computer program that will serve as a simulator of creation and running of processes on a theoretical operating system. These processes will originate from program files (also referred to as templates) provided by students. Program files will be consisting of pre-determined instructions that will simulate the usage of computer system resources. These programs need not to be coded, only simulated. These program files will have simulated instruction and I/O cycles that is proportional to the type and size of the program (e.g., template for printer driver will focus mainly on I/O cycles, while template for a spreadsheet will focus mainly on CPU cycles). Simulator must create a requested number of processes from each of templates randomly using a pre-defined generator. Classes are to be created to mimic the role of different hardware components and software embedded in the operating system. These classes will have methods in them to perform operating system duties and will rely or call on other classes or methods, thus creating a fully interconnected system.

2. Project details

This project will consist of four main components – (1) process management, (2) memory management, (3) I/O management, and (4) user interface. Each individual component is explained in detail below.

2.1. Process management

“Program files” (also referred to as “templates”) are text or .xml files that are used to create processes that will be then managed and run by our OS simulator. Therefore, “program file” must be treated as a template that can be used to create numerous processes with diverse parameters (e.g., by randomization of the values in the template). Each template (and thus each process created from it) will consist of a “mock” code written in a form of keyword operations, each representing the usage of a different resource managed by OS. For simplicity, only three types of operations are required:

<ul>
<li>CALCULATE – When this line is read in, the simulator will run the process in the run state for the number of cycles specified as a parameter (i.e., occupy CPU for a given number of cycles, simulating the usage of CPU resource).</li>
<li>I/O – This will put the process in the waiting state for a specified number of cycles.</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
• FORK – this will create a child process according to a selected parent-child management scheme.

Each “program file” must be created using different combinations of these commands (they can appear multiple times). Each command must have assigned number of cycles necessary for completion, as well as memory necessary for storing this command (in case of a paging model being implemented).

Example of a program file / template (this needs to be enriched with memory management in a later step):

</div>
</div>
<div class="layoutArea">
<div class="column">
Operation list: CALCULATE CALCULATE I/O CALCULATE I/O

This template must

defined number of processes with randomized cycle length for each operation. Example of two processes created from the above template are:

</div>
</div>
<div class="layoutArea">
<div class="column">
Process #1 CALCULATE 46 CALCULATE 33 I/O 17 CALCULATE 11 I/O 22

</div>
<div class="column">
Process #2 CALCULATE 82 CALCULATE 48 I/O 11 CALCULATE 19 I/O 16

</div>
</div>
<div class="layoutArea">
<div class="column">
min cycles 5

25

10

5 15

</div>
<div class="column">
max cycles 100

50

20

20 25

</div>
</div>
<div class="layoutArea">
<div class="column">
be used as an input (seed) for a generator that will spawn a user-

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Each program must contain at least one critical section and at least a single critical section resolving scheme must be implemented. Critical sections can be implemented as tags encoding a number of operations that are considered as a critical section. Critical sections can be hard coded into a template or placed randomly in each created process. All information about each process must be stored in Process Control Block (PCB).

Single level child-parent relationship must be implemented within each template. It may be either deterministic (a child process is always created) or probabilistic (a child process has a fixed chance to be spawned).

Additionally, for points necessary for B or A grades it is required for a at least single interprocess communication scheme, a message passing scheme, and a multi-level child parent relationship to be implemented.

2.2. Process lifecycle

The processes created from templates must be managed by the OS simulator following a process lifecycle that is realized as switching among the possible states in which each individual process will be in a given moment:

<ul>
<li>NEW – The program or process is being created or loaded (but not yet in memory).</li>
<li>READY – The program is loaded into memory and is waiting to run on the CPU.</li>
<li>RUN – Instructions are being executed (or simulated).</li>
<li>WAIT – The program is waiting for some event to occur (such as an I/O
completion).
</li>
<li>EXIT – The program has finished execution on the CPU (all instructions
and I/O complete), releases resources and leaves memory.

2.3. Process scheduling

Student must choose and implement a scheduling algorithm. Easiest solution would be to go with Round Robin approach due to the ease of implementation, however other solutions (with exception of a trivial First Come First Served) also will be accepted.

Additionally, for points necessary for B or A grades it is required to implement at least two different schedulers must and compare them with regard to their performance, as well as
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
assign priorities to processes, implement a multi-level queue scheduling, process resources, and deadlock avoidance algorithm.

2.4. Memory management

Memory Management will be implemented by keeping a running total of all processes in main memory by not letting the overall memory size exceed the set limit. The OS simulator will have a main memory size of 1024MB. This value which is to be compared against the memory requirements of newly arrived processes. If total memory minus used memory is more than the newly arrived job’s memory requirement, it may enter the READY state (queue). Otherwise, the process would remain in the NEW queue (if it has been just spawned) or in the WAITING queue (if it tries to re-enter the ready state).

Additionally, for points necessary for B or A grades it is required for memory to be organized into a hierarchy consisting of three levels: main memory, storage, and registers (with all the necessary migration between these hierarchy levels), as well as to implement virtual memory and paging.

2.5. I/O management

Two types of I/O events must be handled:

<ul>
<li>coming from a process (i.e., generated by I/O command in the process) – as described in the section 2.1. Process management.</li>
<li>caused by external events (e.g., hardware peripherals) that may happen at any moment and caused by processes being executed by CPU. This should be realized as a random event with a given probability of occurring during every cycle.
2.6. Multi-threading and multi-CPU

Multi-threading must implement using software libraries and take advantage of hardware threads in the processor. Single-thread based simulation is not accepted.

Additionally, for for points necessary for B or A grades a simulation of multi-core and multi-thread architecture with at least two cores and four threads per each must be implemented. This can be achieved by dividing existing hardware threads into simulates
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
CPU classes and assigning separate schedules to each CPU instance.

2.7. User interface

This program/simulator will incorporate a user interface so that she/he can control the flow of the operating system and observe the “running” of it for testing purposes. It must be possible to load a program or job file automatically/manually into the simulator thus to conduct the allocation of the program’s PCB and memory space. The user can also specify the number of cycles to run before pausing. Statistics of the simulator should be available upon request, such as number of processes in each state, journal log of the simulator, and what resources are currently being used.

Additionally, for points necessary for B or A grades it is required to implement a Graphical User Interface (GUI). The GUI will display real-time statistics, visualizations, and data on all currently running processes. The PCB information of the jobs that are in memory and in the RUN state will be shown in some sort of GUI data table. This GUI table is always “refreshing” or updating as the simulator runs on its own or steps through the code.

3. General rules for the project

<ul>
<li>This is an open-ended project and the design skills, capability of adapting to specifications where necessary, as well as imagination and creativity of solving the required tasks play a crucial role.</li>
<li>Project will consist of two mandatory phases / assignments that must be build upon each other consecutively. These two assignments are mandatory for C grade. Third assignment will be to implement functionality for A/B grade</li>
<li>Project must be fully functional, and the code of project must compile and run.</li>
<li>Project must be a compound system of modules working together, not a
collection of non-integrated parts.
</li>
<li>Project must be done individually, not code sharing or copying / modifying is
allowed.
</li>
<li>Students are allowed to discuss and consult theoretical solutions and
approaches among themselves.
</li>
<li>Source code must be delivered for grading, as well as an executable version
of the project.
</li>
<li>Student is obliged to deliver a .pdf documentation of the project, discussing
the implemented solutions, software, and hardware requirements for the project to run, as well as guidelines on how to run the project.
</li>
</ul>
</div>
</div>
</div>
