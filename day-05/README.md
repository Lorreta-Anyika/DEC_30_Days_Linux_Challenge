# Day 05 - Redirection and Pipes || Chaining and Combining Commands

## Objective

What was the goal for today?

- Understand command in Linux used in three data streams: stdin, stdout, stderr
- Learn to chain commands for sequential, individual order
---

## What I Learned
1. stdin:

When we write a command, that is the input. 

2. stdout:

What displays on screen (terminal is standard output). If I don't want it to appear on the screen, then i redirect it.

Example: echo "Hello". The "Hello" here is the standard input. The output is still Hello as shown on my screen. 

Now instead of displaying this output on my screen, I can **redirect** it to a file: echo "Hello" file.txt

Using the ">" writes into the file and overwrites what was there. However, ">>" adds to file but don’t replace.


3. Pipes (|): Instead of saving to a file, I can send output directly to another command. 
syntax: command1 | command2.

This implies the output of command1 is sent as input for command2

4. < : to send the content of a file as input to a command

---

## What I Built / Practiced

- ">"
- ">>"
- <
- |
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

![1](image.png)