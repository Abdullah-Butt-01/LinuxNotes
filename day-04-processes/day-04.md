# Day 04 - Processes

## Objective

Understanding processes and commands

## Commands Practiced

* ps - process status
	* ps aux (a: all users, u: user-oriented format, x: background processes)
 	* ps aux | grep bash (|: pipe output, grep bash: show only lines containing "bash")
* top - live preview of processes
* kill - stop a process
	* kill PID

## what I did

* Ran the "ps" commands and checked the running processes
* Ran the "top" command and checked the real-time processses
* Open two terminals, ran "sleep" command in 1 terminal. checked PID using "ps" in the second terminal, and "kill" command to stop the process.

## Problems Faced

* Using "top" command, stucked in the terminal

## How I fixed

* Find out that entering "q" will exit the "top" command terminal

## Key Learnings

* Usually, plane ps is not used.
* ps aux table:
	* User: Who started the process (root, abd)
	* PID: Process Id
	* %CPU: CPU usage 
	* %MEM: RAM usage
	* STAT: Status (R: Running, S: Sleeping, Z: Zombie(bad))
	* COMMAND: What program (bash, systemd, ssh, docker)
* ps aux | grep [nginx, python, bash]
* "kill" command is used when apps hang, scripts freeze or servers stop respondingsle 
