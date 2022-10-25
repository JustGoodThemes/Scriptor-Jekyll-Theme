---
title: "Linux Background"
layout: post
date: 2022-10-25
feature_image: images/linuxintro.jpg
tags: [linux, basics]
---

#### What is Linux?
Linux is an operating system, just like Windows. Something I didn't know until recently is that Android is actually powered by Linux! Just like iPhones are powered by iOS. It's also in cars, refrigerators, televisions, and more. Linux is incredibly important in cybersecurity.

<!--more-->

### Table of Contents
1. [What is Linux?](#what-is-linux)
2. [Important Components](#important-components)
3. [Why Linux](#why-linux)
4. [Linux Distributions](#linux-distributions)
5. [Linux Commands](#linux-commands)
6. [Sources & Additional Resources](#sources-additional-resources)



#### Important Components
- Bootloader - manages the boot process
- Kernel - the core of the system and lowest level of the operating system that manages the CPU, memory, and <div title = "an internal/external device that connects to a computer but isn't a core component, such as a keyboard, mouse, or speaker" style = "color:#6495ED;">peripheral devices</div>.
- Daemons - background services (consider them servants) that run functions such as printing, scheduling, multimedia and sound during bootup or login. 
- OS Shell - The shell is the command line that lets you control the OS using text. 
- Graphical Server - a subsystem that provides graphics, called the X-server or X.
- Desktop Environment - the desktop that allows users to interact with it, usually what most users see on their screen as the "desktop".
- Applications - software!



#### Why Linux?
Linux is free, reliable, and open source. It's also more customizable and secure with strong support forums.



#### Linux Distributions
Linux distributions or distros are simply different versions that can be downloaded. The right one to use depends on personal preference and usage. Common distros include Debian, Ubuntu, Mint, Red Hat Enterprise Linux, CentOS, Fedora, Kali Linux, Arch Linux, etc.



#### Linux Commands
This is the basic command structure:
```console
Command -options otherParamaters
```
Most commands allow arguments to be provided. You can tell arguments apart as they start with a hyphen (-). Following the hyphen is what is called a flag or switch. 

For example, the command **ls** lists files and directories in the directory. By default, it won't show hidden files. If you provide the **-a** argument (**--all**), it will show all files - including the hidden ones (hidden files and folders begin with periods, ".". 
```console
bash:~$ ls -a
.hello
```

Most commands also have the **--help** flag, which lists the other possible options/arguments that the command can take and a description of it. 

The single most important Linux command is:
man
Manual pages (man for short) provide information and documentation on system commands. The command syntax is:
man *command*

Like so:
```console
bash:~$ man ls
```
which will provide the ls documentation. 


For more on Linux, check out my upcoming blog posts on Linux Fundamentals and Linux Commands !

###### Sources & Additional Resources
https://tryhackme.com/room/linuxfundamentalspart1
https://tryhackme.com/room/linuxfundamentalspart2
https://tryhackme.com/room/linuxfundamentalspart3
https://www.linux.com/what-is-linux/
https://www.plesk.com/blog/various/what-is-linux/
https://people.cs.uchicago.edu/~kaharris/cspp51081/Links/unix-resources/linux-fund.pdf
