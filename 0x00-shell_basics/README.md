# 0x00 - Shell Basics

The shell scripts in the current directory do the following tasks:

## Basic Tasks
0. Prints the absolute path name of the current working dir
1. Dsiplays the contents list of your current directory
2. Changes the working directory to the user's home directory
3. Displays the current directory contents in a long format
4. Displays current directory contents including hidden files
5. Displays current directory contents:
    - long format
    - with user and group IDs displayed numerically
    - with hidden files (those that start with .)
6. Creates a directory named `my_first_directory` in the  `/tmp/` directory
7. Moves the file `betty` from `/tmp/` to `/tmp/my_first_directory`
8. Deletes the file `betty`
9. Deletes the directory `my_first_directory` in `/tmp/`
10. Changes the working directory to the previous one
11. Lists all files (inclusive of the hidden ones) in the current directory and the
    parent directory of the working directory and the `/boot` directory in long format
12. Prints the type of the file named `iamafile`. The file `iamafile` will be in the
    `/tmp` directory when we will run your script.
13. Symbolic link to `/bin/ls`, named `__ls__`. The symbolic link is created in the current working directory.
14. Copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

## Advanced Tasks
100. Script that moves all files beginning with an uppercase letter to the directory `/tmp/u`.
101. Deletes all files in the current working directory that end with the character `~`.
102. Creates the directories `welcome/`, `welcome/to/` and `welcome/to/school` in the current directory.
103. Lists all the files and directories of the current directory, separated by commas (`,`).
    - Directory names should end with a slash (`/`)
    - Files and directories starting with a dot (`.`) should be listed
    - The listing should be alpha ordered, except for the directories `.` and `..` which should be listed at the very beginning
    - Only digits and letters are used to sort; Digits should come first
    - You can assume that all the files we will test with will have at least one letter or one digit
    - The listing should end with a new line