# Ex-01-Linux-Commands


## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/d51ef415-a892-4731-9b05-3fef2e8e3914)


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/0faa7b23-de4c-4592-bb25-a902ed47d576)

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/81bb495a-989c-4835-b4d7-0e4b7414e5e4)


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/b03496f8-ca0d-41b8-b872-41749c71a49b)


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/bdbffad3-95a4-4892-a4f3-b54730107a04)


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/8d0ca214-46d2-4412-8cb9-f45d0b448934)

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/97f5022b-c8dd-4499-a476-2e0c57f4dee5)



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/898e87b6-5d29-4f78-8eb1-4f4e0134d383)


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/c4e97a08-2564-438c-9a8e-19449d40340e)


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/7c359bb3-cc2e-4844-945c-1315ef775309)

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/1c6dd2ea-3105-42f0-8070-7f3c577bafe9)


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/8c9ad053-fb92-48cb-8c30-e91d2cc56462)


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/255d0678-8b75-4e28-9083-94305e39bc9a)

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/8962e832-ec99-4e7e-9bd1-d1e466771c23)


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/7d5c3a0a-855d-4bd1-8360-9a0c7a6f9bca)


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/e7769ac9-6c60-429d-96d7-8f875e785ba9)

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c
 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/38d50d9c-189d-46d4-8732-60e13bf9e5a7)

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/5b7d0883-26bf-4dcf-9f88-e04c3036cf0c)


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/7eddefc8-7d15-4db4-b9e3-6970c2c55cd5)


### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/2e6c97a9-8abb-4139-9123-af2386aacea0)

 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/9cea8c3a-d12b-40b5-8df9-247a1def7897)


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/1ee3d8c3-53db-4ec8-adbd-29241c573b35)


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/6ca6788e-0e5e-41cc-8ab3-c488913f3c1b)

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/37f1bea8-6366-4750-8cc1-9beba72cbb46)


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/42f5f8b7-ef23-4885-9007-2fa1ca8443ee)


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/44596c33-f03d-4fa2-af61-6a1a8e3cdd68)

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/9f5a98bd-07c8-4576-8a2c-defbd24b2204)

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”








## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
