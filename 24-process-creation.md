## 24 Process Creation
## 24.1 Overview of `fork()`, `exit()`, `wait()`, and `execve()` p513
## 24.2 Creating a New Process: `fork()` p515
- 24.2.1 File Sharing Between Parent and Child p517
- 24.2.2 Memory Semantics of `fork()` p520
  - Controlling a process's memory footprint p521
## 24.3 The `vfork()` System Call p522
## 24.4 Race Conditions after `fork()` p525
## 24.5 Avoiding Race Conditions by Synchronizing With Signals p527
## 24.6 Summary p529