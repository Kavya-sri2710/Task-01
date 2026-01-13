# Task-01
Task-01 : Foundation &amp; Environment Setup
1:File & Directory Commands
ls # List files
ls -la # List with details + hidden files
pwd # Present working directory
cd folder_name # Change directory
cd .. # Move back one directory
mkdir dir # Create directory
rmdir dir # Delete empty directory
rm file # Delete file
rm -r dir # Delete directory recursively
cp src dest # Copy files
mv src dest # Move / rename file

2:File Viewing & Editing
cat file # View file content
less file # Scroll view
head file # First 10 lines
tail file # Last 10 lines
tail -f file # Live log view
touch file # Create empty file
nano file # Edit with nano
vim file # Edit with vim

3:ls -l # View permissions
chmod 777 file # Full permission
chmod 755 file # Common permission
chown user file # Change owner

4:Package Management
sudo apt update
sudo apt upgrade
sudo apt install pkg
sudo apt remove pkg
sudo yum install pkg
sudo yum remove pkg

5:Networkinip a # IP addresses
ifconfig # Network info
ping google.com # Test connectivity
netstat -tuln # Open ports
ss -tuln # Modern netstat
curl url # Fetch content
wget url # Download file

6:User Management
whoami
id
adduser user
passwd user
su user
sudo command

7:System Info
uname -a
hostname
uptime
date
who

8:Useful Shortcuts
Ctrl + C # Stop process
Ctrl + Z # Pause process
Ctrl + D # Logout
Ctrl + L # Clear screen
!! # Last command
history # Command history
