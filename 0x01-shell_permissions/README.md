# Permissions
* What do the commands chmod, sudo, su, chown, chgrp do
* Linux file permissions
* How to represent each of the three sets of permissions (owner, group, and other) as a single digit
* How to change permissions, owner and group of a file
* Why can’t a normal user chown a file
* How to run a command with root privileges
* How to change user ID or become superuser
## Other Man Pages
* How to create a user
* How to create a group
* How to print real and effective user and group IDs
* How to print the groups a user is in
* How to print the effective userid
  REMEMBER:
  Each permission is represented by a digit in the octal notation:
- 0: No permission (---)
- 1: Execute permission (--x)
- 2: Write permission (-w-)
- 3: Write and execute permissions (-wx)
- 4: Read permission (r--)
- 5: Read and execute permissions (r-x)
- 6: Read and write permissions (rw-)
- 7: Read, write, and execute permissions (rwx)
### Scripts to write
0 Create a script that switches the current user to the user betty.
* You should use exactly 8 characters for your command (+1 character for the new line)
* You can assume that the user betty will exist when we will run your script
1 Write a script that prints the effective username of the current user.
2 Write a script that prints all the groups the current user is part of.
3 Write a script that changes the owner of the file hello to the user betty.
4 Write a script that creates an empty file called hello.
5 Write a script that adds execute permission to the owner of the file hello.
6 Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
7 Write a script that adds execution permission to the owner, the group owner and the other users, to the file hello
* The file hello will be in the working directory
* You are not allowed to use commas for this script
8 Write a script that sets the permission to the file hello as follows:
* Owner: no permission at all
* Group: no permission at all
* Other users: all the permissions
  The file hello will be in the working directory You are not allowed to use commas for this script
9 Write a script that sets the mode of the file hello to this:
  -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
* The file hello will be in the working directory
* You are not allowed to use commas for this script
10 
