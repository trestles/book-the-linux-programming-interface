## 44 Pipes and FIFOs p889
## 44.1 Overview p889
- A pipe is a byte stream p890
- Reading from a pipe p890
- Pipes are unidirectional p890
- Writes of up to PIPE_BUF bytes are guaranteed to be atomic p891
- Pipes have a limited capacity p891
## 44.2 Creating and Using Pipes p892
- Fig44-2 Process file descriptors after creating a pipe p892
- Fig44-3 Setting up a pipe to transfer data from a parent to a child p893
- Listing44-1 Steps in creating a pipe to transfer data from a parent to a child p893
- Pipes allow communication between related processes p894
- Closing unused pipe file descriptors p894
- Example program p895
## 44.3 Pipes as a Method of Process Synchronization p897
## 44.4 Using Pipes to Connect Filters p899
- Example program p900
## 44.5 Talking to a Shell Command via a Pipe: popen()
- Example program p903
- Listing 44-5 Globbing filename patterns with popen() p904
## 44.6 Pipes and `stdio` Buffering p906
## 44.7 FIFOs p906
- Using FIFOs and `tee(1)` to create a dual pipeline p908
## 44.8 A Client-Server Application Using FIFOs p909
- Application overview p909
- Fig44-6 Using FIFOs in a single-server, multiple-client application p910
- Fig44-7 Seperating messages in a byte stream p911
- Listing 44-6 Header file for fifo_seqnum_server.c and fifo_seqnum_client.c p911
- Server program p912
- Client program p914
## 44.9 Nonblocking I/O p915
- Table 44-1 Semantics of open() for a FIFO p916
## 44.10 Semantics of `read()` and `write()` on Pipes and FIFOs p917
## 44.11 Summary p918
## 44.12 Exercises p919