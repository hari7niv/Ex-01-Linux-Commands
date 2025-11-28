# Ex-01-Linux-Commands
# NAME : HARI NIVEDHAN P
# REG. NO. : 212224220031
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

![Screenshot 2025-03-11 084332](https://github.com/user-attachments/assets/5760bbe8-342f-470f-ba8c-ce09dae3aaa8)

### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

![Screenshot 2025-03-11 084348](https://github.com/user-attachments/assets/f3221b98-a104-4504-8458-3d03cb6097ad)


### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

![Screenshot 2025-03-11 084408](https://github.com/user-attachments/assets/3bbf5d7a-de91-4ad9-8c4f-8df69ab6526a)

### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

![Screenshot 2025-03-11 084418](https://github.com/user-attachments/assets/dac3636c-2f02-4e0d-8e98-38b19b542692)

### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

![Screenshot 2025-03-11 084431](https://github.com/user-attachments/assets/5d78fef2-a080-4835-bfbe-7ef8a91b37e9)

### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

 ![Screenshot 2025-03-11 084449](https://github.com/user-attachments/assets/1dc1ad2a-7ca2-47bb-90af-6dd71e13277f)

### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

![Screenshot 2025-03-11 084458](https://github.com/user-attachments/assets/0441caf9-0865-4885-b172-156ede448986)

### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

![Screenshot 2025-03-11 084524](https://github.com/user-attachments/assets/550d021f-f44c-44c0-9a76-d6f20093d59c)

### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

![Screenshot 2025-03-11 084538](https://github.com/user-attachments/assets/8825dc3e-a298-4e47-a4d8-8af968622828)

### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

 ![Screenshot 2025-03-11 084547](https://github.com/user-attachments/assets/b2d85d4a-d6c1-4f2d-9343-a73e5d28fb90)

## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

![Screenshot 2025-03-11 090000](https://github.com/user-attachments/assets/c22ab1f9-ecaa-41ca-87b0-04a16a5409bb)

### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

![Screenshot 2025-03-11 090008](https://github.com/user-attachments/assets/81c91459-c6fb-4aed-9387-850fe10cf522)

### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

 ![Screenshot 2025-03-11 090015](https://github.com/user-attachments/assets/5c0ac3ac-3704-422a-97a8-f1899c55bd7c)

### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

![Screenshot 2025-03-11 090027](https://github.com/user-attachments/assets/d8d5fb14-eae5-43cf-adb9-2d4996f5b07a)

### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

![Screenshot 2025-03-11 090036](https://github.com/user-attachments/assets/74a3e901-d5db-41ee-a7d0-5ef8011694ca)

### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

![Screenshot 2025-03-11 090045](https://github.com/user-attachments/assets/3a20e4bb-8844-4c0f-b2fa-acb3870eec77)

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
![Screenshot 2025-03-11 090501](https://github.com/user-attachments/assets/38476168-bed2-47a5-8819-1272073e6127)

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

![Screenshot 2025-03-11 090517](https://github.com/user-attachments/assets/8b82762d-c789-40e6-90b0-97486ac48cdf)

### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

![Screenshot 2025-03-11 090529](https://github.com/user-attachments/assets/440ada9f-0ad5-4daa-bbca-efd0c01668f2)

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

![Screenshot 2025-03-11 090643](https://github.com/user-attachments/assets/89f609c1-9345-42bb-a28b-9ffbcc10eb4a)

### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

![Screenshot 2025-03-11 090652](https://github.com/user-attachments/assets/3cfa0d55-f58c-4776-8863-e0c77571ce03)

### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

 ![Screenshot 2025-03-11 090701](https://github.com/user-attachments/assets/39e686d7-b05d-4839-97a1-3ceff2695b65)

### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

![Screenshot 2025-03-11 090710](https://github.com/user-attachments/assets/7343f407-f8e7-4e51-b370-328ed7590806)

### 27)	clear Command


Linux clear command is used to clear the terminal screen.

Syntax: clear

![Screenshot 2025-03-11 090718](https://github.com/user-attachments/assets/0371e337-21db-4e1e-bdbf-bf56eaa8a5d3)

### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

 ![Screenshot 2025-03-11 090725](https://github.com/user-attachments/assets/2dea1eaa-906d-4125-aa76-5d8b48090e97)

### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

![Screenshot 2025-03-11 090734](https://github.com/user-attachments/assets/73713de6-0207-4213-9e4e-5c8a9bf46556)

### 30)	find Command


The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
