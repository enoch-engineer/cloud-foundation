# Cloud Engineering Journey (Linux) – Day 3

## Setup

Opened my Linux environment in Ubuntu using WSL2  
Practiced process monitoring and system diagnostics  
Used Linux commands to analyze running processes and system activity  
Created a background process to safely test process management commands  
Explored Linux system log directories and kernel logs  
Checked CPU core counts to compare against system load averages  

## What I Learned

Linux provides powerful tools for monitoring and managing running processes  
Process IDs (PIDs) uniquely identify each running process in the system  
System performance can be analyzed through CPU usage, memory usage, and load averages  
Load averages must be interpreted relative to the number of CPU cores available  
Linux system logs provide valuable insight when diagnosing system issues  
Kernel logs help identify deeper system events related to hardware, drivers, or virtualization  

## Cloud Relevancy

Monitoring system activity is essential when managing cloud servers.  

Identifying and terminating runaway or stuck processes helps maintain system stability and performance.

Understanding PIDs allows engineers to diagnose service failures and troubleshoot application deployments.

System logs and kernel logs are critical for debugging production infrastructure and identifying root causes of system failures.

## Commands Practiced

top  
Monitored live system processes and system resource usage  

q  
Exited the `top` interface  

ps aux  
Viewed all currently running processes  

ps aux | grep <process>  
Searched for specific running processes  

sleep 1000 &  
Created a safe background process for testing  

kill <PID>  
Terminated a running process using its PID  

ls /var/log  
Listed system log files  

sudo tail -n 20 /var/log/kern.log  
Viewed recent kernel log entries  

nproc  
Checked the number of CPU cores
