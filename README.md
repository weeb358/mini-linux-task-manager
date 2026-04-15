# mini-linux-task-manager
Mini Linux Task Manager (HTOP Clone) A simplified Linux Task Manager built in C that displays system processes, CPU usage, memory status, and simulates CPU scheduling algorithms.


Features:
Real-time process monitoring from /proc filesystem
CPU & memory usage tracking
CPU scheduling algorithm simulations (FCFS, SJF, Round Robin)
Multithreaded architecture (Process Scanner, UI Updater, Scheduler)
Process creation using fork() and exec()
IPC via Shared Memory / Message Queues
Thread synchronization with Mutex locks & Semaphores
Dynamic memory management


Tech Stack:
Language: C
Libraries: pthread, standard C libraries
System Calls: fork, exec, IPC mechanisms
OS: Linux


├── src/
│   ├── process_monitor.c
│   ├── cpu_scheduler.c
│   ├── multithreading.c
│   ├── process_creation.c
│   ├── ipc.c
│   ├── synchronization.c
│   └── memory_management.c
├── include/
│   └── headers.h
├── Makefile
└── README.md
