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

- adduser: user + home directory. Interactively
- useradd: adds user
- useradd -m username: user + home directory
- userdel: deletes user but directory and mail spool remians
- userdel -r username: deletes everything completely
---

## Challenges Faced

- I created a user but struggled to locate the home where users are stored. I used the cat/etc/passwrd. It listed all users. But that was not my intent. I found out that i am in the homr directory of the superuser. Instead of the root directory for the server. I had to cd into /. Then ls -a.
- I found it hard to solve this scenario: 

1. You created a user using useradd but with no home directory. To confirm this user was created, I either list everything using  cat/etc/passwd or just grep the user.

Question: how do I delete this user. 
When I run userdel or userdel -r username, it says does not exist. Probably because the home directory is not existing. 

2. I created a user using the adduser or useradd -m username, it creates the user and its  directory in /home. 
Now, I deleted the user. It disappears from the /etc path. But the home directory remains. 
How do everything concerning this user completely....ie user a d home directory.

---

## Key Takeaways

- Users are stored in /etc/passwd, not /home
- /home only contains folders, not actual users
- A user can exist without a home directory
- A folder can exist without a user
---

## Resources

- 

---

## Output

(Include links, screenshots, code snippets, or results)
