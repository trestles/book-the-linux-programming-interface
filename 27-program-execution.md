# Program Execution

## 27.1 Executing a New Program: `execve()` p563
- Example program p565
## 27.2 The `exec()` Library Functions p567
- 27.2.1 The `PATH` Environment Variable p568
- 27.2.2 Specifying Program Arguments as a List p570
- 27.2.3 Passing the Caller's Environment to the New Program p570
- 27.2.4 Executing a File Referred to by a Descriptor: `fexecve()` p571
## 27.3 Interpreter Scripts p572
- Execution of interpreter scripts p573
- Using the script `optional-arg` p574
- Executing scripts with `execlp()` and `execvp()` p575
## 27.4 File Descriptors and `exec()` p575
- The close-on-exec flag (`FD_CLOEXEC`) p576
## 27.5 Signals and `exec()` p578
## 27.6 Executing a Shell Command: `system()` p579
- Example program p580
- Avoid using `system()` in set-user-ID and set-group-ID programs p581
## 27.7 Implementing `system()` p582
- A simple implementation of `system()` p582
- Treating signals correctly inside `system()` p583
- An improved `system()` implementation p585
- Further details on `system()` p588
## 27.8 Summary p588
- Further Information p588
## 27.9 Exercises p589
