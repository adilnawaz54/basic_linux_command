# basic_linux_command

linux start from / directory = cd /
for update = sudo apt update
for upgrade = sudo apt upgrade
how to install = sudo apt install docker.io
how to uninstall = sudo apt purge docker.io

bin = bin is a directory where all the linux commands are written
cat = to view inside a folder
for hidden folders = ls -a
for hidden folders n file with detail = ls -la
descend into write-protected directory = sudo rm -r directory_name
for creating nested or parent directory = mkdir -p A/B/C/D/E
for creating multiple directory = touch test-{1..10}
to print on screen = echo Hello Dosto
To send the output to any folder = echo Hello Dosto > Folder_name
To select top-3 = head -3 directory_name
To select bottom-3 = tail -3 directory_name
To add new user = 1st go to root user and write sudo useradd -m user_name { -m will create a user visible}
TO copy a file = cp d1/A d2/
To view content inside directory = cat /etc/passwd
To enter inside created user = su user_name
If u want to be root acess type = sudo su
To come out of the root we type = exit

----------- How to create Groups and add users-----------

group create = sudo groupadd devops
group check = cat /etc/group
add user to group = sudo usermod -aG devops adil
multiple user add in a group = sudo gpasswd -M adil,adeen,nawaz { -M overrides the group so add everyone in the group}
how to delete group= sudo groupdel tester 

----------- How to give file permission to Groups & users-----------

file permission = chmod 700  { -rwx --- ---}
file permission = chmod 707  { -rwx --- rwx}

----------- How to search in Linux--------------------------

GREP (global regular expression print) = grep -r search_name location          { grep is case sensitve}
                                       = grep -i -r search_name /home/ubuntu/  { i means insensitivity}
if u want to find in some file = grep -i learning folder_name
