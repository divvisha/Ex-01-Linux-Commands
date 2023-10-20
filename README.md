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
<img width="453" alt="ex1 vcc op1" src="https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/fcf029eb-f306-48aa-8ebd-122093c92920">


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd
<img width="450" alt="Screenshot 2023-10-20 085651" src="https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/d659692c-df28-4d56-9021-ac7b35cae24d">

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>
<img width="455" alt="Screenshot 2023-10-20 085809" src="https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/fd0ac99a-4745-4af7-b654-ce4085a360cb">


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>
<img width="450" alt="Screenshot 2023-10-20 085841" src="https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/dfb5a4e4-60c1-466f-b4b5-5f8d82106547">


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>
<img width="449" alt="Screenshot 2023-10-20 085902" src="https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/a3fa1ed5-b16c-4083-9cd1-e32004a1a21c">


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..
<img width="445" alt="Screenshot 2023-10-20 085931" src="https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/81e115cf-00cb-4eb7-81b1-83f37bdb33f7">

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>
<img width="433" alt="Screenshot 2023-10-20 090004" src="https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/fbd61126-4ff4-4aa2-8bdb-b36d8b52e573">



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name
<img width="449" alt="Screenshot 2023-10-20 090034" src="https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/793a5ddd-04e4-4f43-a2fa-aa8bd1553e95">


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>
<img width="430" alt="Screenshot 2023-10-20 090057" src="https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/010721bb-91b1-49c9-80f7-e987fa9c9c21">


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>
<img width="446" alt="Screenshot 2023-10-20 090128" src="https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/5161a168-8ba1-4f65-bf45-42d2532ccd32">

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files
<img width="450" alt="Screenshot 2023-10-20 090156" src="https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/c218071f-bdbc-400a-a3e5-e42114162784">


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>
<img width="442" alt="Screenshot 2023-10-20 090256" src="https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/84251ab2-7b11-48c6-bb72-56c06280d631">



### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>
<img width="402" alt="Screenshot 2023-10-20 090411" src="https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/9fce28e2-2b10-4e41-9a0c-5288e08fe96a">

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id
<img width="453" alt="Screenshot 2023-10-20 090441" src="https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/07ff3f80-839e-465d-a930-18c3d6d5c4b0">


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>
<img width="455" alt="Screenshot 2023-10-20 090531" src="https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/93c26aa1-7706-45ba-a092-b1d92e572eaf">


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>
<img width="454" alt="Screenshot 2023-10-20 090640" src="https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/4d41552a-cf45-4dc9-b461-f85dec9633fe">


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
<img width="426" alt="Screenshot 2023-10-20 091242" src="https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/f1fd7fc3-a6a2-40c6-9b5e-e11e7b6bb906">


### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….
<img width="445" alt="Screenshot 2023-10-20 091345" src="https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/e96fcaf4-2b69-4d67-83a8-69588ea52c92">



### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

### 22)	chmod 777 Command
Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
<img width="227" alt="Screenshot 2023-10-20 092136" src="https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/f0b61b05-d44c-427f-8bd7-584661726948">

 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>
<img width="452" alt="Screenshot 2023-10-20 092258" src="https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/d4b60d82-9e62-4e14-bd4f-d86ccc63d3a7">



### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..
<img width="452" alt="Screenshot 2023-10-20 092412" src="https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/012e8c8a-1f74-457f-b838-5505f6827a55">



### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>
<img width="383" alt="Screenshot 2023-10-20 092455" src="https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/9f8407a9-f4f2-4a34-84b2-defa92e2d9b5">

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal
<img width="428" alt="Screenshot 2023-10-20 092553" src="https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/829cb431-b9ae-4356-a314-9f58203ba417">



### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear
<img width="445" alt="Screenshot 2023-10-20 092625" src="https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/9684d801-cfc4-4af1-9f2a-cdd43a68ff38">


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>
<img width="443" alt="Screenshot 2023-10-20 092702" src="https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/0d33637c-d6af-47d6-99c4-b176549663bd">

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df
<img width="450" alt="Screenshot 2023-10-20 092733" src="https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/127508123/84e58265-dfe4-406a-8efe-ee1ad21726ed">


### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
