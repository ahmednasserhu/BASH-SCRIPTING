# BASH-SCRIPTING

## Lab 1

## Using sed utility
#### 1- Display the lines that contain the word “lp” in /etc/passwd file.
![UNFOUND](https://github.com/ahmednasserhu/BASH-SCRIPTING/blob/main/bash-LAB1/1.png)
#### 2- Display /etc/passwd file except the third line.
![UNFOUND](https://github.com/ahmednasserhu/BASH-SCRIPTING/blob/main/bash-LAB1/2.png)
#### 3- Display /etc/passwd file except the last line.
![UNFOUND](https://github.com/ahmednasserhu/BASH-SCRIPTING/blob/main/bash-LAB1/3.png)
#### 4- Display /etc/passwd file except the lines that contain the word “lp”.
![UNFOUND](https://github.com/ahmednasserhu/BASH-SCRIPTING/blob/main/bash-LAB1/4.png)
#### 5- Substitute all the words that contain “lp” with “mylp” in /etc/passwd file.
![UNFOUND](https://github.com/ahmednasserhu/BASH-SCRIPTING/blob/main/bash-LAB1/5.png)
## Using awk utility
#### 1- Print full name (comment) of all users in the system.
![UNFOUND](https://github.com/ahmednasserhu/BASH-SCRIPTING/blob/main/bash-LAB1/6.png)
#### 2- Print login, full name (comment) and home directory of all users.( Print each line preceded by a line number)
![UNFOUND](https://github.com/ahmednasserhu/BASH-SCRIPTING/blob/main/bash-LAB1/7.png)
#### 3- Print login, uid and full name (comment) of those uid is greater than 500
![UNFOUND](https://github.com/ahmednasserhu/BASH-SCRIPTING/blob/main/bash-LAB1/8.png)
#### 4- Print login, uid and full name (comment) of those uid is exactly 500
![UNFOUND](https://github.com/ahmednasserhu/BASH-SCRIPTING/blob/main/bash-LAB1/9.png)
#### 5- Print line from 5 to 15 from /etc/passwd
![UNFOUND](https://github.com/ahmednasserhu/BASH-SCRIPTING/blob/main/bash-LAB1/10.png)
#### 6- Change lp to mylp
![UNFOUND](https://github.com/ahmednasserhu/BASH-SCRIPTING/blob/main/bash-LAB1/11.png)
![UNFOUND](https://github.com/ahmednasserhu/BASH-SCRIPTING/blob/main/bash-LAB1/11_.png)
#### 7- Print all information about greatest uid.
![UNFOUND](https://github.com/ahmednasserhu/BASH-SCRIPTING/blob/main/bash-LAB1/12.png)
#### 8- Get the sum of all accounts id’s.
![unfound](https://github.com/ahmednasserhu/BASH-SCRIPTING/blob/main/bash-LAB1/13.png)

### Bonus
#### 1. Get the sum of accounts id’s that has the same group.
![UNFOUND](https://github.com/ahmednasserhu/BASH-SCRIPTING/blob/main/bash-LAB1/bonus.png)

## Lab 2
### 1. Create a script that asks for user name then send a greeting to him.
![UNFOUND](https://github.com/ahmednasserhu/BASH-SCRIPTING/blob/main/bash-LAB2/1.png)
### 2. Create a script called s1 that calls another script s2 where:
#### a. In s1 there is a variable called x, it's value 5
#### b. Try to print the value of x in s2 by two different ways.
![UNFOUND](https://github.com/ahmednasserhu/BASH-SCRIPTING/blob/main/bash-LAB2/2.1.png)
![UNFOUND](https://github.com/ahmednasserhu/BASH-SCRIPTING/blob/main/bash-LAB2/2.2.png)
### 3. Create a script called mycp where:
#### a. It copies a file to another
#### b. It copies multiple files to a directory.
![UNFOUND](https://github.com/ahmednasserhu/BASH-SCRIPTING/blob/main/bash-LAB2/3.png)
### 4. Create a script called mycd where:
#### a. It changed directory to the user home directory, if it is called without arguments.
#### b. Otherwise, it change directory to the given directory.
![UNFOUND](https://github.com/ahmednasserhu/BASH-SCRIPTING/blob/main/bash-LAB2/4.png)
![UNFOUND](https://github.com/ahmednasserhu/BASH-SCRIPTING/blob/main/bash-LAB2/4_2.png)
### 5. Create a script called myls where:
#### a. It lists the current directory, if it is called without arguments.
#### b. Otherwise, it lists the given directory.
### 6. Enhance the above script to support the following options individually:
#### a. –l: list in long format
#### b. –a: list all entries including the hiding files.
#### c. –d: if an argument is a directory, list only its name
#### d. –i: print inode number
#### e. –R: recursively list subdirectories
![UNFOUND](https://github.com/ahmednasserhu/BASH-SCRIPTING/blob/main/bash-LAB2/5%2C6.png)
### 7. Create a script called mytest where:
#### a. It check the type of the given argument (file/directory)
#### b. It check the permissions of the given argument (read/write/execute)
![UNFOUND](https://github.com/ahmednasserhu/BASH-SCRIPTING/blob/main/bash-LAB2/7_1.png)
![UNFOUND](https://github.com/ahmednasserhu/BASH-SCRIPTING/blob/main/bash-LAB2/7_2.png)
### 8. Create a script called myinfo where:
#### a. It asks the user about his/her logname.
#### b. It print full info about files and directories in his/her home directory
#### c. Copy his/her files and directories as much as you can in /tmp directory.
#### d. Gets his current processes status.
![UNFOUND](https://github.com/ahmednasserhu/BASH-SCRIPTING/blob/main/bash-LAB2/8.png)
![UNFOUND](https://github.com/ahmednasserhu/BASH-SCRIPTING/blob/main/bash-LAB2/8_2.png)
