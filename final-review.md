Chapter 0: Linkers
==================
1.	What does a linker do?
2.	Draw a diagram of a linker in action.
3.	How does the linker know that a given module should be loaded at a certain location?
4.	Practice linkers from the lab.
5. Do homework problems.

Chapter 1: Intro & History
==================

1.	What’s the purpose of an OS?
2.	Briefly look over system calls.
3.	What are the differences between fork, exec, wait(pid), exit, init? Synchronous vs. asynchronous behavior?
4.	What happens when a user calls read (fd, buffer, nbytes)?
5.	How does the Trap instruction work?
6. Do homework problems.

Chapter 2: Processes
==================
1.	What are a process and the process model?
2.	How are processes created and terminated?
3.	What’s a daemon?
4.	Process States & Transitions: Draw Diagram
5.	How are processes implemented (Process Table)?
6.	Talk about differences between trap and interrupts.
7. Do homework problems.

Chapter 2.2 Threads
==================
1.	What’s the motivation behind using threads? (Advantages & disadvantages?)
2.	What’s the producer consumer pipeline?
3.	How are threads implemented in a user system?
4. Do homework problems.


Chapter 2.4 Process Scheduling
==================
1.	Draw the process state diagram again.
2.	Why is preemption important?
3.	What are the goals of scheduling algorithms?
4.	Distinguish between batch, interactive, real time.
5.	FIFO, SJF
6.	What’s priority aging and priority scheduling? SRTN
7.	RR, choosing a quantum. Do RR practice problems.
8.	What are 3 scheduling algorithms that try to find minimal CPU burst time? How do they work?
9. Do homework problems.

Chapter 2.3 Race Conditions & Coordination/ Synchronization
==================
1.	Give an example of a race condition.
2.	What are critical regions?
3.	What’s mutual exclusion?
4.	How do semaphores work? What’s a binary semaphore?
5.	Solve the Producer-Consumer Problem with semaphores.
6.	What are mutexes?
7.	Solve classical IPC problems such as Reader-Writer’s Problem and Dining Philosopher’s Problem.
8. Do homework problems.


Chapter 6. Deadlocks
==================
1.	When does a deadlock occur? Give an example.
2.	Describe the life history of a resource.
3.	What are the 4 criteria needed for deadlock to occur?
4.	Practice drawing & analyzing resource allocation graphs.
5.	What are the 4 ways to deal with deadlock?
6.	How do we ensure safe states & avoid deadlock?
7.	Discuss Banker’s algorithm – benefits & tradeoffs.
8.	Practice making various states safe, unsafe or deadlocked.
9.	Read 6.9 summary.
10. Do homework problems.

Chapter 3. Memory Management
==================
1.	What is address translation and when should it happen?
2.	Briefly summarize history of monoprogramming vs. multiprogramming.
3.	How are address spaces abstracted? What’s swapping?
4.	Discuss internal vs. external fragmentation.
5.	What is the placement question introduced by MVT and how is it solved?
6.	What is the replacement question?
7.	Give an example of managing memory with a bitmap, or linked list.
8.	How does non-demand paging work? How is it different from demand paging?
9.	Discuss evolution and reasons from evolution of page table to single PTEs to using TLB and multi-level page tables.
10. Do homework problems.

Chapter 3.4 Page Replacement Algorithms
==================
1.	What do we mean by locality (temporal + spatial)?
2.	What are our lower bound & upper bound performance algorithms?
3.	Define how NRU works with pros/ cons.
4.	Define how FIFO works with pros/ cons.
5.	Define how Second Chance PRA works with pros/ cons.
6.	Define how Clock PRA works with pros/ cons.
7.	Define how LRU PRA works. How is it simulated in software with NFU?
8.	What’s the aging PRA?
9.	Define the Working Set PRA policy & algorithms (WS, WSClock).
10.	Overall, what are the general comments we can make for each algorithm?
11. Do homework problems.

Chapter 3.5 Design Issues for Demand Paging
==================
1.	Local vs. Global Allocation?
2.	What’s the Page Fault Frequency algorithm?
3.	Why is load control important?
4.	How do we best determine page size?
5.	Briefly discuss cleaning policy, mapped files and dynamic linking in shared libraries.
6. Do homework problems.

Chapter 3.6 Overall OS + Paging Involvement
==================
1.	When is the OS involved with demand paging?
2.	How are page faults handled?
3.	How are instructions backed up? 
4.	Describe a backing store.
5. Do homework problems.

Chapter 3.7 Segmentation
==================
1.	How is segmentation different from contiguous address spaces?
2.	How is pure segmentation implemented?
3.	Describe demand segmentation & compare & contrast with demand paging.
4.	Discuss internal & external fragmentation as it relates to segmentation.
5.	What happens in demand & non-demand segmentation? (Draw diagrams.)
6.	How can we combine segmentation & paging for best results?
7. Do homework problems.

Chapter 4 File Systems
==================
1.	Briefly look over file access, types, attributes, etc.
2.	Practice path names questions.
3.	What are the directory operations?
4.	How are file systems implemented (partitions)?
5.	Contiguous vs. linked allocation?
6.	FAT
7.	Inode-based directory system implementations
8.	Hard links vs. symlinks
9.	How do we keep track of blocks in directory management?
10.	 What are the 4 phase/ levels of full and incremental dumps?
11.	 Briefly look over history of file systems.
12. Do homework problems.

Chapter 5 Input/ Output
==================
1.	Describe examples of memory-mapped I/O.
2.	How does the DMA save CPU work? 
3.	What are the goals of I/O software?
4.	Describe interrupt handlers, device drivers, kernel I/O, user-level I/O.
5.	Briefly discuss protection & daemons.
6. Do homework problems.

5.4 Disks
==================
1.	How are block sizes chosen?
2.	What are the different RAID levels?
3.	Disk Arm Scheduling Algorithms: Discuss 6.
4.	Describe track caching & rotational latency (origins of term)?
5.	How are disk errors handled?
6. Do homework problems.

5.5 Clocks (Timers) & User Interfaces (Keyboard, Mouse, Monitor)
==================
1.	Describe clock hardware & software.
2.	What’s profiling?
3.	How does input software work (keyboard & mouse)?
4.	Read 5.10.
5. Do homework problems.
