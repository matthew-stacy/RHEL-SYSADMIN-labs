# How I'm Learning Linux Basics

I started by getting a Red Hat Enterprise Linux (RHEL) 10 VM to boot. From there, I worked through the shell, learned how Linux organizes files, and started combining commands to explore text and logs. I'm using this repo to keep track of the commands I try, what their output tells me, and what I figure out when something goes wrong.

## Start here

If you're new to Linux, start with Lab 01 to set up the practice environment. If you already have a Linux shell, start with Lab 02. Follow the labs in order to build from running a command to combining tools and working at a local console.

| Lab | What you'll learn |
| --- | --- |
| [01 · Set up a Linux VM](01-environment-setup/) | Install RHEL in Hyper-V, troubleshoot a PXE boot screen, and verify the installation. |
| [02 · Get comfortable with the shell](02-essential-tools/) | Read command syntax, identify aliases and built-ins, and practice pipes, redirection, and command history. |
| [03 · Find and manage files](03-essential%20file%20management%20tools/) | Navigate with absolute and relative paths, use wildcards, and inspect mounts, and work with links and archives. |
| [04 · Read and work with text](04-working%20with%20text%20files/) | Browse files with `less`, inspect lines with `head` and `tail`, and filter and count matching lines with `grep` and `wc`. |
| [05 · Use a local Linux console](05-connecting%20to%20Red%20Hat%20Enterprise%20Linux/) | Understand the roles of the console, terminal, and shell, and distinguish graphical and text-based logins. |

## Lab environment

I run RHEL 10 in a Microsoft Hyper-V VM on a Dell Precision workstation. I'm using the *Red Hat RHCSA 10 Cert Guide (EX200)* as a study reference while I build the Linux fundamentals I need for system administration.
