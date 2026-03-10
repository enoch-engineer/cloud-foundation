# Cloud Engineering Journey (Linux) – Day 2

## Setup / Practice
- Read and interpreted Linux file permissions
- Added permissions to a file
- Used a shebang
- Created a Bash script
- Identified why a script wasn’t executable and fixed it by adding the correct permissions
- Executed a script
- Changed a file group
- Used symbolic permissions (`+x`, `g+w`)
- Used numeric permissions (`755`, `644`)
- Practiced converting symbolic permissions to numeric mode and applied them to real files
- Changed file group ownership
- Displayed system information via command

---

## What I Learned
- How to read Linux file permissions using different commands
- The difference and application of symbolic permissions and numeric permissions
- A deeper understanding of ownership and group management
- The purpose of a shebang (`#!/bin/bash`) is to tell Linux which interpreter to use
- How variables and system commands can be used inside a script

Permission meanings:

- `r` = read  
- `w` = write  
- `x` = execute  

---

## Cloud Relevancy
File permissions and ownership are essential for managing Linux servers.

Bash scripting is a foundational skill in cloud engineering.

Numeric permissions are industry standards for scripts.

Understanding permissions helps prevent common issues during deployments, automation, and infrastructure management.

---

## Commands Used

`ls -l`  
Viewed file permissions

`chmod +x`  
Added execute permission

`chmod 755`  
Set standard script permissions

`chmod 664`  
Set shared file permissions

`chmod g+w`  
Added write permission for group

`chown`  
Changed file group ownership

`groups`  
Viewed user group memberships

`nano`  
Edited files in the terminal

`./script.sh`  
Executed a Bash script

`uname -a`  
Displayed system information
