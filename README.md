# Shell Basics

Welcome to the Shell Basics project! This repository contains a collection of scripts written in Bash that cover various fundamental concepts of shell scripting. These scripts are designed to help you develop a solid understanding of the Linux shell and its basic functionalities.

## Table of Contents

1. [Introduction](#introduction)
2. [Project Structure](#project-structure)
3. [Learning Objectives](#learning-objectives)
4. [Requirements](#requirements)
5. [Scripts](#scripts)
6. [Quiz](#quiz)
7. [Tasks](#tasks)
    - [Task 0: Where am I?](#task-0-where-am-i)
    - [Task 1: What’s in there?](#task-1-whats-in-there)
    - [Task 2: There is no place like home](#task-2-there-is-no-place-like-home)
    - [Task 3: The long format](#task-3-the-long-format)
    - [Task 4: Hidden files](#task-4-hidden-files)
    - [Task 5: I love numbers](#task-5-i-love-numbers)
    - [Task 6: Welcome](#task-6-welcome)
    - [Task 7: Betty in my first directory](#task-7-betty-in-my-first-directory)
    - [Task 8: Bye bye Betty](#task-8-bye-bye-betty)
    - [Task 9: Bye bye My first directory](#task-9-bye-bye-my-first-directory)
    - [Task 10: Back to the future](#task-10-back-to-the-future)
    - [Task 11: Lists](#task-11-lists)
    - [Task 12: File type](#task-12-file-type)
    - [Task 13: We are symbols, and inhabit symbols](#task-13-we-are-symbols-and-inhabit-symbols)
    - [Task 14: Copy HTML files](#task-14-copy-html-files)

## Introduction

The shell is a command-line interface that allows users to interact with the operating system by executing commands. It provides a powerful set of tools and utilities for managing files, navigating the file system, and automating tasks.

In this project, you will learn the basics of shell scripting using the Bash shell. You will explore essential concepts such as navigation, file manipulation, command execution, and working with commands. By completing the tasks and exercises, you will gain a solid understanding of the shell and its capabilities.

## Project Structure

This project follows a specific structure to ensure consistency and organization. Here's an overview of the project structure:

- **`scripts/`**: This directory contains all the shell scripts for the tasks.
- **`README.md`**: This file provides an overview of the project and its tasks.
- **`quiz.md`**: This file contains quiz questions to test your knowledge.
- **`LICENSE`**: This file includes the license information for the project.

## Learning Objectives

By completing this project, you will achieve the following learning objectives:

- Understand the basics of shell scripting.
- Navigate the file system using commands like `cd`, `pwd`, and `ls`.
- Manipulate files and directories using commands such as `cp`, `mv`, `rm`, and `mkdir`.
- Execute commands and understand their different types.
- Read and understand manual pages for commands.
- Use keyboard shortcuts to improve productivity.
- Create symbolic links and understand their purpose.
- Copy files while considering file existence and modification times.

## Requirements

To work on the scripts in this project, you need the following:

- Editors

: You can use any text editor of your choice (e.g., Vim, Nano, Sublime Text).
- Operating System: This project can be completed on any Linux distribution or Unix-like environment.
- Shell: The scripts are written in Bash (Bourne Again SHell), so you need Bash installed on your system.

## Scripts

The following scripts are included in this project:

1. [0-current_working_directory](scripts/0-current_working_directory): This script prints the absolute path name of the current working directory.
2. [1-listit](scripts/1-listit): This script displays the contents list of the current directory.
3. [2-bring_me_home](scripts/2-bring_me_home): This script changes the working directory to the user's home directory.
4. [3-listfiles](scripts/3-listfiles): This script displays the current directory contents in a long format.
5. [4-listmorefiles](scripts/4-listmorefiles): This script displays the current directory contents, including hidden files, in a long format.
6. [5-listfilesdigitonly](scripts/5-listfilesdigitonly): This script displays the current directory contents in a long format with user and group IDs displayed numerically, including hidden files.
7. [6-firstdirectory](scripts/6-firstdirectory): This script creates a directory named "my_first_directory" in the /tmp/ directory.
8. [7-movethatfile](scripts/7-movethatfile): This script moves the file "betty" from /tmp/ to /tmp/my_first_directory.
9. [8-firstdelete](scripts/8-firstdelete): This script deletes the file "betty" from /tmp/my_first_directory.
10. [9-firstdirdeletion](scripts/9-firstdirdeletion): This script deletes the directory "my_first_directory" from the /tmp directory.
11. [10-back](scripts/10-back): This script changes the working directory to the previous one.
12. [11-lists](scripts/11-lists): This script lists all files in the current directory, parent of the working directory, and /boot directory in a long format.
13. [12-file_type](scripts/12-file_type): This script prints the type of the file named "iamafile" located in the /tmp directory.
14. [13-symbolic_link](scripts/13-symbolic_link): This script creates a symbolic link to /bin/ls named "__ls__" in the current working directory.
15. [14-copy_html_files](scripts/14-copy_html_files): This script copies all HTML files from the current working directory to the parent of the working directory, only if they are newer or do not exist in the parent directory.

## Quiz

To test your knowledge, a quiz is available in the [quiz.md](quiz.md) file. Take the quiz to assess your understanding of shell basics.

## Tasks

The project includes several tasks that you need to complete using the provided scripts. Each task focuses on a specific concept or command related to shell scripting. You will find detailed instructions for each task in the [README.md](README.md) file.

Here's a brief overview of the tasks:

### Task 0: Where am I?

Create a script that prints the absolute path name of the current working directory.

### Task 1: What’s in there?

Write a script that displays the contents list of the current directory.

### Task 2: There is no place like home

Create a script that changes the working directory to the user's home directory.

### Task 3: The long format

Write a script that displays the current directory contents in a long format.

### Task 4: Hidden files



Create a script that displays the current directory contents, including hidden files, in a long format.

### Task 5: I love numbers

Write a script that displays the current directory contents in a long format with user and group IDs displayed numerically, including hidden files.

### Task 6: Welcome

Create a script that creates a directory named "my_first_directory" in the /tmp/ directory.

### Task 7: Betty in my first directory

Write a script that moves the file "betty" from /tmp/ to /tmp/my_first_directory.

### Task 8: Bye bye Betty

Create a script that deletes the file "betty" from /tmp/my_first_directory.

### Task 9: Bye bye My first directory

Write a script that deletes the directory "my_first_directory" from the /tmp directory.

### Task 10: Back to the future

Create a script that changes the working directory to the previous one.

### Task 11: Lists

Write a script that lists all files in the current directory, parent of the working directory, and /boot directory in a long format.

### Task 12: File type

Create a script that prints the type of the file named "iamafile" located in the /tmp directory.

### Task 13: We are symbols, and inhabit symbols

Write a script that creates a symbolic link to /bin/ls named "__ls__" in the current working directory.

### Task 14: Copy HTML files

Create a script that copies all HTML files from the current working directory to the parent of the working directory, only if they are newer or do not exist in the parent directory.

Good luck with the tasks and enjoy learning shell basics!
