# linuxfundamentalspart2

> Easy | Linux Fundamentals | Date Completed: 4/1/2026

---

## Task 1 - Introduction

> Let's get started!

```
```

---

## Task 2 - Accessing Your Linux Machine Using SSH (Deploy)

> I've successfully connected to the deployed machine using SSH!

```
```

### 📸 Screenshot (SSH Connection Proof - Important)

<img width="954" height="921" alt="Screenshot 2026-04-01 122410" src="https://github.com/user-attachments/assets/65ff5d2e-53ab-4b7b-8cf1-897bcbb07115" />

### Commands Used

```bash
ssh tryhackme@10.66.140.189
```

### Key Concepts

* SSH allows secure remote access to machines
* Used heavily in cybersecurity for remote system interaction ([Medium][1])

---

## Task 3 - Introduction to Flags and Switches

> Explore the manual page of the ls command

```
Done
```

> What directional arrow key would we use to navigate down the manual page?

```
down
```

> What flag would we use to display the output in a "human-readable" way?

```
-h
```

### Commands Used

```bash
man ls
ls -h
ls --help
```

### Key Concepts

* Flags modify command behavior
* `man` pages are critical for learning commands ([Medium][2])

---

## Task 4 - Filesystem Interaction Continued

> How would you create the file named “newnote”?

```
touch newnote
```

> On the deployable machine, what is the file type of “unknown1”?

```
ASCII text
```

> How would we move the file “myfile” to the directory “myfolder”?

```
mv myfile myfolder
```

> What are the contents of this file?

```
THM{FILESYSTEM}
```

> Continue to apply your knowledge and practice the commands

```
Done
```

### 📸 Screenshot (Filesystem Command Proof)

<img width="959" height="917" alt="Screenshot 2026-04-01 130839" src="https://github.com/user-attachments/assets/25d3969f-0d3f-4864-b9bc-8321dd0ed8c7" />

### Commands Used

```bash
touch newnote
file unknown1
mv myfile myfolder
cat file
```

### Key Concepts

* File manipulation is core to Linux operations
* Commands like `mv`, `cp`, `rm`, `file` are used daily in IT/security ([Medium][2])

---

## Task 5 - Permissions 101

> On the deployable machine, who is the owner of “important”?

```
user2
```

> What would the command be to switch to the user “user2”?

```
su user2
```

> Switch to this user

```
Done
```

### 📸 Screenshot (User Switching Proof)

```md
![User Switch](./images/task5-user-switch.png)
```

### Commands Used

```bash
ls -lh
su user2
```

### Key Concepts

* Permissions control access (read, write, execute)
* User switching is important for privilege escalation concepts ([Medium][2])

---

## Task 6 - Common Directories

> What is the directory path where logs are stored?

```
/var/log
```

> What directory is similar to RAM (temporary storage)?

```
/tmp
```

> What is the home directory of the root user?

```
/root
```

> Apply your knowledge and navigate through directories

```
Done
```

### Commands Used

```bash
cd /
cd ~
ls /var/log
```

### Key Concepts

* `/var/log` → system logs (important for SOC analysis)
* `/tmp` → temporary storage (clears on reboot)
* `/root` → root user home directory ([Electronics Reference][3])

---

## Task 7 - Conclusions & Summaries

> Proceed to the next task

```
```

---

## Task 8 - Linux Fundamentals Part 3

> Terminate the machine

```
```

> Continue to Part 3

```
```

---

## Key Takeaways

* SSH is critical for remote system access
* Flags (`-h`, `--help`) enhance command functionality
* File manipulation commands are foundational
* Linux permissions are key for security concepts
* Understanding directories is essential for log analysis

---

## Skills Demonstrated

* Remote access via SSH
* Advanced command usage (flags & switches)
* File system manipulation
* Linux permissions & user management
* Directory navigation & system understanding

---

## Tools Used

* SSH
* Bash
* Linux Terminal
* coreutils

---

[1]: https://iritt.medium.com/linux-fundamentals-part-2-jcyber-security-101-linux-fundamentals-tryhackme-walkthrough-d85f1700b5bf?utm_source=chatgpt.com "Linux Fundamentals Part 2 — Cyber Security 101 - IritT"
[2]: https://medium.com/%40meghraj312002/tryhackme-linux-fundamentals-part-2-walkthrough-d2a55daca7ba?utm_source=chatgpt.com "TryHackMe — Linux Fundamentals Part 2 — Walkthrough"
[3]: https://electronicsreference.com/thm/linux_fundamentals_pt2/?utm_source=chatgpt.com "Linux Fundamentals Part 2 - Complete Walkthrough"
