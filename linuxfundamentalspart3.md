# linuxfundamentalspart3

> Easy | Linux Fundamentals | Date Completed:

---

## Task 1 - Introduction

> Let's proceed!

```
```

---

## Task 2 - Deploy Your Linux Machine

> I've successfully deployed the machine and connected via SSH!

```
```

### 📸 Screenshot (SSH Connection Proof - Important)

```md
![SSH Connection](./images/task2-ssh.png)
```

### Commands Used

```bash
ssh tryhackme@<IP>
```

### Key Concepts

* SSH is used for remote system access
* Core skill for real-world infrastructure interaction ([Medium][1])

---

## Task 3 - Terminal Text Editors

> Create a file using Nano

```
Done
```

> Edit “task3” located in “tryhackme”’s home directory using Nano. What is the flag?

```
THM{TEXT_EDITORS}
```

### 📸 Screenshot (Nano Editing Proof)

```md
![Nano Editor](./images/task3-nano.png)
```

### Commands Used

```bash
nano filename
```

### Key Concepts

* `nano` is a beginner-friendly text editor
* Editing files directly is essential for configs and scripts ([Medium][2])

---

## Task 4 - General/Useful Utilities

> Ensure you are connected to the deployed instance

```
Done
```

> Start a web server using Python3 HTTPServer

```
Done
```

> Download the file from the web server. What are the contents?

```
THM{WGET_WEBSERVER}
```

> Apply your knowledge and stop the server

```
Done
```

### 📸 Screenshot (Web Server + Wget Proof)

```md
![HTTP Server & Wget](./images/task4-webserver.png)
```

### Commands Used

```bash
python3 -m http.server
wget http://<IP>:8000/.flag.txt
cat .flag.txt
```

### Key Concepts

* Python HTTP server enables quick file hosting
* `wget` is used for downloading files (used in real attacks & enumeration) ([Medium][3])

---

## Task 5 - Processes 101

> If previous process ID was 300, what is the next?

```
301
```

> What signal is used to cleanly kill a process?

```
SIGTERM
```

> Locate the running process. What flag is given?

```
THM{PROCESSES}
```

> Stop the service “myservice”

```
systemctl stop myservice
```

> Enable the service on boot

```
systemctl enable myservice
```

> Bring a backgrounded process to foreground

```
fg
```

### 📸 Screenshot (Process + Service Management Proof)

```md
![Processes](./images/task5-processes.png)
```

### Commands Used

```bash
ps aux
kill
systemctl stop myservice
systemctl enable myservice
fg
```

### Key Concepts

* Processes are identified by PID and managed via signals
* `SIGTERM` safely stops processes
* `systemctl` manages services (critical for Linux servers) ([Medium][4])

---

## Task 6 - Maintaining Your System: Automation

> When will the crontab run?

```
@reboot
```

### Commands Used

```bash
crontab -l
cat /etc/crontab
```

### Key Concepts

* Cron jobs automate tasks
* `@reboot` runs jobs at system startup
* Critical for persistence and automation ([TryHackMe][5])

---

## Task 7 - Maintaining Your System: Package Management

> Read through the material

```
Done
```

### Key Concepts

* Package managers install and update software
* Examples: `apt`, `dpkg`
* Core for maintaining secure systems ([Jasper Alblas][6])

---

## Task 8 - Maintaining Your System: Logs

> What is the IP address of the user who visited the site?

```
10.9.232.111
```

> What file did they access?

```
catsanddogs.jpg
```

### 📸 Screenshot (Log Analysis Proof - Important)

```md
![Log Analysis](./images/task8-logs.png)
```

### Commands Used

```bash
cat /var/log/apache2/access.log
grep
```

### Key Concepts

* Logs are critical for incident response and SOC analysis
* `/var/log` contains system and service logs ([Medium][3])

---

## Task 9 - Conclusions & Summaries

> Completed Linux Fundamentals Part 3

```
```

---

## Key Takeaways

* Text editors (`nano`) are essential for config changes
* File transfer (`wget`) and quick servers are real-world skills
* Process management is critical for system control
* Automation via cron is used everywhere in production
* Logs are foundational for cybersecurity investigations

---

## Skills Demonstrated

* Remote access (SSH)
* File editing and manipulation
* Web server setup & file transfer
* Process and service management
* Automation (cron jobs)
* Log analysis

---

## Tools Used

* SSH
* Bash
* nano
* wget
* python3 HTTPServer
* systemctl
* cron

---
