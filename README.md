## 🛡️ Linux Fundamentals Part 3

**Room:** [Linux Fundamentals Part 3 — TryHackMe](https://tryhackme.com/room/linuxfundamentalspart3)  
**Status:** ✅ Completed  
**Date:** 28 April 2025  

### 🎯 Objective
This room focused on getting more hands-on with Linux.  
The goal was to practise deploying Linux machines, working with text editors, using file transfer tools, managing processes, automating tasks, handling software packages, and reading system logs.

---

### 🗝️ Key Concepts  
- Deploying and accessing Linux machines over SSH.  
- Using terminal text editors (`nano`) to edit files directly from the command line.  
- Downloading and transferring files using `wget`, `scp`, and simple Python web servers.  
- Managing system processes using `ps`, `top`, `kill`, and controlling services with `systemctl`.  
- Setting up automated tasks using `cron` and `crontab`.  
- Managing installed software and repositories with `apt` and `add-apt-repository`.  
- Understanding system logs stored under `/var/log` for services like Apache2.

---

### 🛠️ Tools Used  
- `nano` — Editing text files within the terminal.  
- `wget`, `scp`, `python3 -m http.server` — Downloading and transferring files.  
- `ps`, `top`, `kill`, `systemctl` — Viewing and managing processes.  
- `cron`, `crontab` — Automating repetitive tasks.  
- `apt`, `add-apt-repository` — Installing and removing software.  
- `/var/log` — Analysing system and service logs.

---

### ⚠️ Challenges Faced  
- Remembering all the different file transfer methods was a little confusing at first (wget vs scp vs HTTP server).  
- Using `systemctl` to control processes felt new compared to basic `kill` commands.  
- Reading through the `/var/log` directory and knowing which logs were important took practice — but looking at examples like `access.log` and `auth.log` made it easier.

---

### 🧠 What I Learned  
- How to securely connect to machines using SSH and basic credentials.  
- Confidence using `nano` to edit files quickly without needing a graphical interface.  
- How to download, serve, and transfer files between machines using terminal-based methods.  
- Process management, including viewing, killing, and backgrounding tasks.  
- Setting up basic cron jobs for task automation.  
- How software packages are managed in Linux and the difference between `apt` and `dpkg`.  
- Where to find and how to read system logs to spot security issues or service failures.

---

### 🌐 Real-World Application:  
> Transferring files, monitoring processes, automating tasks, managing packages, and reviewing logs are all core responsibilities for Linux system administrators and cyber security professionals.  
> These skills help in server maintenance, incident response, and ensuring uptime and security.

---

### 💭 Reflections:  
- Connecting over SSH felt empowering — understanding remote access is crucial for real-world environments.  
- Editing with `nano` was easy and practical, especially for quick configuration changes.  
- Learning how to monitor running services and control them with `systemctl` showed how Linux services stay running.  
- Reading log files like `access.log` and `auth.log` made it clear how valuable logging is for both security and system health.  
