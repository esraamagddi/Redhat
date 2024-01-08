lab1

### 2. What is the difference between cat and more command?
####   Both display rhe content of the file but the difference is that in case of larger files, 'cat' command output will scroll off your screen while 'more' command displays output one screenful at a time (page by page ).
    

### 3. What is the difference between rm and rmdir using man?
#### rm 
##### Remove files or directories




##### SYNOPSIS rm [OPTION]... [FILE]...
#### DESCRIPTION
#####  This manual page documents the GNU version of rm. rm removes each specified file. By default, it does not remove directories.    
#### rmdir
##### Remove empty directories
##### SYNOPSIS rmdir [OPTION]... DIRECTORY...
#### DESCRIPTION    
##### Remove the DIRECTORY(ies), if they are empty.

### 4. Create the following hierarchy under your home directory:
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap1/lap1_44.png)

#### a. Remove dir11 in one-step. What did you notice? And how did you overcome that?
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap1/lap1_5.png)

#### b. Then remove dir12 using rmdir â€“p command. State what happened to the
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap1/lap1_6.png)

#### c. The output of the command pwd was /home/user. Write the absolute and relative path for the file mycv
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap1/lap1_7.png)

### 5. Copy the /etc/passwd file to your home directory making its name is mypasswd.
### 6. Rename this new file to be oldpasswd.
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap1/lap1_6_6.png)

### 7. You are in /usr/bin, list four ways to go to your home directory
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap1/lap1_7.png)

### 8. List Linux commands in /usr/bin that start with letter w
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap1/lap1_8.png)

### 9. Display the first 4 lines of /etc/passwd
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap1/lap1_9.png)

### 10.Display the last 7 lines of /etc/passwd
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap1/lap1_10.png)

### 11.Display the man pages of passwd the command and the file sequentially in one command.
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap1/lap1_11.png)

### 12.Display the man page of the passwd file.
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap1/lap1_12.png)


### 13.Display a list of all the commands that contain the keyword passwd in their man page.
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap1/lap1_13.png)



## Lab2
### 1. Create a user account with the following attribute and username: islam and Fullname/comment: Islam Askar and Password: islam
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap2/Screenshot%20from%202023-11-22%2009-20-48.pngng)

### 2. Create a user account with the following attribute and Username: baduser and Full name/comment: Bad User and Password: baduser
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap2/Screenshot%20from%202023-11-22%2009-20-48.png)

### 3. Create a supplementary (Secondary) group called pgroup with group ID of 30000
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap2/Screenshot%20from%202023-11-22%2009-30-32.png)

### 4. Create a supplementary group called badgroup
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap2/Screenshot%20from%202023-11-22%2009-30-32.png)

### 5. Add islam user to the pgroup group as a supplementary group
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap2/Screenshot%20from%202023-11-22%2009-30-32.png)

### 6. Modify the password of islam's account to password
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap2/lap2-6.png)

### 7. Modify islam's account so the password expires after 30 days
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap2/lap2-7.png)

### 8. Lock bad user account so he can't log in
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap2/lap2-8.png)

### 9. Delete bad user account
![UNFOUND](https://github.com/yossrmohammed/RedHat-System-Administration-/blob/main/lab2/q9.png)

### 10. Delete the supplementary group called badgroup.
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap2/lap2-9.png)

### 13.Create a folder called myteam in your home directory and change its permissions to read only for the owner.
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap2/lap2-13.png)

### 14.Log out and log in by another user.
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap2/lap2-14%2B15.png)
### 15.Try to access (by cd command) the folder (myteam)
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap2/lap2-14%2B15.png)

### 17.What are the minimum permission needed for:
#### Copy a directory (permission for source directory and permissions for target parent directory)
##### source directory : r-x
##### target parent directory: -wx
#### Copy a file (permission for source file and and permission for target parent directory)
##### file: r--
##### source directory : --x
##### target parent directory : -wx
#### Delete a file
##### file: ---
##### source directory: -wx
#### Change to a directory
##### --x
#### List a directory content (ls command)
##### r--
#### View a file content (more/cat command)
##### r--
#### Modify a file content
##### for interactive tool like vi need rw-
##### for non interative tool vi need -w-


## Lab 3
### 1. Using vi write your CV in the file mycv. Your CV should include your name, age, school,college, experience,...
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap3/Screenshot%20from%202023-11-26%2014-44-47.png)

### 2. Open mycv file using vi command then: Without using arrows state how to:
#### a. using j key
#### b. using k key
#### c. using /age
#### d. :5
#### e.using D
#### f.using $
### 3. List the available shells in your system.
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap3/Screenshot%20from%202023-11-26%2014-50-18.png)
### 4. List the environment variables in your current shell.
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap3/Screenshot%20from%202023-11-26%2014-50-18.png)
### 5. List all of the environment variables for the bash shell.
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap3/Screenshot%20from%202023-11-26%2015-08-08.png)
### 6. What are the commands that list the value of a specific variable?
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap3/Screenshot%20from%202023-11-26%2015-08-08.png)

### 7. Display your current shell name.
   ![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap3/Screenshot%20from%202023-11-26%2015-08-08.png)

