# Linux Essentials


##  Day 6 - Chapter 6:Getting to Know the Command Line

What is the shell?
   > The shell is a layer on the kernel that can receive the user commands and then send them to the kernel.

Linux has several shells:
  - zsh
  - tesh
  - ksh
  - bash
  - dash
    
Everything in Linux is a file.


The important commands for this section are:

user@system$ nano file1.txt
user@system$ touch file1.txt

user@system$ cat file1.txt

user@system$ mkdir dir1

user@system$ cd dir1
user@system$ cd .
user@system$ cd ..
user@system$ cd ~

user@system$ pwk

user@system$ ls
user@system$ ls *.txt
user@system$ ls -a
user@system$ ls -l
user@system$ ls -al

user@system$ rmdir dir1
user@system$ rm file1.txt
user@system$ rm -r dir1

user@system$ locate COMMAND


What is the terminal?

   > Users use a terminal to send commands to the shell.

What is TTY?

   > The TTY is a technology which allows several users to execute their commands.

What is the man page?

   > Every program has a number of manual pages (man pages) for guiding the users.the man pages are saved on your computer.

The important commands for this section are:

user@system$ man COMMAND
user@system$ man -k COMMAND
user@system$ man SECTION_NUMBER COMMAND
user@system$ apropos COMMAND

user@system$ info COMMAND

user@system$ help COMMAND
user@system$ help -d COMMAND

user@system$ help -m COMMAND
user@system$ man -s COMMAND

user@system$ whatis COMMAND
user@system$ mackwhatis
user@system$ whereis COMMAND


What is the environment variable?
   > When an OS is booted,the OS creates some variables called "Environment Variables(EV)".The enviroment variable can help the shell to works.
These variables are used by programmers to program easily.
The important commands for this section are:

user@system$ print env
user@system$ env
user@system$ echo $PATH
user@system$ echo aria
user@system$ echo "aria"
user@system$ j="jack"
user@system$ echo $j
user@system$ echo $j;echo "hello"
user@system$ echo $j$j
user@system$ echo $200
user@system$ echo "$200"
user@system$ echo \$200
user@system$ echo "\$200"
user@system$ echo '\$200'

user@system$ history
user@system$ history 5
user@system$ history c


written on: June 17 2026
