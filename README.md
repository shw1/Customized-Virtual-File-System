Customized Virtual File System
Project Overview
Name: Customized Virtual File System
Technology Used: System Programming using C++
User Interface: Command Line Interface
Platform Required: Windows NT Platform OR Linux Distributions
Architectural Requirement: Intel 32-bit processor
SDK Used: None
Description
The Customized Virtual File System project emulates all data structures used by the operating system to manage file system-oriented tasks. It's termed "virtual" because it maintains all records in primary storage. The project creates all necessary data structures for file subsystems and implements essential system calls and commands of the file subsystem such as Open, Close, Read, Write, Lseek, Create, RM, LS, Stat, Fstat, etc. The implementations utilize custom data structures inspired by the algorithms of UNIX operating systems. This project provides an overview of the UNIX File System (UFS) on any platform.

Data Structures Used
Inode Table
File Table
UAREA
User File Descriptor Table
Super Block
Disk Inode List Block
Data Block
Boot Block, etc.
Usage
How to Start the Project
Navigate to the project directory:
arduino
Copy code
cd Customized-Virtual-File-System-project
Compile the project:
arduino
Copy code
g++ File-system.cpp -o file-exe
Run the executable:
bash
Copy code
./file-exe
You are now in the Customized VFS prompt:
yaml
Copy code
Customized VFS : >
Commands
help: Display a list of available commands.

bash
Copy code
Customized VFS : > help
man: Get a description of how to use different commands (e.g., read, write, create).

lua
Copy code
Customized VFS : > man create
clear: Clear the console.

arduino
Copy code
Customized VFS : > clear
create: Create a new file with permissions (read only, write only, read and write).

lua
Copy code
Customized VFS : > create myfile.txt 3
write: Write to a file.

arduino
Copy code
Customized VFS : > write myfile.txt
read: Read from a file.

arduino
Copy code
Customized VFS : > read myfile.txt
open: Open a file in read mode, write mode, or read and write mode.

arduino
Copy code
Customized VFS : > open myfile.txt 3
close: Close a file.

arduino
Copy code
Customized VFS : > close myfile.txt
ls: List all available commands.

bash
Copy code
Customized VFS : > ls
closeall: Close all open files.

yaml
Copy code
Customized VFS : > closeall
stat: Get statistical information about a file.

bash
Copy code
Customized VFS : > stat myfile.txt
truncate: Delete data from a file.

bash
Copy code
Customized VFS : > truncate myfile.txt
rm: Remove a file.

bash
Copy code
Customized VFS : > rm myfile.txt
exit: Terminate the file system.

bash
Copy code
Customized VFS : > exit
Screenshots
Terminal Snippet 1

Terminal Snippet 2

Terminal Snippet 3

Thank you for using this documentation.
