## Multitasking

The ability to work on multiple independent tasks at the same time  by rapidly switching the CPU among them is Multitasking.

- The operating system (OS) rapidly “switches” the CPU between completely separate programs (processes)—for example, your web browser, music player, and word processor.

---
## Multithreading
The ability of a single process to have multiple threads of execution within it's own address space is Multithreading.

- **Thread: A lightweight unit of execution that shares the process’s memory and resources but has its own program counter and stack.**

- A single program splits its work into smaller tasks (threads). They share the same kitchen tools (memory) but each has its own little to‑do list (stack and registers).

---

## Comparison -

| Aspect                  | Multitasking                                     | Multithreading                                |
| ----------------------- | ------------------------------------------------ | --------------------------------------------- |
| **Unit of Work**        | Process                                          | Thread                                        |
| **Context Switch Cost** | High (save/load full process state, memory maps) | Lower (only thread registers & stack pointer) |
| **Memory**              | Each process has separate address space          | Threads share the same address space          |
| **Communication**       | Inter-process communication (IPC) needed         | Direct access to shared variables             |
| **Fault Isolation**     | Strong (one process crash ≠ others crash)        | Weaker (one thread crash may bring down all)  |
| **Creation Overhead**   | Relatively heavy                                 | Relatively light                              |
| **Use Cases**           | Running independent applications simultaneously  | Parallel tasks within one application         |

---

- Multitasking = multiple processes, heavy isolation, higher overhead.

- Multithreading = multiple threads in one process, shared memory, lower overhead, but requires careful synchronization.