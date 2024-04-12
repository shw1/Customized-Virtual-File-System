# Customized Virtual File System

## Project Overview

- **Name of the Project:** Customized Virtual File System
- **Technology Used:** System Programming using C++
- **User Interface:** Command Line Interface
- **Platform Required:** Windows NT Platform OR Linux Distributions
- **Architectural requirement:** Intel 32 bit processor
- **SDK used:** None

## Description

The Customized Virtual File System project emulates all data structures used by the operating system to manage file system-oriented tasks. It's termed "virtual" because it maintains all records in primary storage. The project creates all necessary data structures for file subsystems and implements essential system calls and commands of the file subsystem such as Open, Close, Read, Write, Lseek, Create, RM, LS, Stat, Fstat, etc. The implementations utilize custom data structures inspired by the algorithms of UNIX operating systems. This project provides an overview of the UNIX File System (UFS) on any platform.

## Data Structures Used

1. Inode Table
2. File Table
3. UAREA
4. User File Descriptor Table
5. Super Block
6. Disk Inode List Block
7. Data Block
8. Boot Block, etc.

## Usage

### How to Start the Project

1. Navigate to the project directory:                                                                                                      cd Customized-Virtual-File-System-project
2. Compile the project:
g++ File-system.cpp -o file-exe
3. Run the executable:
./file-exe
4. You are now in the Customized VFS prompt:
Customized VFS : >

### Commands
For Detail usage of this command check (https://github.com/shw1/Customized-Virtual-File-System/blob/main/Customized%20virtual%20file%20system%20documentation.pdf) file in this project.

- **help**: Display a list of available commands.
- **man**: Get a description of how to use different commands (e.g., read, write, create).
- **clear**: Clear the console.
- **create**: Create a new file with permissions (read only, write only, read and write).
- **write**: Write to a file.
- **read**: Read from a file.
- **open**: Open a file in read mode, write mode, or read and write mode.
- **close**: Close a file.
- **ls**: List all available commands.
- **closeall**: Close all open files.
- **stat**: Get statistical information about a file.
- **truncate**: Delete data from a file.
- **rm**: Remove a file.
- **exit**: Terminate the file system.

## Screenshots

![Terminal Snippet 1](https://github.com/shw1/Customized-Virtual-File-System/assets/108781084/0c1c3646-a1c8-4eb7-b791-b4f5dd63be67)

![Terminal Snippet 2](https://github.com/shw1/Customized-Virtual-File-System/assets/108781084/6058a9ed-c932-437f-a9e0-01793ff93e0d)

![Terminal Snippet 3](https://github.com/shw1/Customized-Virtual-File-System/assets/108781084/a51a6b0f-4993-44e2-9eaa-ccf5f57b32bb)

Thank you for using this documentation.
