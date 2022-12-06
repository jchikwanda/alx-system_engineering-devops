# Alx System Engineering Devops

## About the Repository
This repository contains all the projects that relate to the unix command line interface. These projects are part of the weekly assessments given by ALX.

## Contents of the Repository

### [0x00 Shell Basics](./0x00-shell_basics/README.md) 

#### 30<sup>th</sup> November, 2022

First project. The learning goals are as follows - learn how to:

1. Navigate the filesystem
    
    ```bash
    cd # Changes the directory
    pwd # prints the current working directory
    ls # lists contents of a directory
    ```

2. Look around

    ```bash
    ls
    less # helps view files content
    file # tells us the kond of file we have
    ln # Creates links to files or directories
    ```

3. Manipulate Files

    ```bash
    cp # Copies files and directories
    mv # Moves or renames files and directories
    rm # Removes files and directories
    mkdir # Creates a new directory
    ```

4. Work with commands 

    ```bash
    type # Tells us about a command
    which # Tells about the location of a command
    help # Displays all shell available commands
    man # Tells us how to use a command
    ```

5. Know what the shell is all about.
6. Understand the shebang
    ```bash
    #!/bin/bash
    ```

### [0x01. Shell, permissions](./0x00-shell_basics/README.md) 

#### 1<sup>st</sup> December, 2022

Second project. The learning goals are as follows - learn how to:

1. Use the following commands
    
    ```bash
    chown
    sudo
    su
    chown
    chgrp
    ```

2. Create a user
3. Create a group
4. Print real and effective user and group id's
5. Print groups a user is in

### [0x02. Shell, I/O Redirections and filters](./0x02-shell_redirections/README.md) 

#### 5<sup>th</sup> December, 2022

Third project. The learning goals are as follows - learn how to:

1. Use the following commands
    
    ```bash
    head
    tail
    find
    wc
    sort
    uniq
    grep
    tr
    ```

2. What are special characters
3. Understand what do the white spaces, single quotes, double quotes, backslash, comment, pipe, command separator, tilde and how and when to use them
4. What is the /etc/passwd file and what is its format
5. What is the /etc/shadow file and what is its format
6. How to combine commands and filters with redirections
7. How to send the output from one program to the input of another program
8. How to get standard input from a file instead of the keyboard
9. How to redirect standard output to a file