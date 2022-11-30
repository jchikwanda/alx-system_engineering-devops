# 0x00 Shell Basics

## About Directory

This directory contains my solutions to the following problem statements:

1. Write a script that prints the absolute path name of the current working directory. 

    [My Solution](./0-current_working_directory)
2. Display the contents list of your current directory.

    [My Solution](./1-listit)

3. Write a script that changes the working directory to the user’s home directory.
    
    ***You are not allowed to use any shell variables***
    
    [My Solution](./2-bring_me_home)

4. Display current directory contents in a long format

    [My Solution](./3-listfiles)

5. Display current directory contents, including hidden files (starting with .). Use the long format.

    [My Solution](./4-listmorefiles)

6. Display current directory contents.

    a. ***Long format***
    
    b. ***with user and group IDs displayed numerically***

    c. ***And hidden files (starting with .)***

    [My Solution](./5-listfilesdigitonly)

7. Create a script that creates a directory named my_first_directory in the /tmp/ directory.

    [My Solution](./6-firstdirectory)

8. Move the file betty from /tmp/ to /tmp/my_first_directory.

    [My Solution](./7-movethatfile)

9. Delete the file betty.

    ***The file betty is in /tmp/my_first_directory***

    [My Solution](./8-firstdelete)

10. Delete the directory my_first_directory that is in the /tmp directory.

    [My Solution](./9-firstdirdeletion)

11. Write a script that changes the working directory to the previous one.

    [My Solution](./10-back)

12. Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

    [My Solution](./11-lists)

13. Write a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.

    [My Solution](./12-file_type)

14. Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.

    [My Solution](./13-symbolic_link)

15. Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

    ***You can consider that all HTML files have the extension .html***

    [My Solution](./14-copy_html)

16. Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u.

    ***You can assume that the directory /tmp/u will exist when we will run your script***

    [My Solution](./100-lets_move)

17. Create a script that deletes all files in the current working directory that end with the character ~.

    [My Solution](./101-clean_emacs)

18. Create a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.

    ***You are only allowed to use two spaces (and lines) in your script, not more.***

    [My Solution](./102-tree)

19. Write a command that lists all the files and directories of the current directory, separated by commas (,).

    a. ***Directory names should end with a slash (/)***
    
    b. ***Files and directories starting with a dot (.) should be listed***

    c. ***The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning***

    d. ***Only digits and letters are used to sort; Digits should come first***
    
    e. ***You can assume that all the files we will test with will have at least one letter or one digit***

    f. ***The listing should end with a new line***

    [My Solution](./103-commas)

19. Create a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.

    [My Solution](./school.mgc)
