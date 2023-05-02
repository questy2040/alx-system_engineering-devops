0x05. Processes and signals
Learning the Use of Loops to automate operations in the unix system

General Objectives
To know what a PID is
To know what a process is
To know how to find a process’ PID
To know how to kill a process
To know what a signal is
To know what the 2 signals that cannot be ignored are
General Requirements
Allowed editors: vi, vim, emacs
All files are interpreted on Ubuntu 20.04 LTS
All files end with a new line
There is a README.md file, at the root of the folder of the project
All Bash script files are executable
Not allowed to use awk||awk||awk
Bash script pass Shellcheck (version 0.7.0) without any error
The first line of all Bash scripts are exactly #!/usr/bin/env bash
The second line of all the Bash scripts has comment explaining what the script doing
More info
Shellcheck is a tool that will help you write proper Bash scripts. It will make recommendations on your syntax and semantics and provide advice on edge cases that you might not have thought about. Shellcheck is your friend! All your Bash scripts must pass Shellcheck without any error or you will not get any points on the task. Also, for every feedback, Shellcheck will provide a code that you can use to get more information about the issue, for example for code SC2034, you can browse https://github.com/koalaman/shellcheck/wiki/SC2034. Shellcheck is available on the school’s computers. If you want to use it on your own computer, here is how to install it.

Resources
Read or watch:

Linux PID
Linux process
Linux signal
more aabout Linux signals
Ampersands & on the command line
init.d
Daemon
Positional parameters
man or help:
ps, pgrep, pkill, kill, exit, trap

Files & Description
S/N	File	Description
1.	0-what-is-my-pid	A Bash script that displays its own PID.
2.	1-list_your_processes	A Bash script that displays a list of currently running processes.
3.	2-show_your_bash_pid	A Bash script that displays lines containing the bash word, thus allowing you to easily get the PID of your Bash process.
The third line of your script must be # shellcheck disable=SC2009 (for more info about ignoring shellcheck error here)
4.	3-show_your_bash_pid_made_easy	A Bash script that displays the PID, along with the process name, of processes;
bash PID
script PID (3-show_your_bash_pid_made_easy)
whose name contain the word bash.
5.	4-to_infinity_and_beyond	A Bash script that displays To infinity and beyond indefinitely.
6.	5-dont_stop_me_now	A Bash script that stops 4-to_infinity_and_beyond process.
7.	6-stop_me_if_you_can	A Bash script that stops 4-to_infinity_and_beyond process, without using kill or killall flag.
8.	7-highlander	A Bash script that displays:
To infinity and beyond indefinitely
With a sleep 2 in between each iteration
I am invincible!!! when receiving a SIGTERM signal
9.	8-beheaded_process	A a Bash script that kills the process 7-highlander.
10.	100-process_and_pid_file	A Bash script that:
Creates the file /var/run/myscript.pid containing its PID
Displays To infinity and beyond indefinitely
Displays I hate the kill command when receiving a SIGTERM signal
Displays Y U no love me?! when receiving a SIGINT signal
Deletes the file /var/run/myscript.pid and terminates itself when receiving a SIGQUIT or SIGTERM signal
101.	101-manage_my_process	A Bash (init) script 101-manage_my_process that manages manage_my_process.
102.	102-zombie.c	A C program that creates 5 zombie processes.
