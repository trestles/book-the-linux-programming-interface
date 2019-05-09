# 59 Sockets: Internet Domains 
## 59.1 Internet Domain Sockets 1197
## 59.2 Network Byte Order p1198
## 59.3 Data Representation p1199
## 59.4 Internet Socket Addresses p1202
- IPv4 socket addresses p1202
- IPv6 socekt addresses p1202
## 59.5 Overview of Host and Service Conversion Functions p1204
## 59.6 The `inet_pton()` and `inet_ntop()` Functions p1206
## 59.7 Client-Server Example (Datagram Sockets) p1207
## 59.8 Domain Name System (DNS) p1209
- Recursive and iterative resolution requests p1211
- Top-level domains p1212
## 59.9 The `/etc/services` File p1212
## 59.10 Protocol-Independent Host and Service Conversion p1213
- 59.10.1 The `getadderinfo()` Function p1213
  - The `hints` argument p1215
- 59.10.2 Freeing `addrinfo` Lists: `freeadderinfo()` p1217
- 59.10.3 Diagnosing Errors: `gai_strerror()` p1217
- 59.10.4 The `getnameinfo()` Function p1218
## 59.11 Client-Server Example (Stream Sockets) p1219
- Common Header File p1219
- Server Program p1219
- Client program p1223 
## 59.12 An Internet Domain Sockets Library p1225
## 59.13 Obsolete APIs for Host and Service Conversions p1230
- 59.13.1 The `inet_aton()` and `inet_ntoa()` Functions p1230
- 59.13.2 The `gethostbyname()` and `gethostbyaddr()` Functions p1231
- 59.13.3 The `getserverbyname()` and `getserverbyport()` Functions p1234
## 59.14 UNIX Versus Internet Domain Sockets p1235
## 59.16 Summary p1236