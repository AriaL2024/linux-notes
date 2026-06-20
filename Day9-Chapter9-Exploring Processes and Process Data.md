# Linux Essentials


##  Day 9 - Chapter 9:Exploring Processes and Process Data

What is a Software Package Management System(PMS)?
  > By using a PMS, Linux administrators can install software packages on Linux.
A PMS handles software dependencies, architecture info, version numbers, binary files, and libraries.
What can PMS do?
  - install a package
  - remove a package
  - update a package
  - upgrade a package
What is a Repository?
  > A repository is a database for storing software. Repositories are usually located on a disk or a server on the Internet.
Each country has several repositories for internal usage.

Types of PMS:
  - Offline: It just installs package files on linux
  - Online: It can download packages file from the internet and install them

Some Offline PMSs:
  - dpkg: It is used in Debian, Ubuntu
  - rpm: It is used in CentOS and Redhat
  - tarballs: It is used in Slack

Some Online PMSs:
  - apt-get: this is used by Debian and Ubuntu
  - yum: this is used by CentOS and Redhat
  - zypper: this is used by OpenSUSE
  - snap: this is used by Ubuntu

The important commands for online PMSs are:
```
user@system$ yum install vscode

user@system$ yum remove vscode

user@system$ yum update

user@system$ yum upgrade

user@system$ apt-get install vscode

user@system$ apt-get remove vscode

user@system$ apt-get update

user@system$ apt-get upgrade
```

The important commands for offline PMSs are:
```
user@system$ rpm -i vscode.rpm

user@system$ rpm -e vscode vscode

user@system$ rpp -q vscode

user@system$ rpm -ql vscode

user@system$ dpkg -i vscode.deb

user@system$ dpkg -r vscode.deb

user@system$ dpkg -L

user@system$ dpkg -p vscode
```
What is a process?
   > A process is a task created by a program or a user.
The CPU must execute a process and finish it.
Each process has a unique identification number called a "Process ID (PID)".
Each process has a parent.
Linux users can see processes using the top and ps tools.
Linux creates a tree structure for processes.

The important commands for this section are:

```
user@system$ ps -aux

user@system$ ps -axjf 

user@system$ ps -u aria

user@system$ top

```
What is a network log?
A network log typically contains records of events categorized as errors, warnings, or informational activities.
Linux logs are saved in the /var/log directory.
Also, a number of the kernel logs are stored in the "Kernel Ring Buffer (KRB)".
The important commands for this section are:

```
user@system# demsg
```

written on: June 20 2026
