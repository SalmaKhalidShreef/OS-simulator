# OS-simulator
# Scheduling
A scheduler that is responsible for scheduling between the processes in the Ready
Queue. It ensures that all processes get a chance to execute. the algorithm used is Round Robin. Round
robin is a scheduling algorithm where each process is assigned a fixed time slice.
For this project, each process executes 2 instructions in its time slice.

# Memory Management

The OS manage it and assigns a space for each process. The memory is of non-dynamic size. The
memory is large enough to hold the un-parsed lines of code, variables and PCB
for each of the processes. The memory is divided into memory words, each word
can store 1 variable and it’s corresponding data. 
Processes doesn't  access any data outside their allocated
memory block.

# Process Control Block

A process control block is a data structure used by computer operating systems to
store all the information about a process.In order to schedule your processes, you
will need to keep a PCB for every process. The PCB should contain the following
information:
1. Process ID (Assume that the ID corresponds to the program number)
2. Process State
3. Program Counter
4. Memory Boundaries

# Output
When  run the main class ,  The
system will start by reading the program files from the disk and assigning memory
locations for each of the aforementioned processes. Once all the processes are
loaded in the memory, the OS will start the scheduling process. The scheduler
will choose the process to run and do so by checking the processes states from the
PCBs stored in the memory, then running the selected process’s code from the
memory.
