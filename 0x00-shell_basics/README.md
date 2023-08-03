# Here is Where the Fun Begins
With the thousands of commands available to the command line user, how can we remember them all? The answer is, we don't. The real power of the computer is its ability to do the work for us. To get it to do that, we use the power of the shell to automate things. We write shell scripts.
## What are Shell Scripts?
In the simplest terms, a shell script is a file containing a series of commands. The shell reads this file and carries out the commands as though they have been entered directly on the command line. The shell is somewhat unique, in that it is both a powerful command line interface to the system and a scripting language interpreter. As we will see, most of the things that can be done on the command line can be done in scripts, and most of the things that can be done in scripts can be done on the command line. We have already covered many shell features, but we have focused on those featuresmost often used directly on the command line. The shell also provides a set of features usually (but not always) used when writing programs.
Scripts unlock the power of our Linux machine. So let's have some fun! (http://linuxcommand.org/lc3_writing_shell_scripts.php)
### Writing a Script
A shell script is a file that contains ASCII text. To create a shell script, we use a text editor. A text editor is a program, like a word processor,that reads and writes ASCII text files. There are many, many text editors available for Linux systems, both for the command line and GUI environments. (NOTE: ASCII, in full American Standard Code for Information Interchange, a standard data-encoding format for electronic communication between computers. ASCII assigns standard numeric values to letters, numerals, punctuation marks, and other characters used in computers.)
#### Using shell commands and a text editor (vim) write the following executable scripts:
1 Display the contents list of your current directory.
2 Write a script that changes the working directory to the users home directory.
3 Display current directory contents in a long format
4 Display current directory contents, including hidden files (starting with .). Use the long format
5 Display current directory contents.
*   Long format
*   with user and group IDs displayed numerically
*   And hidden files (starting with .)
6 Create a script that creates a directory named my_first_directory in the /tmp/ directory.
7 Move the file betty from /tmp/ to /tmp/my_first_directory.
8 Delete the file betty.
9 Delete the directory my_first_directory that is in the /tmp directory.
10 Write a script that changes the working directory to the previous one.
11 Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden)
   in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
12 Write a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.
13 Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory. 
14 Create a script that copies all the HTML files from the current working directory to the parent of the working directory, 
   but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent
   of the working directory. You can consider that all HTML files have the extension .html
15 Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u.
16 Create a script that deletes all files in the current working directory that end with the character ~.
17 Create a script that creates the directories welcome/, welcome/to/ and welcome/to/holberton in the current directory.
18 Write a command that lists all the files and directories of the current directory, separated by commas (,).
*    Directory names should end with a slash (/).
*    Files and directories starting with a dot (.) should be listed
*    The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
*    Only digits and letters are used to sort; Digits should come first
*    You can assume that all the files we will test with will have at least one letter or one digit
*    The listing should end with a new line# Write a script that prints the absolute path name of the current working directory.
19 Create a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCH   OOL at offset 0.