### 11. Create a Bash shell alias named ls for the â€œls â€“lâ€ command
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap3/Screenshot%20from%202023-11-26%2015-08-08.png)


## Lab 4

### 1. List the user commands and redirect the output to /tmp/commands.list
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap4/Screenshot%20from%202023-11-25%2019-46-54.png)

### 2. Count the number of user commands
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap4/Screenshot%20from%202023-11-25%2019-46-54.png)     

### 3. Get all the users names whose first character in their login is â€˜gâ€™.
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap4/Screenshot%20from%202023-11-25%2019-46-54.png)   

### 4. Get the logins name and full names (comment) of logins starts with â€œgâ€.
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap4/Screenshot%20from%202023-11-25%2019-46-54.png)


### 5. Save the output of the last command sorted by their full names in a file.
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap4/Screenshot%20from%202023-11-25%2019-46-54.png)

### 6. Write two commands: first: to search for all files on the system that named .bash_profile. Second: sorts the output of ls command on / recursively, Saving their output and error in 2 different files and sending them to the background.
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap4/Screenshot%20from%202023-11-25%2019-46-54.png)

### 7. Display the number of users who is logged now to the system.
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap4/Screenshot%20from%202023-11-25%2020-05-15.png)

### 8.Display lines 7 to line 10 of /etc/passwd file
![UNFOUND](https://github.com/yossrmohammed/RedHat-System-Administration-/blob/main/lab4/q8.png)

### 9. What happens if you execute:

#### a. cat filename1 | cat filename2
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap4/Screenshot%20from%202023-11-25%2020-05-15.png)

#### b. Tcat filename1 | cat filename2
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap4/Screenshot%20from%202023-11-25%2020-05-19.png)

#### c. ls /etc/passwd | wc â€“l
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap4/Screenshot%20from%202023-11-25%2020-05-15.png)

### 10.Issue the command sleep 100.
### 11.Stop the last command.
### 12.Resume the last command in the background
### 13.Issue the jobs command and see its output.
### 14.Send the sleep command to the foreground and send it again to the background.
### 15.Kill the sleep command.
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap4/Screenshot%20from%202023-11-25%2020-10-52.png)
### 16.Display your processes only
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap4/Screenshot%20from%202023-11-25%2020-13-01.png)
### 17.Display all processes except yours
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap4/Screenshot%20from%202023-11-25%2020-13-33.png)
### 18.Use the pgrep command to list your processes only
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap4/Screenshot%20from%202023-11-25%2020-14-15.png)
### 19.Kill your processes only.
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap4/Screenshot%20from%202023-11-25%2020-14-41.png)


## lab5
#### 1. Compress a file by compress, gzip, zip commands and decompress it again. State the differences between compress and gzip commands.
![UNFOUND](lap5/5_1.png)

#### 2. What is the command used to view the content of a compressed file.
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap5/5_2.png)

#### 3. Backup /etc directory using tar utility.
![UNFOUND](lap5/5_3.png)

#### 4. Starting from your home directory, find all files that were modified in the last two day.
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap5/5_4.png)

#### 5. Starting from /etc, find files owned by root user.
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap5/5_5.png)

#### 6. Find all directories in your home directory.
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap5/5_6.png)

#### 7. Write a command to search for all files on the system that, its name is â€œ.profileâ€.
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap5/5_7.png)

#### 8. Identify the file types of the following: /etc/passwd, /dev/pts/0, /etc, /dev/sda
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap5/5_8.png)

#### 9. List the inode numbers of /, /etc, /etc/hosts.
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap5/5_9.png)
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap5/5_9_3.png)
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap5/5_10.png)

#### 10. Copy /etc/passwd to your home directory, use the commands diff and cmp, and Edit in the
file you copied, and then use these commands again, and check the output.
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap5/5_10_1.png)

#### 11. Create a symbolic link of /etc/passwd in /boot.
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap5/5_11.png) 

#### 12. Create a hard link of /etc/passwd in /boot. Could you? Why
##### 
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap5/5_12.png)
###### creating a hard link between files on different file systems is not allowed. Hard links are restricted to the same file system because they share the same inode, and inodes are specific to a file system


## Lab6
###
### 1.Use systemctl to view the status of all the system services.
![UNFOUND](lap6/6_1.png)
### 2.Change the default run level back to multi-user.target and reboot.
![UNFOUND](lap6/6_2.png)
### 3.Send mail to the root user.
![UNFOUND](lap6/6_3.png)
### 4.Verify that you have received this mail.
![UNFOUND](lap6/6_4.png)
### 5.Use  systemctl utility to stop postfix service
![UNFOUND](lap6/6_5.png)
### 6.Send mail again to the root user.
![UNFOUND](lap6/6_6.png)
### 7.Verify that you have received this mail.
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap6/6_7.png)
### 8.Use systemctl utility to start postfix service
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap6/6_8.png)
### 9.Verify that you have received this mail.
![UNFOUND](https://github.com/esraamagddi/Redhat/blob/7f8ac422e29f571691f3218809204cfc23e12b1e/lap6/6_44.png)




