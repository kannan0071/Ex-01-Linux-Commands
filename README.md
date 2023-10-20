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
 
 ![image](https://github.com/kannan0071/Ex-01-Linux-Commands/assets/119641638/876876a6-dbae-4eb2-bf66-759263831767)



### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

![image](https://github.com/kannan0071/Ex-01-Linux-Commands/assets/119641638/14b629c9-d134-4ad8-9a17-be69f5c292bc)


 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

![image](https://github.com/kannan0071/Ex-01-Linux-Commands/assets/119641638/d8c5e8ae-4507-4f88-9f12-b8e7fb26ae66)



### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

![image](https://github.com/kannan0071/Ex-01-Linux-Commands/assets/119641638/e0b34679-14d7-4267-9a05-58b214dcbb26)



### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

![image](https://github.com/kannan0071/Ex-01-Linux-Commands/assets/119641638/e31c1ada-0741-4bab-bc7a-2d040927928e)



### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

![image](https://github.com/kannan0071/Ex-01-Linux-Commands/assets/119641638/433d5de5-581c-4392-9ae2-f0bbce8e8bed)


 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

![image](https://github.com/kannan0071/Ex-01-Linux-Commands/assets/119641638/0762756d-171e-441b-b14c-dd0332597ac1)




### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

![image](https://github.com/kannan0071/Ex-01-Linux-Commands/assets/119641638/08cd398d-3cc7-4c53-9090-8fa81571bdac)



### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

![image](https://github.com/kannan0071/Ex-01-Linux-Commands/assets/119641638/c8180f86-9338-4bed-ab19-493c0845ef2f)



### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

![image](https://github.com/kannan0071/Ex-01-Linux-Commands/assets/119641638/db7e6070-0476-42f7-aa3d-aeb2d03170a4)


 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

![image](https://github.com/kannan0071/Ex-01-Linux-Commands/assets/119641638/f40260c5-5a57-48f9-9884-73e4751a9436)



### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

![image](https://github.com/kannan0071/Ex-01-Linux-Commands/assets/119641638/055740cc-5dcd-444f-b089-6bd962a1a640)



### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

![image](https://github.com/kannan0071/Ex-01-Linux-Commands/assets/119641638/a7d6c496-ae76-4511-b61c-fb0d8cbdda03)


 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

![image](https://github.com/kannan0071/Ex-01-Linux-Commands/assets/119641638/202288a6-3f93-4302-8826-8b3aa75d9d3c)


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

![image](https://github.com/kannan0071/Ex-01-Linux-Commands/assets/119641638/0cec60c9-3eab-4a82-93d9-2c6edddddda9)



### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

![image](https://github.com/kannan0071/Ex-01-Linux-Commands/assets/119641638/87c89bd9-f79f-4421-8c8a-104bcc314737)


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

![image](https://github.com/kannan0071/Ex-01-Linux-Commands/assets/119641638/41184116-1fa6-4c1a-a880-e9c0ac72638f)


### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

![image](https://github.com/kannan0071/Ex-01-Linux-Commands/assets/119641638/3f94fe8f-ea0c-43bf-b12b-38a22fa2e43b)

### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

![image](https://github.com/kannan0071/Ex-01-Linux-Commands/assets/119641638/24af8992-102e-4980-813b-13dd30bebf33)


### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder


 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

![image](https://github.com/kannan0071/Ex-01-Linux-Commands/assets/119641638/72ef6ac7-39b5-4ad5-94f3-132392b63423)

### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

![image](https://github.com/kannan0071/Ex-01-Linux-Commands/assets/119641638/6a981860-c653-4385-ba1b-3dd5f98f5f0f)

### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

![image](https://github.com/kannan0071/Ex-01-Linux-Commands/assets/119641638/97a0db5a-b8df-48da-9179-e031a9f9e6c2)
 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

![image](https://github.com/kannan0071/Ex-01-Linux-Commands/assets/119641638/52d73f7a-00d9-4c47-a7e8-115e5ad41ca6)

### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

![image](https://github.com/kannan0071/Ex-01-Linux-Commands/assets/119641638/f6ad8d7f-9ed3-4028-adc6-89114525f5f9)

### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

![image](https://github.com/kannan0071/Ex-01-Linux-Commands/assets/119641638/c3618896-ea2a-40f4-aaf7-f9f228df85bc)
 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

![image](https://github.com/kannan0071/Ex-01-Linux-Commands/assets/119641638/dc9f658b-8774-4422-b4f7-91a0c962afcc)


### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”























## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
