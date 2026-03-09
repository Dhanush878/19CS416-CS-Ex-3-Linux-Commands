# 19CS416-CS-Ex-3-Linux-Commands
### NAME: DHANUSH M D
### REG. NO.: 212224100011

## Introduction to Linux
**Linux** is an open-source operating system, and its kernel is the heart of the OS, facilitating communication between hardware and software. One of the key advantages of Linux is its customizability; developers can modify the Linux kernel to create their own tailored operating systems.

## Linux Commands

Linux commands are executed in the terminal, which is case-sensitive. This guide covers some basic and advanced commands used in Linux.

### 1. `ls` Command

The `ls` command is used to display a list of contents in a directory.

**Syntax:** 
```bash
ls
```

**Output:**

<img width="783" height="57" alt="image" src="https://github.com/user-attachments/assets/f5a47861-18c6-4691-bf31-71ee845752b9" />

### 2. `pwd` Command

The `pwd` command displays the location of the current working directory.

**Syntax:**
```bash
pwd
```

**Output:**

<img width="250" height="67" alt="image" src="https://github.com/user-attachments/assets/f109b5da-c6db-483c-b169-7bfca0a073c2" />


### 3. `mkdir` Command

The `mkdir` command is used to create a new directory.

**Syntax:**
```bash
mkdir <directory_name>
```

**Output:**

<img width="795" height="92" alt="image" src="https://github.com/user-attachments/assets/cbc52820-d96a-42aa-a805-74967f55fb63" />


### 4. `rmdir` Command

The `rmdir` command is used to delete a directory.

**Syntax:**
```bash
rmdir <directory_name>
```

**Output:**

<img width="766" height="102" alt="image" src="https://github.com/user-attachments/assets/c51c75a9-fa58-4bcc-aa8c-9b5509b29c93" />


### 5. `cd` Command

The `cd` command is used to change the current directory.

**Syntax:**
```bash
cd <directory_name>
```

**Output:**

<img width="598" height="88" alt="image" src="https://github.com/user-attachments/assets/3f36eba6-db64-4661-b86a-021549897801" />


### 6. `cat` Command

The `cat` command is used to create, display, and concatenate files.

**Syntax:**
```bash
cat [OPTION]... [FILE]...
```

**Output:**

<img width="362" height="212" alt="image" src="https://github.com/user-attachments/assets/09efb782-1edc-416d-aebd-fae177fc4ca6" />

### 7. `cp` Command

The `cp` command is used to copy files or directories.

**Syntax:**
```bash
cp <source_file> <destination_file>
```

**Output:**

<img width="315" height="157" alt="image" src="https://github.com/user-attachments/assets/12fc3307-5834-445e-b1d0-9bbe63255651" />


### 8. `gedit` Command

`gedit` is a general-purpose text editor used to create and edit text files.

**Syntax:**
```bash
gedit <file_name>
```

**Output:**

<img width="415" height="37" alt="image" src="https://github.com/user-attachments/assets/3a0038a2-4240-4c8c-97b5-2eb0aca63841" />


### 9. `su` Command

The `su` command provides administrative access to another user.

**Syntax:**
```bash
su <username>
```

**Output:**

<img width="276" height="105" alt="image" src="https://github.com/user-attachments/assets/abadda1d-b010-48f3-94b6-23557eb24ed6" />


### 10. `mv` Command

The `mv` command is used to move a file or directory from one location to another.

**Syntax:**
```bash
mv <file_name> <directory_path>
```

**Output:**

<img width="391" height="317" alt="image" src="https://github.com/user-attachments/assets/28af63c8-37d8-495f-a18f-e8151d93fdf9" />


### 11. `rename` Command

The `rename` command is used to rename files.

**Syntax:**
```bash
rename 's/old-name/new-name/' <files>
```

**Output:**

<img width="472" height="203" alt="image" src="https://github.com/user-attachments/assets/2e33b4fa-254e-4af5-a08b-b846553a70b2" />


### 12. `head` Command

The `head` command displays the first 10 lines of a file.

**Syntax:**
```bash
head <file_name>
```

**Output:**

<img width="423" height="647" alt="image" src="https://github.com/user-attachments/assets/360a7499-4039-47e6-980b-e390309b5616" />


### 13. `tail` Command

The `tail` command displays the last 10 lines of a file.

**Syntax:**
```bash
tail <file_name>
```

**Output:**

<img width="305" height="275" alt="image" src="https://github.com/user-attachments/assets/84bf474c-e3b8-4ffb-b955-0ab9e4a5977f" />


### 14. `id` Command

The `id` command displays the user ID (UID) and group ID (GID).

**Syntax:**
```bash
id
```

**Output:**

<img width="807" height="31" alt="image" src="https://github.com/user-attachments/assets/4f52e986-6d38-43a7-ae0d-1f173730831c" />


### 15. `grep` Command

The `grep` command is used to search for a pattern within files.

**Syntax:**
```bash
command | grep <search_word>
```

**Output:**

<img width="368" height="77" alt="image" src="https://github.com/user-attachments/assets/ee9fda3b-8878-46b3-a3b2-7a2ad3ef217e" />


### 16. `tr` Command

The `tr` command is used to translate or delete characters.

