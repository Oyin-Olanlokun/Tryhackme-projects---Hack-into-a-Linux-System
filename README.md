# Tryhackme-projects---Hack-into-a-Linux-System
Room 2: Hacking into a Linux system on TryHackMe
Date: September 2024
Objective: Utilize an AttackBox to access the content of the file in the root directory
  
Tools Used:
- AttackBox Terminal
  
Step-by-Step Process: -

1. Connect to a server over SSH and answered 
2. Used the following the following Linux commands: whoami 
ssh USERNAME@10.10.66.232
ls
cat FILENAME
history
3. Used the command _history_ to check the commands the user has typed
4. 
5. Gained access into the bank account and transferred $2000 from the bank account 

Results:
- Encountered permission issues when trying to access the file; had to run the command with superuser privileges - sudo cat /root/flag.txt
- Displayed the contents of the file flag.txt in the root directory
- Discovered the root password
- 
