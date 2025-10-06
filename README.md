### Ex.3 Virtualization: Installation and Configuration of Oracle VirtualBox & Kali Linux, and Execution of Linux Commands

## NAME:LOKESH N
## REG NUMBER: 212222100023

## Aim:
To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.

## 3.a) Installation and Configuration of Oracle VirtualBox
## Aim:
To install and configure Oracle VM VirtualBox.

## Pre-requisites:
Machine with Internet access

Minimum 4 GB RAM

Sufficient storage space

## Steps:
# 1.Download Oracle VM VirtualBox:
  Visit Oracle VirtualBox Official Site
  
  Download installer for your OS (Windows/macOS/Linux).
# 2.Install Oracle VM VirtualBox (Example: Windows):
  Launch Installer → Allow Changes → Click Next.
  
  Choose Installation Options → Click Next.
  
  Accept Network Interface Warning → Click Yes.
  
  Click Install.    
  
  Finish Installation and Launch VirtualBox.
# 3.Configure VirtualBox:
  Open VirtualBox.
  
  Click New → Name VM → Select Type (Linux/Windows) and Version.
  
  Allocate:
  
Minimum 2 GB RAM

# Create Virtual Hard Disk (20 GB recommended).

    Start Virtual Machine and provide ISO to install OS.
    
## Result:

Thus, Oracle VM VirtualBox was installed successfully.

3.b) Installation and Configuration of Kali Linux
## Aim:
To install and configure Kali Linux in Oracle VirtualBox.

## Pre-requisites:
Oracle VM VirtualBox Installed

4 GB RAM and 20 GB Storage Minimum

Kali Linux ISO image

## Steps:
1.Download Kali Linux ISO:

    Visit Kali Linux Official Site

    Download 64-bit ISO (Installer version).

2.Create a New Virtual Machine:

    Open VirtualBox → Click New.

    Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit).

Allocate Memory:
    Minimum 2 GB RAM (recommended 4 GB).
4.Create Virtual Hard Disk:

    Select VDI (VirtualBox Disk Image).

    Choose Dynamically allocated.

    Set Disk size to 20 GB or more.

5.Configure ISO Image:

    Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali       Linux ISO.
6.Start Installation:

    Boot Virtual Machine → Choose Graphical Install.

    Set Language, Region, Keyboard.

    Configure Network → Set Hostname (e.g., kali).

    Set root password.

    Disk Partitioning: Use entire disk → All files in one partition.

    Install System → Install GRUB Bootloader → Finish Installation.

7.Login to Kali Linux:

    Use root credentials.
8.(Optional) Install Guest Additions:

    Devices → Insert Guest Additions CD Image → Follow steps inside Kali.
    
## Snapshots:
AWS Account Creation Snapshot

## Snapshot 1: Installing Oracle VirtualBox image
<img width="783" height="57" alt="image" src="https://github.com/user-attachments/assets/cbf4494e-d5cd-4f8c-bd7d-ee7403140124" />

Snapshot 2: Kali Running in Virtual image
<img width="787" height="483" alt="image" src="https://github.com/user-attachments/assets/718f5c4a-951b-45c2-87b7-15885b49766f" />

## Result:
Thus, Kali Linux guest OS was installed and configured successfully.

## 3.c) Execution of Linux Commands in Kali
## About Linux:
Open-source operating system.

Kernel manages communication between hardware and software.

Commands are case-sensitive.

## Commands:
1) ls Command
The ls command is used to display a list of content of a directory.

##   Syntax: ls
<img width="1161" height="427" alt="image" src="https://github.com/user-attachments/assets/ba5970ab-4760-4f3c-a495-d83845e9d92f" />

## 2) pwd Command
The pwd command is used to display the location of the current working directory.

Syntax: pwd <img width="250" height="67" alt="image" src="https://github.com/user-attachments/assets/13ad1c6f-66f6-418a-9dcd-10ba386d4bd9" />

## 3) mkdir Command
The mkdir command is used to create a new directory under any directory.

Syntax: mkdir

<img width="795" height="92" alt="image" src="https://github.com/user-attachments/assets/0b97e400-d756-4094-8a78-07dc167ec5ae" />

## 4) rmdir Command
The rmdir command is used to delete a directory.

Syntax: rmdir

<img width="766" height="102" alt="image" src="https://github.com/user-attachments/assets/6177ccba-f918-4a31-9faa-31641bbca80d" />

## 5) cd Command
The cd command is used to change the current directory.

Syntax: cd

## 6) cat Command
The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

<img width="362" height="212" alt="image" src="https://github.com/user-attachments/assets/dcd0b310-a65a-4b4a-9cdd-c0214874e5fd" />

## 7) cp Command
The cp command is used to copy a file or directory.

Syntax: cp

<img width="315" height="157" alt="image" src="https://github.com/user-attachments/assets/baf43bfa-b093-4002-94be-132c81419b86" />

