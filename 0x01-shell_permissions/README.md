0-iam_betty: switch user 

1-who_am_i: print effective username of current user

2-groups: all groups the current user is part of

3-new_owner: changer file owner

4-empty: empty file

5-execute: execute file permission to owner

6-multiple_permissionsWrite a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
    The file hello will be in the working directory: 

7-everybody:  adds execution permission to the owner, the group owner and the other users, to the file hello

8-James_Bond:Write a script that sets the permission to the file hello as follows:
    Owner: no permission at all
    Group: no permission at all
    Other users: all the permissions

9-John_Doe:Write a script that sets the mode of the file hello to this:
    -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello

10-mirror_permissions:sets the mode of the file hello the same as olleh’s mode.
    The file hello will be in the working directory
    The file olleh will be in the working directory

11-directories_permissions: Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.

12-directory_permissions:Create a script that creates a directory called my_dir with permissions 751 in the working directory.
