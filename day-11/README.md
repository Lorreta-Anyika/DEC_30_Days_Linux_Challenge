# Day 11 - sers and Groups contd.

## Objective

What was the goal for today?
Go deeper into user, groups and permissions

---

## What I Learned

- As the root user, I do not need sudo to adduser. I just ran: adduser test. It adds the user in an interactive manner; asking for personal details. This is contrary to what useradd does. The useradd just  creates the user without asking for password or personal details. 
- userdel: this deletes a user. However it still appears in the home directory. By default, the userdel command does not remove the user's home directory and mail spool. To delete these as well, use the -r option: (sudo) userdel -r username
- useradd creates the user but does not create a home directory for it. That is why when i userdel the user, it does not exist inside the home. Users created with useradd live in etc/passwd. 
- the etc/passwd gives a list of users. 
- The /home containers directories/folders of the users.

---

## What I Built / Practiced

- 
- 

---

## Challenges Faced

- I created a user but struggled to locate the home where users are stored. I used the cat/etc/passwrd. It listed all users. But that was not my intent. I found out that i am in the homr directory of the superuser. Instead of the root directory for the server. I had to cd into /. Then ls -a.
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
