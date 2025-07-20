# Process in Operating System
The Process is a program in execution, like when  we run a c/c++ code it creates a binary code now when we actually run the binary code it became a process.

### Process has varous sections :-
- Text Section: A text or code segment contains executable instructions. It is typically a read only section
- Stack: The stack has temp data such as local variable, functions etc
- Data Sections: Contain Global variable
- Heap Section: Dynamically memory allocated to process during its run time

## Attributes of a Process
A process has several important attributes that help the operating system manage and control it. These attributes are stored in a structure called the Process Control Block (PCB) (sometimes called a task control block). 
## States of Process
- New: Newly Created Process (or) being-created process.
- Ready: After the creation process moves to the Ready state, i.e. the process is ready for execution.
- Wait (or Block): When a process requests I/O access.
- Complete (or Terminated): The process completed its execution.
- Suspended Ready: When the ready queue becomes full, some processes are moved to a suspended ready state
- Suspended Block: When the waiting queue becomes full.
![](https://media.geeksforgeeks.org/wp-content/cdn-uploads/gq/2015/06/process-states1.png)