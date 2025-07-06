# FILE-HANDLING-PROGRAM 

COMPANY : CODTECH IT SOLUTIONS

NAME : VYSHNAVI E R

INTERN ID : CITS0D93

DOMAIN :  C PROGRAMMING

DURATION : 4 WEEKS

MENTOR : NEELA SANTHOSH

# PROGRAM DESCRIPTION – FILE HANDLING IN C

This project demonstrates a basic yet significant concept in C programming: File Handling. The primary objective of this program is to illustrate how to create a text file, write content to that file, append additional information, and finally read and display the file's contents. These operations form the backbone of many real-world applications and are considered essential for every C programmer, especially those working in system-level programming, data logging, or embedded development environments.

# Tools and Technologies Used

# Programming Language: C

C is a powerful and highly efficient programming language, widely used for developing operating systems, embedded systems, and low-level hardware applications. This project makes use of C because of its simplicity, portability, and direct access to file-level operations provided by its standard input/output library.

# Libraries Used:

stdio.h: Provides core functions like fopen(), fprintf(), fgets(), and fclose() for file operations, and printf() for displaying output.

stdlib.h: Included as a best practice. While not strictly necessary in this case, it provides general-purpose utility functions such as memory allocation, process control, and data conversions.

# Code Editor / IDE: Visual Studio Code (VS Code)

VS Code is a lightweight yet highly capable source code editor. It offers features like syntax highlighting, code navigation, error detection, and terminal integration. These make it ideal for writing, compiling, and testing C programs with ease.

# Compiler Used: GCC (GNU Compiler Collection)

The program is compiled using GCC, one of the most widely adopted C compilers in the world. It ensures high performance, cross-platform compatibility, and is commonly used in academic, industrial, and open-source projects.

# Operating System: Windows

Development and execution of this program were done on a Windows platform. The compiled .exe file and the generated .txt file can be found in the local directory and accessed using Windows File Explorer.

# Program Overview

The code is divided into four main functions, each designed to handle a specific file operation:

createFile()
Opens a file in "w" mode. If it exists, it will be overwritten. This ensures a fresh file is created for writing.

writeToFile()
Writes initial content into the file using fprintf(). It includes basic sample text and a signature line to identify the file creator.

appendToFile()
Reopens the file in "a" mode to add additional data at the end without modifying or erasing previous content.

readFromFile()
Uses fgets() in a loop to read and print the contents of the file line by line until the end of the file is reached.

Each function implements basic error handling to manage scenarios where file access fails, helping maintain robustness and stability.

# Applicability of the Task

This task is useful for:

Students and Interns learning file handling in academic or project-based settings.

Junior Developers building command-line utilities or desktop tools.

Embedded Developers storing logs, configuration settings, or sensor outputs.

Any application that requires reading or writing persistent data to files for long-term storage or retrieval.

# Conclusion

In summary, this project effectively demonstrates how basic file operations in C can be applied in  the real-world contexts. The skills learned through this task not only help in academic development but also prepare programmers to handle file-related operations in larger software systems.File handling remains a vital concept in programming, and mastering it ensures better control over data and improved program functionality.

