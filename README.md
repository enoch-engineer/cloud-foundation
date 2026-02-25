# cloud-foundation

# Cloud Engineering Journey – Day 1

## What I Did Today
- Installed WSL2 on Windows 11
- Installed Ubuntu 22.04 LTS
- Restarted the computer to complete installation
- Launched Ubuntu for the first time
- Created my Linux username and password
- Used linux commands
- created a directioy
- changed into a directory
- created a file
- viewed a file 

## Why This Matters
This is the foundation of my cloud engineering environment.  
All future Linux, Docker, Terraform, and AWS work will be done here.
Linux is for infrastructure 


## Commands I Used
- `wsl --install -d Ubuntu`
- `ls`, `pwd`, `cd`
- `sudo apt update && sudo apt upgrade`
- tocuch, nano, cat


## Lessons Learned
- WSL2 gives me a real Linux environment inside Windows.
- Ubuntu is a great tool for practice 
- Cloud engineers rely heavily on Linux, so this is step one.
- Nano is a text editor inside the terminal
- cat is to view text files

## Next Steps
- Learn basic Linux commands
- Set up my development environment
- Start my first Bash script




# Cloud Engineering Journey – Day 2

## What I Did Today

-practiced commands to organize directory and files
-encountered and learned -rw-r--r-- and -rwxr-xr-x
-Wrote and executed two bash scripts
-learn different bash syntax and 


## Why This Matters
-It's an important skill to be able to manage files and directories fast and efficiently through a command sysytem
-Understanding the permissions of users and groups of through the terminal allows for efficency
- Bash scripting is very important for automation 




## Commands I Used
- cd / , cd .. , cd ~
- rm, rm -r ,
- ls -l
- chmod +x script.sh
- ./script.sh
- echo
- df
- -h  

## Lessons Learned
-rwxr-xr-x 
 - - is the  file type
 - rw- what the owner can do
 - r-- what your group can do
 - r-- what everyone else can do
 - r means read
 - w means write
 - x means execute(run)
-chmod +x turns text files into a runnable program that can be excuted by linux
-.sh tells humans it is a shell script
-./ is used to execute the program
- #! this is a shebang
-  /bin/bash this is the path to the bash interpreter
-  $ is a variable 
-  $() prints the input as an output $(pwd) will print the current directory
-  df means disk free shows how much disk space is available
-  -h means human readble 
## Next Steps
- Processes
- Services
- Logs
- System monitoring
- Killing processes
- Troubleshooting


  
