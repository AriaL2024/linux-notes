# Linux Essentials


##  Day 7 - Chapter 7:Managing files

Linux uses the FHS (Filesystem Hierarchy Standard) to manage its files.
The file system is a low level disk structure to organize OS files.
Linux defined two levels for the user:
  - root
  - normal user
The important commands for this section are:
```
user@system$ sudo su
user@system$ whoami
```


The FHS has several primary nodes:
  - /bin
  - /boot
  - /sbin
  - /lib
  - /usr
  - /home
  - /root
  - /var
  - /tmp
  - /mnt
  - /media
  - /dev
  - /run
  - /proc
  - /opt

    
Types of files in linux:
  - shareable files 
  - unshareable files 
  - static files 
  - variable files


What is a link?
A link is a tool in linux that makes it possible to create several shortcuts to a file.
Types of links:
  - hard link 
  - soft link (symbolic link)

    
The important commands for this section are:
```
user@system$ ln fileA fileB
user@system$ ln -s fileA fileB
```


The important commands for this chapter are:
  - touch: this command can create a file or change timestamps.
```
user@system$ touch fileA
user@system$ touch -c fileA
user@system$ touch -d "oct 16 11:24" fileA 
user@system$ touch fileA fileB fileC

```
  - mkdir: this command can create an empty directory.
```
user@system$ mkdir dirA
user@system$ mkdir -p dirA/dirB
```
  - rmdir: this command can remove a directory.
```
user@system$ rmdir dirA
```
  - rm: this command can remove a files or directories.
```
user@system$ rm fileA 
user@system$ rm -r dirA
user@system$ rm -f dirA
```
  - mv: this command can move a file or directory.
```
user@system$ mv fileA fileB
```
  - cp: this command copies a file.
```
user@system$ cp fileA fileB
user@system$ cp fileA /dirA/
user@system$ cp fileA dirA/fileB
user@system$ cp -R SRC DST
user@system$ cp -f SRC DST
user@system$ cp -i SRC DST
user@system$ cp -u SRC DST
user@system$ cp -p SRC DST
```
  - tree: this command shows files in a tree structure.
```
user@system$ tree
```
  - ls: this command shows a list of files.
```
user@system$ ls -d
user@system$ ls -R
user@system$ ls -p
user@system$ ls net*
user@system$ ls -F
user@system$ ls dirA/
```






written on: June 18 2026