## 8) gedit Command
The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

<img width="415" height="37" alt="image" src="https://github.com/user-attachments/assets/af2d8e1e-ef4d-4963-ba2d-a241b19e5404" />

## 9) su Command
The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su

<img width="276" height="105" alt="image" src="https://github.com/user-attachments/assets/3802eb7a-2725-4a66-9278-dbf0eb65714a" />

## 10) mv Command
The mv command is used to move a file or a directory form one location to another location.

Syntax: mv

<img width="391" height="317" alt="image" src="https://github.com/user-attachments/assets/7c158b46-4f3b-4e4f-a58c-6ebd348aae7e" />

## 11) rename Command
The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

<img width="472" height="203" alt="image" src="https://github.com/user-attachments/assets/a98a5d72-5388-4fb3-9386-01663250d335" />

## 12) head Command
The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head
<img width="423" height="647" alt="image" src="https://github.com/user-attachments/assets/3c3b419b-60f3-4708-9c13-ced4fe2bb73e" />

## 13) tail Command
The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail

<img width="305" height="275" alt="image" src="https://github.com/user-attachments/assets/e08f8f54-e903-4b9b-86dc-4585a5acee22" />

## 14) id Command
The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

<img width="807" height="31" alt="image" src="https://github.com/user-attachments/assets/264ccfd1-6e5e-49ea-8d8c-0e51f1f77067" />

## 15) grep Command
The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep

<img width="368" height="77" alt="image" src="https://github.com/user-attachments/assets/952aa9d7-2eb5-4e49-bae2-cc93ea3decee" />

## 16) tr Command
The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

<img width="522" height="138" alt="image" src="https://github.com/user-attachments/assets/b0352890-f870-4e52-9a23-7983b4db3a54" />

## 17) chmod Command
The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<file_name>

image
18) tar Command
The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved] $ tar xvzf file.tar *.c

<img width="405" height="185" alt="image" src="https://github.com/user-attachments/assets/54eedf81-7168-4598-9e14-cc5f0bd0a151" />

## 19) chown Command
The chown command is used to change ownership.

Syntax: chown owner_name file_name

<img width="422" height="363" alt="image" src="https://github.com/user-attachments/assets/ee4649ae-7d3e-495a-a6d6-c3c4eb5651e2" />

## 20) make Command
The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

i<img width="253" height="72" alt="image" src="https://github.com/user-attachments/assets/0cb5da77-df98-45cc-aebc-1d7bf8c7b273" />

## 21) ifconfig Command
The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

<img width="747" height="87" alt="image" src="https://github.com/user-attachments/assets/545c4ca6-a1fb-4c6f-b8ec-1aa0a21ab41a" />

## 22) chmod 777 Command
The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name $chmod -R 777 /path/to/file/or/folder

<img width="542" height="137" alt="image" src="https://github.com/user-attachments/assets/ecb2b572-bc37-4a2f-b29e-48ba00869814" />

## 23) host Command
The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host or

<img width="608" height="120" alt="image" src="https://github.com/user-attachments/assets/52faddcc-b993-4242-8e8d-89b18f907fd3" />

## 24) gzip Command
The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip ..

## 25) sort Command
The sort command is used to sort files in alphabetical order.

Syntax:sort

<img width="265" height="363" alt="image" src="https://github.com/user-attachments/assets/9361f830-62c5-47b7-87b7-ec716799f7f2" />

## 26) cal Command
The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

<img width="318" height="233" alt="image" src="https://github.com/user-attachments/assets/bef434b7-48f2-4606-acf0-140d46d184f2" />

## 27) clear Command
Linux clear command is used to clear the terminal screen.

Syntax: clear

<img width="683" height="772" alt="image" src="https://github.com/user-attachments/assets/ed8dce09-9033-4ae7-9ee4-c39cca0e46d6" />
<img width="547" height="286" alt="image" src="https://github.com/user-attachments/assets/b115746e-3786-45b9-abf7-17b4810b9e0b" />

## 28) mail Command
The mail command is used to send emails from the command line.

Syntax: mail -s "Subject"

<img width="771" height="65" alt="image" src="https://github.com/user-attachments/assets/ac0eefac-81d2-4a7f-ac95-a11e2e0169c8" />

## 29) df Command
The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

<img width="761" height="248" alt="image" src="https://github.com/user-attachments/assets/92752a6c-007a-4a70-a56a-2042cd235ef4" />

## 30) find Command
The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

<img width="342" height="96" alt="image" src="https://github.com/user-attachments/assets/2d14aad1-5c6f-429c-9d85-86a73dc7f3b8" />
<img width="381" height="85" alt="image" src="https://github.com/user-attachments/assets/906c0a5b-a5fa-4454-8172-76eee2406402" />

## Result:
Thus, the execution of various Linux commands is executed successfully using Kali Linux.
