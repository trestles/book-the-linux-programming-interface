
# 26 Monitoring Child Processes 

## 26.1 Waiting on a Child Process 
- 26.1.1 The `wait()` System Call p541
- 26.1.2 The `waitpid()` System Call p544
- 26.1.3 The Wait Status Value p545
  - example program p546
- 26.1.4 Process Termination from a Signal Handler p549
- 26.1.5 The `waitid()` System Call p550
- 26.1.6 The `wait3()` and `wait4()` System Calls p552
## 26.2 Orphans and Zombies p553
## 26.3 The `SIGCHLD` Signal p555
- 26.3.1 Estabishing a Handler for `SIGCHLD` p555
  - Design issues for `SIGCHLD` handlers p556
  - Example program p556
- 26.3.2 Delivery of `SIGCHLD` for Stopped Children p559
- 26.3.3 Ingoring Dead Child Processes p559
  - Deviations from SUSv3 in older Linux kernels p560
  - The `sigaction()` SA_NOCLDWAIT flag p560
  - The System V `SIGCHLD` signal p561
## 26.4 Summary p561
## 26.5 Exercises p562