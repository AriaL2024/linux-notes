# Linux Essentials


##  Day 8 - Chapter 8:Searching, Extracting,and Archiving Data

What are regular expressions?
   > Regular expressions (regex) are tools in linux.these tools can search for patterns in a file
Types of regular expressions:
  - basic
  - Extended
Several regular expression characters (metacharacters) are:
  - *
  - .
  - |
  - []
  - ^
  - $
  - -
  - ?
  - +
The important commands for this section are:
```

user@system$ grep ^[^a] file.A

user@system$ grep a.b file.A

user@system$ grep -E "^[^a]|c..b*|free$" file.A
```
What is an archive?
   > Users can group the files by using archive tools
Linux has two tools for archiving: tar,zip
Zip can also compress files.  
The important commands for this section are:
```
user@system$ tar cvf backup.tar file.txt

user@system$ tar xvf backup.tar 

user@system$ tar cvjf backup.tar file.txt

user@system$ tar jxvf backup.tar 

```

Linux supports three common algorithms for data compression.These algorithms are xz,bzip2,gzip 
What is redirection?
   > We can save the output of commands by using redirection.
Several redirection commands in Linux:
  - >
  - >>
  - 2>
  - 2>>
  - &>

The important commands for this chapter are:
  - tar
  - grep
  - fgrep
  - egrep
  - cut
  - sort
  - find
  - seq
  - cpio
  - gzip
  - gunzip
  - bzip2
  - bunzip2
  - xz
  - unxz
  - zip
  - unzip

written on: June 19 2026
