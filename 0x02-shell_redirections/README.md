# 0x02. Shell, I/O Redirections and filters

## About Directory

This directory contains my solutions to the following problem statements:

1. Write a script that prints “Hello, World”, followed by a new line to the standard output..

    [My Solution](./0-hello_world)

2. Write a script that displays a confused smiley "(Ôo)'.

    [My Solution](./1-confused_smiley)

3. Display the content of the /etc/passwd file.

    [My Solution](./2-hellofile)

4. Display the content of /etc/passwd and /etc/hosts

    [My Solution](./3-twofiles)

5. Display the last 10 lines of /etc/passwd

    [My Solution](./4-lastlines)

6. Display the first 10 lines of /etc/passwd

    [My Solution](./5-firstlines)

7. Write a script that displays the third line of the file iacta.

    ```bash
    # iacta file contains
    Alea iacta est

    Alea iacta est ("The die is cast") is a Latin phrase attributed by Suetonius
    (as iacta alea est) to Julius Caesar on January 10, 49 BC
    as he led his army across the Rubicon river in Northern Italy. With this step,
    he entered Italy at the head of his army in defiance of the Senate and began
    his long civil war against Pompey and the Optimates. The phrase has been
    adopted in Italian (Il dado è tratto), Romanian (Zarurile au fost aruncate),
    Spanish (La suerte está echada), French (Les dés sont jetés), Portuguese (A
    sorte está lançada), Dutch (De teerling is geworpen),
    German (Der Würfel ist gefallen), Hungarian (A kocka el van vetve) and many other languages to
    indicate that events have passed a point of no return.

    Read more: https://en.wikipedia.org/wiki/Alea_iacta_est
    ```

8. Write a shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.

    [My Solution](./7-file)

9. Write a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.

    [My Solution](./8-cwd_state)

10. Write a script that duplicates the last line of the file iacta

    [My Solution](./9-duplicate_last_line)

11. Write a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.

    [My Solution](./10-no_more_js)

12. Write a script that counts the number of directories and sub-directories in the current directory.

    ***1. The current and parent directories should not be taken into account***
    ***2. Hidden directories should be counted***

    [My Solution](./11-directories)

13. Create a script that displays the 10 newest files in the current directory.

    *Requirements*
    
    ***1. One file per line***
    ***2. Sorted from the newest to the oldest***

    [My Solution](./12-newest_files)

14. Create a script that takes a list of words as input and prints only words that appear exactly once.

    ***1. Input format: One line, one word***
    ***2. Output format: One line, one word***
    ***3. Words should be sorted***

    [My Solution](./13-unique)

15. Display lines containing the pattern “root” from the file /etc/passwd

    [My Solution](./14-findthatword)

16. Display the number of lines that contain the pattern “bin” in the file /etc/passwd

    [My Solution](./15-countthatword)

17. Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.

    [My Solution](./16-whatsnext)

18. Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.

    [My Solution](./17-hidethisword)

19. Display all lines of the file /etc/ssh/sshd_config starting with a letter.

    ***1. include capital letters as well***

    [My Solution](./18-letteronly)

20. Replace all characters A and c from input to Z and e respectively.

    [My Solution](./19-AZ)

21. Create a script that removes all letters c and C from input.

    [My Solution](./20-hiago)

22. Write a script that reverse its input.

    [My Solution](./21-reverse)

23. Write a script that displays all users and their home directories, sorted by users.

    ***1. Based on the the /etc/passwd file***

24. Write a command that finds all empty files and directories in the current directory and all sub-directories.

    ***1. Only the names of the files and directories should be displayed (not the entire path)***
    ***2. Hidden files should be listed***
    ***3. One file name per line***
    ***4. The listing should end with a new line***
    ***5. You are not allowed to use basename, grep, egrep, fgrep or rgrep***

    [My Solution](./100-empty_casks)

25. Write a script that lists all the files with a .gif extension in the current directory and all its sub-directories.

    ***1. Hidden files should be listed***
    ***2. Only regular files (not directories) should be listed***
    ***3. The names of the files should be displayed without their extensions***
    ***4. The files should be sorted by byte values, but case-insensitive (file aaa should be listed before file bbb, file .b should be listed before file a, and file Rona should be listed after file jay)***
    ***5. One file name per line***
    ***6. The listing should end with a new line***
    ***7. You are not allowed to use basename, grep, egrep, fgrep or rgrep***

    [My Solution](./101-gifs)

26. An acrostic is a poem (or other form of writing) in which the first letter (or syllable, or word) of each line (or paragraph, or other recurring feature in the text) spells out a word, message or the alphabet. The word comes from the French acrostiche from post-classical Latin acrostichis). As a form of constrained writing, an acrostic can be used as a mnemonic device to aid memory retrieval. Read more.

    *Create a script that decodes acrostics that use the first letter of each line.*

    ***1. The decoded message has to end with a new line***
    ***2. You are not allowed to use grep, egrep, fgrep or rgrep***

    [My Solution](./102-acrostic)

27. Write a script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.

    ***1. Order by number of requests, most active host or IP at the top***
    ***2. You are not allowed to use grep, egrep, fgrep or rgrep***

    [My Solution](./103-the_biggest_fan)