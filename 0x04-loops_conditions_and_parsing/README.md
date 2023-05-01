BASH Scripting - Loops, conditions and parsing
Learning the Use of Loops to automate operations in the unix system

General Objectives
To know how to create SSH keys
To know what the advantage of using #!/usr/bin/env bash over #!/bin/bash
To know how to use while, until and for loops
To know how to use if, else, elif and case condition statements
To know how to use the cut command
To know what files are, other comparison operators, and how to use them
General Requirements
Allowed editors: vi, vim, emacs
All files are interpreted on Ubuntu 20.04 LTS
All files end with a new line
There is a README.md file, at the root of the folder of the project
All Bash script files are executable
Not allowed to use awk
Bash script pass Shellcheck (version 0.7.0) without any error
The first line of all Bash scripts are exactly #!/usr/bin/env bash
The second line of all the Bash scripts has comment explaining what the script doing
More info
Shellcheck is a tool that will help you write proper Bash scripts. It will make recommendations on your syntax and semantics and provide advice on edge cases that you might not have thought about. Shellcheck is your friend! All your Bash scripts must pass Shellcheck without any error or you will not get any points on the task. Also, for every feedback, Shellcheck will provide a code that you can use to get more information about the issue, for example for code SC2034, you can browse https://github.com/koalaman/shellcheck/wiki/SC2034. Shellcheck is available on the school’s computers. If you want to use it on your own computer, here is how to install it. For every feedback, Shellcheck will provide a code that you can use to get more information about the issue, for example for code SC2034, you can browse https://github.com/koalaman/shellcheck/wiki/SC2034.

Resources
Read or watch:

Loops sample
Variable assignment and arithmetic
Comparison operators
File test operators
Make your scripts portable
19 Common SSH Commands in Linux With Examples
Linux and Mac OS users (How do I set up SSH authentication keys)
Windows users (To Generate RSA keys with SSH by using PuTTYgen)
Generate an SSH Key Pair on UNIX and UNIX-Like Systems
How to Create a Public/Private Key Pair
SSH login without password
Files & Description
S/N	File	Description
1.	0-RSA_public_key.pub	To create a RSA key pair.
2.	1-for_best_school	To write a Bash script that displays Best School 10 times.
Requirement:
You must use the for loop (while and until are forbidden)
3.	2-while_best_school	To write a Bash script that displays Best School 10 times.
Requirement:
You must use the for loop (while and until are forbidden)
4.	3-until_best_school	To write a Bash script that displays Best School 10 times.
5.	4-if_9_say_hi	To Write a Bash script that displays Best School 10 times, but for the 9th iteration, displays Best School and then Hi on a new line.
