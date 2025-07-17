# Introduction of System Call
A system call is a programmatic way in which a computer program request a service from the kernel of the operating system on which it is executed.
 - A user program can intract with the OS using system call. A number of services are requested by the program and the OS responds by launching a number of systems calls to fulfill the request.

 - Systen call uses context switching to switch between user mode to kernal mode allowing the program to request a service from the OS. The OS then handles the request, performs the necessary operations, and returns the result back to the program.

 - A system call can be written in a high lvl language like c or pascal, so if a high level language is used then the os may just directly invoke the system call which are just predefined funciton

 - System Call provide a standardized way for programs to access system resources.

 ### Services Provided by System Calls
 - file access , Directory,file system management
 - process creation and management
 - main memory and management   
 - Device handling and management
 - Networking , Protection etc
   