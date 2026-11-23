---
layout: page
title: Unix Shell
description: Linux shell with job control, signal handling, and foreground/background execution.
importance: 2
category: systems
---

Developed a Linux shell supporting foreground and background processes and job control using `fork`, `execve`, and `waitpid`. Implemented `SIGCHLD`, `SIGINT`, and `SIGTSTP` handling, process-group management, and synchronization with signal masking and `sigsuspend` to avoid race conditions and reap zombie processes.
