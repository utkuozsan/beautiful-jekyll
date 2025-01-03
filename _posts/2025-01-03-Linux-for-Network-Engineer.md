---
layout: post
title: Linux for Network Engineer
subtitle: 
tags: [Linux]
#image: /img/markdown.jpg
#bigimg: /img/markdown.jpg
#gh-repo: daattali/beautiful-jekyll
#gh-badge: [star, fork, follow]
comments: true
---

# What is a Kernel, and What does it Do?

The **kernel** is the special piece of the operating system that controls 
    - the CPU hardware, 
    - allocates memory 
    - accesses data
    - schedules processes 
    - runs the applications
    - protects them from each other
It is the first program loaded on the computer when the computer starts up. The most critical pieces of code in the kernel are loaded into protected areas of memory so that they cant be overwritten by other applications running in the operating system.

# What is an Operating System?

Hardware -> Kernel -> Operating System => Libraries, System Daemons, Shells, Tools
# What is the boot process ?
Note: Explain the booting process here

# What is Linux Daemon?
A system daemon in Linux is typically a background system process that awaits a specific set of conditions before jumping into action.

For example, your Linux system may have a daemon called sshd. This system daemon runs in the background and accepts authorized incoming requests to log into the Linux host.

System daemons do not interact with users and are not typically under the direct control of users, but rather of the system itself. 

# User Space vs Kernel Space 

