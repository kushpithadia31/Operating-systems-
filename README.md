![Profile Views](https://komarev.com/ghpvc/?username=YOUR_USERNAME&style=for-the-badge)

![GitHub stars](https://img.shields.io/github/stars/YOUR_USERNAME/REPO_NAME?style=for-the-badge)

![GitHub forks](https://img.shields.io/github/forks/YOUR_USERNAME/REPO_NAME?style=for-the-badge)

![GitHub last commit](https://img.shields.io/github/last-commit/YOUR_USERNAME/REPO_NAME?style=for-the-badge)
# 🐧 UNIX Important Commands – A Practical Guide

## Introduction

The UNIX operating system has been the foundation of modern computing for decades. Most modern operating systems, including Linux and macOS, inherit many concepts from UNIX. One of the biggest strengths of UNIX is its powerful Command Line Interface (CLI), which enables users to perform tasks quickly and efficiently.

As part of the **Complete UNIX & Linux OS Fundamentals Training** on **Infosys Springboard**, I explored the essential UNIX commands that are commonly used for file management, process handling, user administration, networking, and system monitoring. This article summarizes the most important commands along with their purpose and practical examples.

---

## Why Learn UNIX Commands?

Unlike graphical interfaces, UNIX commands allow users to interact directly with the operating system. They are widely used by:

- Software Developers
- System Administrators
- Cybersecurity Professionals
- DevOps Engineers
- Cloud Engineers

Learning these commands improves productivity and provides a deeper understanding of how an operating system works.

---

# 1. Navigating the File System

Navigation is one of the first skills every UNIX user should master.

### Print Current Directory

```bash
pwd
```

Displays the current working directory.

Example Output:

```text
/home/kush/Documents
```

---

### List Files and Directories

```bash
ls
```

Shows all visible files.

For detailed information:

```bash
ls -l
```

To include hidden files:

```bash
ls -la
```

---

### Change Directory

```bash
cd Desktop
```

Move to Desktop directory.

```bash
cd ..
```

Move one directory back.

---

# 2. Creating and Managing Files

Creating files and folders is a basic administrative task.

### Create a Directory

```bash
mkdir Projects
```

Creates a folder named **Projects**.

---

### Create an Empty File

```bash
touch notes.txt
```

Creates a new empty text file.

---

### Copy Files

```bash
cp notes.txt backup.txt
```

Copies one file to another.

---

### Move or Rename Files

```bash
mv notes.txt LinuxNotes.txt
```

Moves or renames files.

---

### Delete Files

```bash
rm notes.txt
```

Deletes a file permanently.

Delete an entire folder recursively:

```bash
rm -r Projects
```

---

# 3. Reading File Contents

Viewing files from the terminal avoids opening graphical applications.

### Display Entire File

```bash
cat notes.txt
```

---

### Display First 10 Lines

```bash
head notes.txt
```

---

### Display Last 10 Lines

```bash
tail notes.txt
```

Useful for monitoring log files.

```bash
tail -f server.log
```

---

# 4. Searching Files

Finding information quickly is essential in UNIX.

### Search Text

```bash
grep "error" log.txt
```

Searches for the word **error**.

Ignore uppercase/lowercase:

```bash
grep -i error log.txt
```

---

### Find Files

```bash
find . -name report.txt
```

Searches for a file in the current directory.

---

# 5. File Permissions

UNIX provides a permission system to protect files.

View permissions:

```bash
ls -l
```

Example:

```text
-rwxr-xr--
```

Grant execute permission:

```bash
chmod +x script.sh
```

Change ownership:

```bash
chown username file.txt
```

---

# 6. Process Management

Every running application is known as a process.

Display running processes:

```bash
ps
```

Live process monitoring:

```bash
top
```

Terminate a process:

```bash
kill PID
```

Force terminate:

```bash
kill -9 PID
```

---

# 7. User Information

Current logged-in user:

```bash
whoami
```

Display user ID:

```bash
id
```

Show all logged-in users:

```bash
who
```

---

# 8. Disk and Memory Information

Check available disk space:

```bash
df -h
```

Check folder size:

```bash
du -sh Downloads
```

View memory usage:

```bash
free -h
```

---

# 9. Networking Commands

Check internet connectivity:

```bash
ping google.com
```

Display IP address:

```bash
ip addr
```

Download files:

```bash
wget https://example.com/file.zip
```

Retrieve web content:

```bash
curl https://example.com
```

---

# 10. Compression Commands

Create an archive:

```bash
tar -cvf project.tar Project/
```

Extract archive:

```bash
tar -xvf project.tar
```

Compress using gzip:

```bash
gzip file.txt
```

---

# Common Keyboard Shortcuts

| Shortcut | Function |
|----------|----------|
| Ctrl + C | Stop current process |
| Ctrl + Z | Suspend process |
| Ctrl + D | Exit terminal |
| Ctrl + L | Clear screen |
| Ctrl + R | Search command history |
| Tab | Auto-complete commands |

---

# Sample Practice Session

```bash
mkdir LinuxLab
cd LinuxLab

touch notes.txt

echo "Learning UNIX Commands" > notes.txt

cat notes.txt

cp notes.txt backup.txt

ls -l

chmod +x notes.txt

pwd
```

---

# Key Takeaways

- UNIX commands provide complete control over the operating system.
- Command-line tools are significantly faster than graphical interfaces for repetitive tasks.
- Understanding file permissions enhances system security.
- Process management commands help monitor and control running applications.
- Networking and system monitoring commands are essential for Linux administrators and cybersecurity professionals.

---

# Conclusion

Mastering UNIX commands is an essential step for anyone pursuing careers in software development, cybersecurity, cloud computing, or system administration. While graphical interfaces simplify everyday tasks, the command line offers unmatched flexibility, automation, and control.

The **Complete UNIX & Linux OS Fundamentals Training** on **Infosys Springboard** provided practical exposure to these core commands and strengthened my understanding of UNIX-based operating systems. This article serves as a concise reference for the most frequently used UNIX commands and their real-world applications.

---

**Author:** Kush Pithadiya  
**Course:** Complete UNIX & Linux OS Fundamentals Training  
**Platform:** Infosys Springboard
