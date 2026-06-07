# Day 2 - Linux Permissions & Git

## Overview

This lab focused on Linux users, groups, file permissions, and Git version control. The goal was to understand how Linux manages file access and how Git tracks project changes.

---

## Commands Learned

### Users and Groups

```bash
id
groups
```

### File Permissions

```bash
touch permissions.txt
ls -l permissions.txt

chmod 755 permissions.txt
chmod 644 permissions.txt
```

### Git Basics

```bash
git init
git status
git add README.md
git commit -m "Initial commit"
git log --oneline
```

---

## Understanding Permissions

### Permission 755

```text
rwxr-xr-x
```

* Owner: Read, Write, Execute
* Group: Read, Execute
* Others: Read, Execute

Used for:

* Scripts
* Directories
* Executable files

### Permission 644

```text
rw-r--r--
```

* Owner: Read, Write
* Group: Read
* Others: Read

Used for:

* Text files
* Configuration files
* Documentation

---

## Git Activities Completed

### Repository Initialization

```bash
mkdir Git-Lab
cd Git-Lab
git init
```

### First Commit

```bash
git add README.md
git commit -m "Initial commit"
```

### Second Commit

```bash
git commit -m "Add Day 2 progress"
```

### Commit History

```bash
git log --oneline
```

Example:

```text
8504dfd Add Day 2 progress
e08ff75 Initial commit
```

---

## Skills Learned

* Linux users and groups
* Linux file permissions
* Permission management using chmod
* Git repository creation
* Git commits
* Version control basics

---

## Lab Outcome

Successfully learned Linux permission management and created a Git repository with multiple commits from Ubuntu Linux.

---

**Author:** uzers090
**Track:** Cybersecurity Learning Journey
