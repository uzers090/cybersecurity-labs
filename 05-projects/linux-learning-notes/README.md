# Linux Learning Notes

## Overview

This repository contains my Linux learning journey as part of my Cybersecurity roadmap. It includes Linux commands, Bash scripting, networking basics, and security-related tools used during hands-on lab practice.

---

## Day 1 - Ubuntu Linux Basics

### Commands Learned

#### User & System Information

```bash
whoami
pwd
uname -a
id
groups
```

#### File & Directory Management

```bash
ls
ls -la
mkdir
cd
touch
cat
cp
mv
rm
```

#### Permissions

```bash
chmod +x
```

#### Package Management

```bash
sudo apt update
sudo apt upgrade -y
sudo apt install nmap -y
```

#### Networking

```bash
ip a
ping
curl
ss -tuln
nmap
```

---

## Bash Scripts Created

### hello.sh

A simple Bash script that prints:

```text
Hello Cybersecurity World!
```

### sysinfo.sh

Displays:

* Current user
* Current directory
* IP address

---

## Networking Exercises

### Check IP Address

```bash
ip a
```

### Display Listening Ports

```bash
ss -tuln
```

### Test Internet Connectivity

```bash
ping -c 4 google.com
```

### Fetch Web Content

```bash
curl https://example.com
```

### Nmap Scan

```bash
nmap 127.0.0.1
```

Result:

```text
Host is up
All 1000 scanned ports are closed
```

---

## Skills Gained

* Linux terminal navigation
* File and directory management
* User and permission management
* Bash scripting
* Network enumeration
* Port scanning with Nmap
* Documentation and note-taking

---

## Screenshots

The screenshots folder contains:

* Ubuntu terminal setup
* hello.sh output
* sysinfo.sh output
* Nmap scan results
* ss -tuln output

---

## Tools Used

* Ubuntu Server
* Bash
* Nano
* Nmap

---

## Learning Goal

To build a strong foundation in Linux and Cybersecurity through daily hands-on practice, scripting, networking, and security tool usage.

---

**Author:** uzers090
**Track:** Cybersecurity Learning Journey
