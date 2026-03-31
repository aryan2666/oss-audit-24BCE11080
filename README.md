```sh
# OSS Audit Lab – Git on Ubuntu 24.04 (WSL2)

This repository contains my work for the Open Source Software Lab, where I performed a basic audit of Git and the system environment using shell scripting on Ubuntu 24.04 running under WSL2.

**Name:** Aryan Jain  
**Registration Number:** 24BCE11080  

The objective of this lab was to gain practical experience with Linux shell scripting, system inspection, package management, and log analysis using open-source tools.

---

## Repository Overview

This repository consists of multiple shell scripts, each designed to perform a specific auditing or information-gathering task. The scripts are modular and can be executed independently.

### Files Included

- `script1.sh`  
  Generates a system identity report. It collects and displays details such as kernel version, operating system information, system uptime, and other basic system-level data.

- `script2.sh`  
  Acts as a package inspector for Git. It checks whether Git is installed on the system and displays relevant package details using Debian-based package management tools.

- `script3.sh`  
  Performs disk usage and permission auditing on commonly used directories. It helps in understanding storage utilization and access control settings.

- `script4.sh`  
  A log file analyzer that scans a specified log file and counts occurrences of a given keyword. This is useful for identifying patterns such as error frequency in system logs.

- `script5.sh`  
  An interactive script that generates a simple open-source manifesto. It prompts the user with a few questions and creates a text file based on the responses.

- `manifesto_Aryan.txt`  
  A sample output file generated using `script5.sh`.

---

## Environment Details

- Operating System: Ubuntu 24.04  
- Platform: Windows Subsystem for Linux (WSL2)  
- Shell: Bash  
- Package Manager: APT (Debian-based)

---

## Instructions to Run the Scripts

clone from `https://github.com/aryan2666/oss-audit-24BCE11080`

Ensure that you are inside the repository directory before executing the scripts.

### Step 1: Provide Execute Permissions

Run the following command once to make all scripts executable:

```bash
chmod +x script1.sh script2.sh script3.sh script4.sh script5.sh
```

