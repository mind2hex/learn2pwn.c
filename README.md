# learn2pwn.c
Mini proyects to learn C language.

## 1. Basic Tools reimplementation
Programs that simulate the behaviour of basic system tools like cp, rm, ls, whoami, etc.
Learn:
- File Handling
- Syscalls
- Processes
- Pointers
- Structs

## 2. Basic Keylogger
Basic keyboard hook to capture keystrokes.
Learn:
- File Handling
- Stdin/raw mode
- Terms
- /dev/input read

## 3. Sockets, networking and C for cyberperverts
A mini nc tool or a basic chat. (use SSL or OPENSSL)
Learn:
- socket
- bind
- accept
- etc

## 4. Port Scanner tool like nmap
Scan ports using TCP connect or SYN.
Learn:
- sockets
- timers
- concurrence
- multithreading
- etc

## 5. Network Sniffer with libpcap
Capture network packets and filter by protocol/port.
Learn:
- Packet Structures
- Raw Sockets
- Header parsing

## 6. Buffer Overflow vulnerable program
Write a simple vulnerable program, then exploit it with GDB.
Learn:
- StackSmashing
- Shellcode

## 7. Mini shell
A mini shell that execute basic commands (ls, cd, echo, cat, ps, etc)
Learn:
- `fork()`
- `execve()`
- pipes
- signal handling
- input parsing

## 8. Load a shellcode from C
Write a program that read bytes and execute it in memory.
Learn:
- `mprotect()`
- `malloc()`
- `memcpy()`
- `exec`

## 9. Bind/reverse shell
Program that listen and gives a shell or that connects to a remote server and execute `/bin/sh`
Learn:
- sockets
- `dup2()`
- `execve()`

## 10. Mini rootkit userland
Function hooking with `LD_PRELOAD` (hide files, processes)
Learn:
- Intercept syscalls
- fuck what user see

## 11. Static binary analysis
Write a C tool that read an ELF and show the structure (`.text`, `.data`, `symbols`, etc)
Learn:
- ELF format
- How a binary is formed
- offset
- headers

## 12. Crypto tool
Write a program that encrypt data using a XOR encoder/decoder, caesar cipher or vigenere, etc.
Password generator with homemade entrophy
