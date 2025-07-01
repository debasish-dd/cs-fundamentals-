# Types of Operating Systems
We are going to classify based on functionalities an operating system provides.
---
## 1. Batch Operating System
Batch OS dose not intract with the computer directly, There is an operator which takes similar jobs having the same requirements and groups them into batches. Then the computer process these batches together. It is the responsibility of the operator to sort jobs with similar needs. These type of OS are meant for large amount of jobs.

![](https://media.geeksforgeeks.org/wp-content/uploads/20230511130815/types1-(1).webp)

## 2. Multi-Programming Operating System
Here more than one jobs are present in main memory and any one of them can be kept in execution. This is used for better utilization of resources.

![](https://media.geeksforgeeks.org/wp-content/uploads/20230516182714/Types-of-OS-03-660.webp)

## 3. Multi-tasking/Time-sharing Operating systems
Just like Multi-Programming OS in Multi-Tasking OS multiple tasks can be in the main memory but here for every tasks some time has allotted, The time that each task gets to execute is called quantum. In this time that task can use system resources and cpu. After the time is over then the OS allote some time for the other task to execute.

![](https://media.geeksforgeeks.org/wp-content/uploads/20230516183620/Types-of-OS-01.webp)

## 4. Multi-User Operating Systems
This system allows multiple users at the same time. This system can be multi-processor or single processor (like Multi User & Multi Programming OS).

![](https://media.geeksforgeeks.org/wp-content/uploads/20230512125908/Capture2210.png)

## 5. Multi-Processing OS
These type of OS has multiple cpus unlike Multi-User & Multi-Programming OS, so the chances of starvation problem is very less in this OS, it can run multiple tasks more efficiently.

## 6. Distributed Operating System
This is a widely used (recently) OS, in this OS autonomous interconnected computers communicate with each other using a shared communication network.

![](https://media.geeksforgeeks.org/wp-content/uploads/20230516183602/Types-of-OS-04.webp)

## 7. Real-Time Operating System
This type of OS has a very low response time. Real-time systems are used when there are time requirements that are very strict like missile systems, air traffic control systems, robots, etc.

---
- Hard Real-Time Systems : Time constraints are very strict, and even the shortest possible delay is not acceptable.
---
- Soft Real-Time Systems: Time is less strict
---