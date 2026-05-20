Linux
---------------------------------------------------------------
- Open source operating system developed by Linus Torvalds in September 1991.
- Everything in Linux is a represented as file, files are stored in directory and every directory contains file in tree structure. This is called File System Hierarchy.

Ways To Use Linux: 
-----------------
- Download Virtual Box, WSL2, Dual Boot, docker, On Cloud Server, KillerCoda playground, Primary OS as Linux

The core components of Linux (kernel, user space, init/systemd)


Day 02 of my #90DaysOfDevOps journey 🚀

𝗜 𝗹𝗲𝗮𝗿𝗻𝗲𝗱 𝘁𝗵𝗲 𝗯𝗮𝘀𝗶𝗰𝘀 𝗼𝗳 𝗟𝗶𝗻𝘂𝘅, 𝘄𝗵𝘆 𝗶𝘁 𝗶𝘀 𝗶𝗺𝗽𝗼𝗿𝘁𝗮𝗻𝘁 𝗶𝗻 𝗗𝗲𝘃𝗢𝗽𝘀, 𝗮𝗻𝗱 𝗵𝗼𝘄 𝗟𝗶𝗻𝘂𝘅 𝗮𝗰𝘁𝘂𝗮𝗹𝗹𝘆 𝘄𝗼𝗿𝗸𝘀 𝗯𝗲𝗵𝗶𝗻𝗱 𝘁𝗵𝗲 𝘀𝗰𝗲𝗻𝗲𝘀.

Linux is a free and open-source operating system that manages communication between computer hardware and software.
One reason Linux is heavily used in DevOps is because it is lightweight, automation-friendly, and most cloud platforms and production servers run on Linux.

𝗜 𝗮𝗹𝘀𝗼 𝘂𝗻𝗱𝗲𝗿𝘀𝘁𝗼𝗼𝗱 𝘁𝗵𝗲 𝗟𝗶𝗻𝘂𝘅 𝗮𝗿𝗰𝗵𝗶𝘁𝗲𝗰𝘁𝘂𝗿𝗲:

Linux architecture is mainly divided into different layers/components which work together to run the operating system smoothly.

• 𝗛𝗮𝗿𝗱𝘄𝗮𝗿𝗲 𝗟𝗮𝘆𝗲r → Physical components like CPU, RAM, Disk, and Network devices
• 𝗞𝗲𝗿𝗻𝗲𝗹 → The heart of Linux which manages hardware, memory, processes, and system resources
• 𝗦𝗵𝗲𝗹𝗹 → Interface between user and kernel that helps us run commands in human-readable language
• 𝗦𝘆𝘀𝘁𝗲𝗺 𝗟𝗶𝗯𝗿𝗮𝗿𝗶𝗲𝘀 → Help applications communicate with the kernel
• 𝗨𝘀𝗲𝗿 𝗦𝗽𝗮𝗰𝗲 / 𝗔𝗽𝗽𝗹𝗶𝗰𝗮𝘁𝗶𝗼𝗻𝘀 → Programs and tools used by users like Vim, Docker, Nginx, etc.

𝘍𝘰𝘳 𝘦𝘹𝘢𝘮𝘱𝘭𝘦, 𝘸𝘩𝘦𝘯 𝘸𝘦 𝘳𝘶𝘯 𝘢 𝘤𝘰𝘮𝘮𝘢𝘯𝘥 𝘭𝘪𝘬𝘦 `𝙚𝙘𝙝𝙤`, 𝘵𝘩𝘦 𝘴𝘩𝘦𝘭𝘭 𝘱𝘳𝘰𝘤𝘦𝘴𝘴𝘦𝘴 𝘵𝘩𝘦 𝘤𝘰𝘮𝘮𝘢𝘯𝘥 𝘢𝘯𝘥 𝘤𝘰𝘮𝘮𝘶𝘯𝘪𝘤𝘢𝘵𝘦𝘴 𝘸𝘪𝘵𝘩 𝘵𝘩𝘦 𝘬𝘦𝘳𝘯𝘦𝘭 𝘵𝘰 𝘦𝘹𝘦𝘤𝘶𝘵𝘦 𝘪𝘵.

Another important concept I learned today was 𝘀𝘆𝘀𝘁𝗲𝗺𝗱.
systemd is the first process that starts when Linux boots and it manages all other processes and services in the system.
It runs with 𝗣𝗜𝗗 𝟭, which means it is the parent of all system processes.

𝗦𝗼𝗺𝗲 𝗯𝗮𝘀𝗶𝗰 𝗟𝗶𝗻𝘂𝘅 𝗰𝗼𝗺𝗺𝗮𝗻𝗱𝘀 𝗜 𝗽𝗿𝗮𝗰𝘁𝗶𝗰𝗲𝗱 𝘁𝗼𝗱𝗮𝘆:
`cd`, `ls`, `pwd`, `cat`, `echo`, `df -h`, `free -h`, `touch`, `vim`, `htop`, `wc -l` and `cat /etc/os-release`

𝗢𝗻𝗲 𝘂𝘀𝗲𝗳𝘂𝗹 𝗰𝗼𝗺𝗺𝗮𝗻𝗱 𝗜 𝗲𝘅𝗽𝗹𝗼𝗿𝗲𝗱 𝘁𝗼𝗱𝗮𝘆:
systemctl status → used to check service status and logs.

Slowly building strong Linux fundamentals because Linux is the base of almost every production and cloud environment in DevOps. 🙌

