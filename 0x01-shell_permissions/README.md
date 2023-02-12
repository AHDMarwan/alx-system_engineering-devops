# Day 002: Shell Permissions #
Commands: chmod, sudo, su, chown, chgrp, id, groups, whoami, adduser, useradd, addgroup

Important Links:
http://linuxcommand.org/lc3_lts0090.php

Task Descriptions:
0.My Name is Betty: 0-iam_betty
Changes user ID to "betty". Uses only 8 characters

1.Who am I: 1-who_am_i
Prints current user ID.

2.Groups: 2-groups
Prints all the groups the current user is part of.

3.New Owner: 3-new_owner
Changes owner of file "hello" to user "betty"

4.Empty!: 4-empty
Creates an empty file called "hello"

5.Execute: 5-execute
Adds execute permission for the file "hello"

6.Multiple Permissions: 6-multiple_permissions
On the file "hello", adds execute permissions to owner and group owner, and adds read permission to other users.

7.Everybody: 7-everybody
On the file "hello", adds execute permissions to the owner, group owner and the other users.

8.James Bond: 8-james_bond
On the file "hello", adds permissions as follows: no permission at all for owners, and group owners. All permissions for all other users.

9.John Doe: 9-john_doe
On the file "hello", set mode of the file to this: -rwxr-x-wx

10.Look in the Mirror: 10-mirror_permissions
Set the mode of file "hello" the same as file "olleh". (They are both in the same working directory)

11.Directories: 11-directory_permissions
adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed

12.More Directories: 12-directory_permissions
Create a script that creates a directory called my_dir with permissions 751 in the working directory.

13.Change Group: 13-change_group
Write a script that changes the group owner to school for the file "hello" (File "hello" will be in the current working directory)

