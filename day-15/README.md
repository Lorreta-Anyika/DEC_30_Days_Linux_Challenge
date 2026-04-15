# Day 15 Understanding Processes

## Objective

What was the goal for today?
- To understand what processes are in Linux, how they function, and how to view, manage, and control them using essential system commands.
---

## What I Learned

- A process is a running instance of a program, and each process has a unique Process ID (PID).
- Processes can have relationships such as parent and child processes, where one process spawns another.
- Foreground processes run directly in the terminal and block further input, while background processes run without interrupting the terminal.
- Commands like ps, top, htop, and pidof help monitor system processes and performance.
- Process control commands like kill, pkill, fg, bg, and jobs are essential for managing running processes.
- 
- 

---

## What I Built / Practiced

- Ran scripts in both foreground and background using & eg. python script.py &
- Used process monitoring commands: ps aux | grep python
top
- Practiced suspending and resuming processes:

- Ctrl + Z: bg || fg

---

## Challenges Faced

- Initially confusing the difference between foreground and background processes.
- Understanding when to use kill vs kill -9 and the risks of forcefully terminating processes.
- Keeping track of PIDs and identifying the correct process among many running ones.

---

## Key Takeaways

- Every command executed in Linux creates a process, making process management a core system skill.
- Background processing improves efficiency by allowing multiple tasks to run simultaneously.
- Monitoring tools like top provide real-time insight into system performance.
- Care must be taken when killing processes to avoid disrupting critical system operations.

---

## Resources

- -  Linux file system[https://github.com/Najeeb-Sulaiman/linux-and-bash-scripting-guide/tree/main/02-linux-commands]

---

## Output

(Include links, screenshots, code snippets, or results)
