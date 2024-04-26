### Table of Contents
- [kernel](#kernel)
  - [tasks performed by the kernel](#tasks-performed-by-the-kernel)
  - [kernel mode and user mode](#kernel-mode-and-user-mode)
  - [process versus kernel views of the system](#process-versus-kernel-views-of-the-system)
- shell
- users and groups
- directory hierarchy(directories,links and files)
- file I/O
- program
- processes
- memory mapping
- static and shared libraries
- interprocess communication and synchronization
- signals
- threads
- process groups and shell job control
- sessions, controlling terminals, and controlling processes
- pseudoterminals
- date and time
- client-server architecture
- realtime
- /proc

# Fundamental Concepts
![](images/kernel-arch.png "overview")

### kernel
##### short notes
##### description
&ensp;&ensp;&ensp;&ensp;အဓိက core operating system က kernel ပါ။ kernel ထဲမှာ command-line interpreters, graphical user interfaces, file utilities, text editiors လိုမျိုး **standard software tool** တွေပါဝင်တယ်။
#### tasks performed by the kernel
- [process](../process/process.md) scheduling
- [memory](../memory/memory.md) management
- [files](../file/file.md) operation
- creation and termination of [processes](../process/process.md)
- access to devices
- networking
- api for system call.
#### kernel mode and user mode
#### process versus kernel views of the system