**Syntax:**
```bash
command | tr <old> <new>
```

**Output:**

<img width="422" height="363" alt="image" src="https://github.com/user-attachments/assets/108cd05c-3a5b-4e41-b5d0-6e14e50a7d27" />


### 17. `chmod` Command

The `chmod` command is used to change the access mode (permissions) of a file.

**Syntax:**
```bash
chmod <options> <permissions> <file_name>
```

**Output:**

<img width="522" height="138" alt="image" src="https://github.com/user-attachments/assets/2e015f71-baa0-40d5-8002-42937e42cc3a" />


### 18. `tar` Command

The `tar` command is used to create or extract archive files.

**Syntax:**
```bash
tar [options] [archive-file] [files_to_archive]
```

**Output:**

<img width="405" height="185" alt="image" src="https://github.com/user-attachments/assets/73654aa4-e11d-4901-9334-820aefde655a" />


### 19. `chown` Command

The `chown` command is used to change the ownership of a file.

**Syntax:**
```bash
chown <owner_name> <file_name>
```

**Output:**

<img width="532" height="155" alt="image" src="https://github.com/user-attachments/assets/b8a2b8fa-b095-45f8-974c-a379a99a7bde" />


### 20. `make` Command

The `make` command is used to build and maintain groups of programs.

**Syntax:**
```bash
make [-f makefile] [options] [targets]
```

**Output:**

<img width="253" height="72" alt="image" src="https://github.com/user-attachments/assets/b319bc46-9b86-43af-8f1b-ac218c49d9d9" />


### 21. `ifconfig` Command

The `ifconfig` command is used to configure network interfaces.

**Syntax:**
```bash
ifconfig [options] [interface]
```

**Output:**

<img width="747" height="87" alt="image" src="https://github.com/user-attachments/assets/5bebe4e9-28fc-40b8-bf5d-2618c5e4697f" />


### 22. `chmod 777` Command

The `chmod 777` command gives read, write, and execute permissions to the owner, group, and others.

**Syntax:**
```bash
chmod 777 <file_name>
chmod -R 777 /path/to/file/or/folder
```

**Output:**

<img width="542" height="137" alt="image" src="https://github.com/user-attachments/assets/509b3a93-ae93-47c1-852b-e9d37513cf37" />


### 23. `host` Command

The `host` command is used to display the IP address for a given domain name.

**Syntax:**
```bash
host <domain_name> or <ip_address>
```

**Output:**

<img width="608" height="120" alt="image" src="https://github.com/user-attachments/assets/4cb52485-72e9-4b68-9967-dbbfb70a7fdc" />


### 24. `gzip` Command

The `gzip` command is used to compress files, replacing the original file with a compressed one with a `.gz` extension.

**Syntax:**
```bash
gzip <file1> <file2> <file3>...
gzip filename.txt
gzip -d filename.txt.gz
gzip -k filename.txt
gzip -l filename.txt.gz
```

**Output:**

<img width="536" height="227" alt="image" src="https://github.com/user-attachments/assets/d12db83e-7755-411c-b11c-99bc894bf78e" />


### 25. `sort` Command

The `sort` command is used to sort the contents of a file alphabetically.

**Syntax:**
```bash
sort <file_name>
```

**Output:**

<img width="265" height="363" alt="image" src="https://github.com/user-attachments/assets/2e8d9d29-4e4b-47f7-9fe8-52636da381a6" />


### 26. `cal` Command

The `cal` command displays the current month's calendar with the current date highlighted.

**Syntax:**
```bash
cal
```

**Output:**

<img width="318" height="233" alt="image" src="https://github.com/user-attachments/assets/8a213217-ee35-47dc-a4c1-543588cb31b7" />


### 27. `clear` Command

The `clear` command clears the terminal screen.

**Syntax:**
```bash
clear
```

**Output:**

<img width="683" height="772" alt="image" src="https://github.com/user-attachments/assets/48ac904b-7486-4035-8a97-d0e0117f2831" />

<img width="547" height="286" alt="image" src="https://github.com/user-attachments/assets/0a377cda-a9d4-40fd-9f60-1c7a4d256be7" />


### 28. `mail` Command

The `mail` command is used to send emails from the command line.

**Syntax:**
```bash
mail
```

**Output:**

<img width="771" height="65" alt="image" src="https://github.com/user-attachments/assets/5291a3d5-ef0d-4ba9-954d-d08e274526cc" />


### 29. `df` Command

The `df` command displays the disk space usage of file systems.

**Syntax:**
```bash
df
```

**Output:**

<img width="761" height="248" alt="image" src="https://github.com/user-attachments/assets/ddd09234-3826-4d7e-9a51-84441104c848" />


### 30. `find` Command

The `find` command is used to search for files in a directory hierarchy.

**Syntax:**
```bash
find <directory> -name <file_name>
```

**Output:**

<img width="342" height="96" alt="image" src="https://github.com/user-attachments/assets/a855266b-9b2b-4bcc-8edb-6c76819bc11c" />


<img width="381" height="85" alt="image" src="https://github.com/user-attachments/assets/cbd77c63-1a73-4b71-8bfb-10e0b9bfd642" />


## Result
Thus, the execution of various Linux commands is executed successfully using Kali Linux.
