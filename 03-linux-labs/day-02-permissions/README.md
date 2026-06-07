# Day 2 - Linux Permissions & Git

## Overview

This lab focused on Linux users, groups, file permissions, and Git version control. The goal was to understand how Linux manages access to files and how Git tracks changes in projects.

---

## Commands Learned

### Users & Groups

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

## Understanding Linux Permissions

### Permission 755

```text
rwxr-xr-x
```

| User Type | Permissions          |
| --------- | -------------------- |
| Owner     | Read, Write, Execute |
| Group     | Read, Execute        |
| Others    | Read, Execute        |

Commonly used for:

* Scripts
* Executable files
* Directories

---

### Permission 644

```text
rw-r--r--
```

| User Type | Permissions |
| --------- | ----------- |
| Owner     | Read, Write |
| Group     | Read        |
| Others    | Read        |

Commonly used for:

* Text files
* Configuration files
* Documentation

---

## Git Activities Completed

### Repository Creation

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

---

## Skills Learned

* Linux users and groups
* Linux file permissions
* Permission management using chmod
* Git repository initialization
* Staging files with git add
* Creating commits
* Viewing commit history
* Basic version control concepts

---

## Lab Outcome

Successfully learned Linux permission management and created a Git repository with multiple commits from Ubuntu Linux.

---

**Author:** uzers090
**Track:** Cybersecurity Learning Journey
