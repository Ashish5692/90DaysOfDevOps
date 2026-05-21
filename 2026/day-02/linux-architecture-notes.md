Day 02 of my #90DaysOfDevOps journey 🚀

Linux
---------------------------------------------------------------
- Open source operating system developed by Linus Torvalds in September 1991.
- Linux is a free and open-source operating system that manages communication between computer hardware and software.
One reason Linux is heavily used in DevOps is because it is lightweight, automation-friendly, and most cloud platforms and production servers run on Linux.
- Everything in Linux is a represented as file, files are stored in directory and every directory contains file in tree structure. This is called File System Hierarchy.

Ways To Use Linux: 
-----------------
- Download Virtual Box, WSL2, Dual Boot, docker, On Cloud Server, KillerCoda playground, Primary OS as Linux

Linux Architecture Working
--------------------------
Linux works on ASK principal and it is based on CLI.
A- Application / User space - Program and tools used by user like VIM, Docker, Nginx etc.
S- Shell - Interactive way to talk to kernel. It is GUI interface between user and kernel that helps to run shell commands in human readable format. User talk to shell. Shell through commands talks to kernel using its commands
K - Kernel - Kernel talks to hardware, it is C program, heart of linux that manages hardware, memory, processes and system resources.
H - Hardware - Physical components like Monitor, Printer, Speaker, Mic etc.

 - Linux Flavors: Ubuntu, Fedora, CentOS, RHEL(RedHat) Enterprises

 - Shell VS Terminal - Through shell user commnicates with Linux kernel
 Terminal is place where shell is accessible.

𝘍𝘰𝘳 𝘦𝘹𝘢𝘮𝘱𝘭𝘦, 𝘸𝘩𝘦𝘯 𝘸𝘦 𝘳𝘶𝘯 𝘢 𝘤𝘰𝘮𝘮𝘢𝘯𝘥 𝘭𝘪𝘬𝘦 `𝙚𝙘𝙝𝙤`, 𝘵𝘩𝘦 𝘴𝘩𝘦𝘭𝘭 𝘱𝘳𝘰𝘤𝘦𝘴𝘴𝘦𝘴 𝘵𝘩𝘦 𝘤𝘰𝘮𝘮𝘢𝘯𝘥 𝘢𝘯𝘥 𝘤𝘰𝘮𝘮𝘶𝘯𝘪𝘤𝘢𝘵𝘦𝘴 𝘸𝘪𝘵𝘩 𝘵𝘩𝘦 𝘬𝘦𝘳𝘯𝘦𝘭 𝘵𝘰 𝘦𝘹𝘦𝘤𝘶𝘵𝘦 𝘪𝘵.

Some Linux Commands
-------------------
uname - r : tells version/release of linux
ls -l , cd , pwd , man , find, touch, cp, mv, rm, ping, ip addr, htop, df-h, free(tells free/used storage), 

bin -> user/bin
bin - binaries - 101010
cd(shell program) -> c program -> binaries
sbin -> system binaries - help in checking storage(includes LVM) & others 
cd - built in command to navigate the shell, it is not sbin

Understanding of Everything is a process
----------------------------------
Power ON
BIOS - when we do power on , BIOS supply power supply to Motherboard which loads the hardware.

GNU GRUB - Harware ask GNU to load Linux Kernel. It shows logo of unbuntu loading...
When there is ubuntu loading, then a process is initialized called as init process/ systemd. Its process id is 1 (PID-1)

systemd - System - OS , d- daemon(runs in background) -         it is the first process that starts when the Linux boots and it manages all other processes in the system,
It runs with PID - 1 means it is parent of all system processes.

systemctl - system controller - I f we have any software installed and we want to run it as a process we write
systemctl start nginx
systemctl start docker
systemctl start ssh

systemctl status → used to check service status and logs.
systemctl status docker
systemctl status ssh

cp SRC DEST - means cp(it is a process) -> bin -> c prog -> comp language

About Processes
---------------
ps - show processes
ps -a - show active running processes
ps aux - show all proccess running in system
top - active running processes

ps aux | grep ping - used to find and display specific running processes on Linux system that matches a given pattern.It is comman technique for system monitoring and troubleshooting.

2 mantras of Linux
------------------
- Everything in linux is file or directory.
- Everything in linux starts with process


