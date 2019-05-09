
## 21 Signals: Signal Handlers
## 21.1 Designing Signal Handlers 
- 21.1.1 Singals Are Not Queued (Revisited) p422
- 21.1.2 Reentrant and Async-Signal-Safe Functions p422
  - Reentrant and nonreentrant functions p422
  - Example program p424
  - Standard async-signal-safe functions p425
  - Use of `errno` inside signal handlers p427
  - Use of unsafe functions in example programs in this book p427
- 21.1.3 Global variables and the `sig_atomic_t` Date Type p428
## 21.2 Other Methods of Terminating a Signal Handler p428
- 21.2.1 Performing a Nonlocal Goto from a Signal Handler p429
  - Example program p430
- 21.2.2 Terminating a Process Abnormally: `abort()` p433
## 21.3 Handling a Signal on an Alternate Stack: `signalstack()` p434
## 21.4 The `SA_SIGINFO` Flag p437
- The `siginfo_t` structure p438
- The `ucontext` argument p442
## 21.5 Interruption and Restarting of System Calls p442
- System calls (and library functions) for which `SA_RESTART` is effective p443
- Modifying the `SA_RESTART` flag for a signal p444
- Unhandled stop signals can generate `EINTR` for some Linux system calls p445
## 21.6 Summary p445
## 21.7 Exercise p446