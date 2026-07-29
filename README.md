<div align="center">

# 🐧 UNIX Important Commands
### *A Practical Guide to Essential UNIX & Linux Terminal Commands*

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=00FF88&center=true&vCenter=true&width=650&lines=Complete+UNIX+%26+Linux+OS+Fundamentals;Infosys+Springboard+Course+Notes;Essential+UNIX+Commands;Cybersecurity+Student+Reference" />

<p align="center">

![Linux](https://img.shields.io/badge/Linux-UNIX-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Shell](https://img.shields.io/badge/Shell-Bash-4EAA25?style=for-the-badge&logo=gnubash)
![Platform](https://img.shields.io/badge/Platform-Infosys%20Springboard-0078D4?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

</p>

---

*"The command line is where real control begins."*

</div>

# 📖 Introduction

The UNIX operating system has served as the backbone of modern computing for over five decades. Many popular operating systems, including **Linux** and **macOS**, are built upon UNIX concepts, making UNIX knowledge a valuable skill for software developers, cybersecurity professionals, system administrators, and DevOps engineers.

This repository documents the important commands learned during the **Complete UNIX & Linux OS Fundamentals Training** offered by **Infosys Springboard**. Rather than simply listing commands, this guide explains **what each command does**, **why it is important**, and **where it is commonly used**.

---

# 📚 Table of Contents

- Introduction
- Why Learn UNIX?
- File & Directory Navigation
- File Management
- Viewing File Contents
- Searching Files
- User Management
- Process Management
- File Permissions
- Disk & Memory Monitoring
- Networking Commands
- Compression Commands
- Practice Session
- Key Learnings
- Conclusion

---

# 🚀 Why Learn UNIX?

> Modern servers, cloud platforms, and cybersecurity tools all rely heavily on Linux/UNIX systems.

### Learning UNIX helps you:

✅ Understand Operating Systems

✅ Work with Linux Servers

✅ Perform System Administration

✅ Automate Tasks

✅ Learn Shell Scripting

✅ Build Cybersecurity Skills

---

# 📂 File & Directory Navigation

## Print Current Directory

```bash
pwd
```

📌 Displays your current working directory.

---

## List Files

```bash
ls
```

Lists all visible files.

### Long Listing

```bash
ls -l
```

Shows

- Permissions
- Owner
- File Size
- Date
- File Name

---

## Hidden Files

```bash
ls -la
```

Displays hidden files beginning with `.`

---

## Change Directory

```bash
cd Desktop
```

Move into Desktop.

```bash
cd ..
```

Move back one directory.

---

# 📁 File Management

### Create Directory

```bash
mkdir LinuxLab
```

Creates a new directory.

---

### Create Empty File

```bash
touch notes.txt
```

---

### Copy File

```bash
cp notes.txt backup.txt
```

---

### Rename File

```bash
mv notes.txt unix_notes.txt
```

---

### Delete File

```bash
rm notes.txt
```

⚠ **Warning:** Deleted files cannot be recovered using `rm`.

---

# 📖 Reading Files

Display file contents

```bash
cat notes.txt
```

View first 10 lines

```bash
head notes.txt
```

View last 10 lines

```bash
tail notes.txt
```

Monitor live log

```bash
tail -f server.log
```

---

# 🔍 Searching

Search for a word

```bash
grep "error" log.txt
```

Search ignoring uppercase/lowercase

```bash
grep -i error log.txt
```

Find files

```bash
find . -name notes.txt
```

---

# 🔐 File Permissions

View permissions

```bash
ls -l
```

Example

```text
-rwxr-xr--
```

Give execute permission

```bash
chmod +x script.sh
```

Change owner

```bash
chown username file.txt
```

---

# ⚙ Process Management

View running processes

```bash
ps
```

Real-time monitoring

```bash
top
```

Terminate process

```bash
kill PID
```

Force terminate

```bash
kill -9 PID
```

---

# 🌐 Networking

Check connectivity

```bash
ping google.com
```

Display IP Address

```bash
ip addr
```

Download files

```bash
wget URL
```

Retrieve webpage

```bash
curl URL
```

---

# 💾 Disk Monitoring

Disk Usage

```bash
df -h
```

Folder Size

```bash
du -sh Downloads
```

RAM Usage

```bash
free -h
```

---

# 📦 Compression

Create Archive

```bash
tar -cvf project.tar Project
```

Extract Archive

```bash
tar -xvf project.tar
```

Compress

```bash
gzip file.txt
```

---

# 💻 Practice Session

```bash
mkdir UNIX_Practice

cd UNIX_Practice

touch notes.txt

echo "Learning UNIX Commands" > notes.txt

cat notes.txt

cp notes.txt backup.txt

ls -la

pwd

chmod +x notes.txt
```

---

# 💡 Key Learnings

> 📌 Command-line interfaces provide faster and more efficient system interaction.

> 📌 UNIX permissions ensure secure access control.

> 📌 Process management commands help monitor running applications.

> 📌 Networking commands assist in troubleshooting connectivity issues.

> 📌 UNIX commands form the foundation of Linux administration and cybersecurity.

---

# 🎯 Conclusion

Completing the **Complete UNIX & Linux OS Fundamentals Training** strengthened my understanding of the UNIX operating system and its command-line environment. Mastering these commands is an essential step toward becoming proficient in Linux administration, cloud computing, DevOps, and cybersecurity.

This repository serves as a quick reference guide and a demonstration of the concepts learned throughout the course.

---

<div align="center">

## ⭐ If you found this repository useful, consider giving it a star!

### Made with ❤️ by **Kush Pithadia**

**Cybersecurity Student • Linux Enthusiast • Future Security Engineer**

</div>
