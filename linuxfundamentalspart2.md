# linuxfundamentalspart1

> Easy | Linux Fundamentals | Date Completed:

---

## Task 1 - Introduction

> Let's get started!

```
```

---

## Task 2 - A Bit of Background on Linux

> Research: What year was the first release of a Linux operating system?

```
1991
```

### Key Concepts

* Linux is an open-source operating system created by Linus Torvalds
* Widely used in servers, cybersecurity, and cloud environments

---

## Task 3 - Interacting With Your First Linux Machine (In-Browser)

> I've deployed my first Linux machine!

```
```

### Key Concepts

* Linux is primarily interacted with through the terminal (CLI)
* TryHackMe provides a browser-based VM

---

## Task 4 - Running Your First Few Commands

> If we wanted to output the text "TryHackMe", what would our command be?

```
echo TryHackMe
```

> What is the username of who you're logged in as on your deployed Linux machine?

```
tryhackme
```

### 📸 Screenshot (Command Execution Proof)

```md
![Command Output](./images/task4-command-output.png)
```

### Commands Used

```bash
echo TryHackMe
whoami
```

### Key Concepts

* `echo` outputs text
* `whoami` identifies current user

---

## Task 5 - Interacting With the Filesystem!

> On the Linux machine that you deploy, how many folders are there?

```
4
```

> Which directory contains a file?

```
folder4
```

> What is the contents of this file?

```
Hello World
```

> Use the cd command to navigate to this file and find out the new current working directory. What is the path?

```
/home/tryhackme/folder4
```

### 📸 Screenshot (Filesystem Navigation Proof)

```md
![Filesystem Navigation](./images/task5-filesystem.png)
```

### Commands Used

```bash
ls
cd
cat
pwd
```

### Key Concepts

* File navigation is foundational in Linux

---

## Task 6 - Searching for Files

> Use grep on “access.log” to find the flag that has a prefix of “THM”. What is the flag?

```
[fill this in]
```

### 📸 Screenshot (Log Analysis Proof - Important)

```md
![Grep Flag Output](./images/task6-grep-flag.png)
```

### Commands Used

```bash
grep "THM" access.log
```

### Key Concepts

* `grep` is critical for log analysis (SOC-level skill)

---

## Task 7 - An Introduction to Shell Operators

> If we wanted to run a command in the background, what operator would we want to use?

```
&
```

> If I wanted to replace the contents of a file named “passwords” with the word “password123”, what would my command be?

```
echo password123 > passwords
```

> Now if I wanted to add “tryhackme” to this file named “passwords” but also keep “password123”, what would my command be?

```
echo tryhackme >> passwords
```

### Commands Used

```bash
&
>
>>
```

### Key Concepts

* `>` overwrite vs `>>` append
* `&` runs processes in background

---

## Task 8 - Conclusions & Summaries

> Proceed to the next room

```
```

---

## Key Takeaways

* Linux CLI is essential for cybersecurity roles
* Core commands: `ls`, `cd`, `cat`, `pwd`, `grep`
* Log searching (`grep`) is directly applicable to SOC work
* Shell operators control command behavior

---

## Skills Demonstrated

* Linux command-line usage
* File system navigation
* Basic log analysis
* Command execution

---

## Tools Used

* Linux Terminal
* Bash
* grep
* coreutils

---
