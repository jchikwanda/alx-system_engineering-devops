# 0x01. Shell, permissions

## About Directory

This directory contains my solutions to the following problem statements:

1. Create a script that switches the current user to the user **betty**.

    ***1. You should use exactly 8 characters for your command (+1 character for the new line)***

    ***2. You can assume that the user 'betty' will exist when we will run your script***

    [My Solution](./0-iam_betty)

2. Write a script that prints the effective username of the current user.

    [My Solution](./1-who_am_i)

3. Write a script that prints all the groups the current user is part of.
    
    [My Solution](./2-groups)

4. Write a script that changes the owner of the file hello to the user betty.

    [My Solution](./3-new_owner)

5. Write a script that creates an empty file called hello.

    [My Solution](./4-empty)

6. Write a script that adds execute permission to the owner of the file hello.

    ***The file hello will be in the working directory.***

    [My Solution](./5-execute)

7. Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.

    ***The file hello will be in the working directory***

    [My Solution](./6-multiple_permissions)

8. Write a script that adds execution permission to the owner, the group owner and the other users, to the file hello

    ***1. The file hello will be in the working directory***

    ***2. You are not allowed to use commas for this script***

    [My Solution](./7-everybody)

9. Write a script that sets the permission to the file hello as follows:

    ***1. Owner: no permission at all***
    
    ***2. Group: no permission at all***

    ***3. Other users: all the permissions***

    *The file hello will be in the working directory You are not allowed to use commas for this script*

    [My Solution](./8-James_Bond)

10. Write a script that sets the mode of the file hello to this:

    ```
    -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
    ```

    ***1. The file hello will be in the working directory***
    
    ***2. You are not allowed to use commas for this script***

    [My Solution](./9-John_Doe)

11. Write a script that sets the mode of the file hello the same as olleh’s mode.

    ***1. The file hello will be in the working directory***
    
    ***2. The file olleh will be in the working directory***

    *Note: the mode of olleh will not always be 664. Make sure your script works for any mode.*

    [My Solution](./10-mirror_permissions)

12. Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.

    [My Solution](./11-directories_permissions)

13. Create a script that creates a directory called my_dir with permissions 751 in the working directory.

    [My Solution](./12-directory_permissions)

14. Write a script that changes the group owner to school for the file hello

    ***The file hello will be in the working directory***

    [My Solution](./13-change_group)

15. Write a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.

    [My Solution](./100-change_owner_and_group)

16. Write a script that changes the owner and the group owner of _hello to vincent and staff respectively.

    ***1. The file _hello is in the working directory***

    ***2. The file _hello is a symbolic link***

    [My Solution](./101-symbolic_link_permissions)

17. Write a script that changes the owner of the file hello to betty only if it is owned by the user guillaume.

    ***The file hello will be in the working directory***

    [My Solution](./102-if_only)

18. Write a script that will play the StarWars IV episode in the terminal.

    [My Solution](./103-Star_Wars)