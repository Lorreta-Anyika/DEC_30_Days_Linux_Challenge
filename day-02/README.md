# Day 02 - Linux File System

## Objective

What was the goal for today?
- Know where I am
- Know how to move
- Know what exists where I am
---

## What I Learned
1. Know where I am
To understand where I am, I either run the "pwd" or "whoami" commands. At first I found myself in the "/root" and it is flagged by "~". My sources called it home. But I did not understand. So I needed to move around.

2. Know how to move
To move, I used the "cd" and its variants such as "cd .." to move one step back. Doing this landed me inside the "/", called root. Also running the "cd /" still landed me inside the root straight up. I still did not understand their differences. 

- I needed to understand the differences between the root and home directory. So I explored more. I decided to understand what exists where I am. 

3. Know what exists where I am
To know what exists where i am, I ran the "ls", "ls -a", "ls -lh", and "ls -lh /home"
- ls displays all files in my current directory
- ls -a displays all hidden files
- ls -lh displays the files in long and human readable format: shows the file permissions, size of the file, date modified, etc.

Moving into the /, and running ls, i noticed that the files inside ~ do not appear here. 
Because the / is like the entire building, it houses files including home, /bin, /etc and so on. 

These make up the linux file system. I will be describing these shortly. 

---

## What I Built / Practiced

- 
- 

---

## Challenges Faced

- 
- 

---

## Key Takeaways

- 
- 

---

## Resources

- 

---

## Output

(Include links, screenshots, code snippets, or results)
