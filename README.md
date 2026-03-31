# OSS Audit Lab – Git on Ubuntu 24.04 (WSL2)

This repository documents my work for the Open Source Software Lab, where I conducted a structured audit of Git and the system environment using shell scripting on Ubuntu 24.04 running under WSL2.

**Name:** Aryan Jain  
**Registration Number:** 24BCE11080  

---

## Objective

The primary objective of this lab was to develop practical proficiency in:

- Linux shell scripting (Bash)
- System inspection and monitoring
- Package management using APT
- File system and permission auditing
- Log analysis and keyword-based filtering

This project emphasizes automation, modular scripting, and reproducibility using open-source tools.

---

## Repository Overview

This repository contains a collection of modular shell scripts. Each script performs a specific auditing or information-gathering task and can be executed independently.

---

## File Descriptions

### `script1.sh` — System Identity Report
Generates a detailed system profile including:
- Kernel version (`uname`)
- OS release information (`/etc/os-release`)
- System uptime
- Hostname and architecture details

---

### `script2.sh` — Git Package Inspector
Performs package-level inspection of Git:
- Verifies whether Git is installed
- Displays installed version
- Retrieves package metadata using `dpkg` and `apt`

---

### `script3.sh` — Disk Usage and Permission Audit
Analyzes file system usage and permissions:
- Reports disk usage statistics (`df`, `du`)
- Examines directory permissions
- Helps identify storage bottlenecks and access control issues

---

### `script4.sh` — Log File Analyzer
Processes system or application logs:
- Accepts a log file as input
- Searches for a specified keyword
- Counts occurrences and highlights patterns (e.g., errors, warnings)

---

### `script5.sh` — Open Source Manifesto Generator
An interactive script that:
- Prompts the user with questions
- Generates a customized manifesto text file
- Demonstrates user input handling and file output in Bash

---

### `manifesto_Aryan.txt`
A sample output file generated using `script5.sh`, showcasing the structure and content of the generated manifesto.

---

## Environment Details

| Component          | Specification              |
|-------------------|----------------------------|
| Operating System  | Ubuntu 24.04               |
| Platform          | WSL2 (Windows Subsystem for Linux) |
| Shell             | Bash                       |
| Package Manager   | APT (Debian-based)         |

---

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/aryan2666/oss-audit-24BCE11080
cd oss-audit-24BCE11080
