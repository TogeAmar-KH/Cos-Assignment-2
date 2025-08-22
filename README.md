# Cos-Assignment-2

## these are the solutions for Cos-Assignment-2

## Part A

** echo "Hello, World!"**
>it prints whatever is written in quotes.


** name="Productive"**
>it creates and assigns a value to a variable


** touch file.txt**
>it creates a file



** ls -a**
>it lists all the files even the hidden ones



<img width="1920" height="1080" alt="Screenshot from 2025-08-21 09-20-24" src="https://github.com/user-attachments/assets/904673d5-cde8-41ab-a1e4-45bf7b78041d" />

** rm file.txt**
>it removes the file.txt



** cp file1.txt file2.txt**
>it copies content from file1.txt to file2.txt



** mv file.txt /path/to/directory/**
>it moves file.txt to desired path


** chmod 755 script.sh**
>it gives the user permision as 7=111 meaning read write and execute and group and others as 5=101 which have only permissions of read and execute



** grep "pattern" file.txt**
>searches for lines containing "pattern" in file.txt and displays those matching lines



** kill PID** 
>The command kill PID terminates a running process by sending it a signal to stop.


** mkdir mydir && cd mydir && touch file.txt && echo "Hello, World!" > file.txt && cat file.txt**
>it creates a mydir directory and selects that directory then creates a file.txt then write 
into it and then finally shows the contents of that file

<img width="1920" height="1080" alt="Screenshot from 2025-08-21 10-20-00" src="https://github.com/user-attachments/assets/b938f742-734a-499d-9818-cfbef1670c1a" />


** ls -l | grep ".txt"**
>it displays all the text files with all the details of permissions also


** cat file1.txt file2.txt | sort | uniq**
>it displays contents by combining them and sorting then and then it shows only the unique lines from both

<img width="1917" height="652" alt="Screenshot from 2025-08-21 10-30-20" src="https://github.com/user-attachments/assets/f8e94c9f-6a55-419e-a7a6-2cdb5045148d" />


** ls -l | grep "^d"**
>it lists only the directories because ls -l dislpays all in detail but grep shows only starting with d which are directories


<img width="1917" height="597" alt="Screenshot from 2025-08-21 10-39-25" src="https://github.com/user-attachments/assets/4ba190b0-8f65-4143-8d7b-67703b1b1968" />



** grep -r "pattern" /path/to/directory/**
>it searches for word pattern in all the files and subdirectories of given path recursively




**cat file1.txt file2.txt | sort | uniq –d**
>it finds and shows only the duplicate lines that appear in both files
>just like the recent command but difference is just -d which makes it display only duplicates



** chmod 644 file.txt**
>it give user permission to read and write and only read to group and others as 6=110,4=100



** cp -r source_directory destination_directory**
>it copies a directory and all the content of that directory to specified directory. i tried it doing it without the -r but i got something else.

<img width="1920" height="1080" alt="Screenshot from 2025-08-21 21-23-24" src="https://github.com/user-attachments/assets/d5c2f522-cb8d-4f76-9210-f0f4a48aec5e" />



** find /path/to/search -name "*.txt"**
>it searches for files which have .txt extension in the specified path or directory


** chmod u+x file.txt**
>it gives user the permission to execute file\.txt as u denotes user and + show that permission is given and x is permission to execute


** echo $PATH**
>this command shows the contents of path environment variable which shows all the directories that systems looks for
>executable commands.like if use ls command its most likely in the very first directory and if you search for python it will be in some other
>directory



## Part B
### Identify True or False:


**1. ls is used to list files and directories in a directory.**
>**its true**

**2. mv is used to move files and directories.**
>**true**

**3. cd is used to copy files and directories.**
>**false. its used to change directory**


**4. pwd stands for "print working directory" and displays the current directory.**
>**True**


**5. grep is used to search for patterns in files.**
>**true**


**6. chmod 755 file.txt gives read, write, and execute permissions to the owner, and read and execute
permissions to group and others.**
>**True**


7. mkdir -p directory1/directory2 creates nested directories, creating directory2 inside directory1
if directory1 does not exist.
>**True**


9. rm -rf file.txt deletes a file forcefully without confirmation.
>**true**

### Identify the Incorrect Commands: 

**1. chmodx is used to change file permissions.**
>**incorrect**

**2. cpy is used to copy files and directories.**
>**incorrect**

**3. mkfile is used to create a new file.**
>**incorrect**

**4. catx is used to concatenate files.**
>**incorrect**

**5. rn is used to rename files.**
>**incorrect**


## Part c

**Question 1**: Write a shell script that prints "Hello, World!" to the terminal

<img width="1026" height="749" alt="Screenshot from 2025-08-22 06-58-10" src="https://github.com/user-attachments/assets/4fdc9fdd-341d-4992-bbb5-7ec1010a7ed9" />


**Question 2: Declare a variable named "name" and assign the value "CDAC Mumbai" to it. Print the
value of the variable.

**Question 3: Write a shell script that takes a number as input from the user and prints it.**

**Question 4: Write a shell script that performs addition of two numbers (e.g., 5 and 3) and prints the
result.**


<img width="1477" height="708" alt="image" src="https://github.com/user-attachments/assets/86ca96c7-3189-4bef-81db-207ede6d6bcd" />


**Question 5: Write a shell script that takes a number as input and prints "Even" if it is even, otherwise
prints "Odd".**


<img width="1026" height="749" alt="image" src="https://github.com/user-attachments/assets/a43b2acc-e79b-464b-ab84-cd286904efa2" />



**Question 6: Write a shell script that uses a for loop to print numbers from 1 to 5.**

<img width="1026" height="749" alt="image" src="https://github.com/user-attachments/assets/874ed7ed-80de-493a-aed0-93cfdee8e82c" />

**Question 7: Write a shell script that uses a while loop to print numbers from 1 to 5.**

<img width="1026" height="749" alt="image" src="https://github.com/user-attachments/assets/15d524f0-b69e-4102-adf8-3ab0386010a4" />

**Question 8: Write a shell script that checks if a file named "file.txt" exists in the current directory. If it
does, print "File exists", otherwise, print "File does not exist".**


<img width="1026" height="749" alt="image" src="https://github.com/user-attachments/assets/ef1cac64-d867-4240-ac8f-fa1df046c3df" />


**Question 9: Write a shell script that uses the if statement to check if a number is greater than 10 and
prints a message accordingly.**

<img width="1026" height="749" alt="Screenshot from 2025-08-22 15-09-49" src="https://github.com/user-attachments/assets/91143b95-f2a9-42de-8335-d85cd985f830" />


**Question 10: Write a shell script that uses nested for loops to print a multiplication table for numbers
from 1 to 5. The output should be formatted nicely, with each row representing a number and each
column representing the multiplication result for that number.**
>**here i was having problem with printing values with spaces then i used empty echo**


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/86609f63-151b-42e7-9a62-9a2baa62eb98" />


**Question 11: Write a shell script that uses a while loop to read numbers from the user until the user enters
a negative number. For each positive number entered, print its square. Use the break statement to exit the
loop when a negative number is entered.**

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/716cdf67-20a3-413d-93f3-2b51731c1107" />


## Part D

### Common Interview Questions (Must know) 
>**going to do it later**


## Part E

**1. Consider the following processes with arrival times and burst times:
 | Process | Arrival Time | Burst Time |
 |---------|--------------|------------|
 | P1 | 0 | 5 |
 | P2 | 1 | 3 |
 | P3 | 2 | 6 |
 Calculate the average waiting time using First-Come, First-Served (FCFS) scheduling.**
 >**average waiting time is 4.3 as all three wait for 0,5,8 resp.**
>

**onsider the following processes with arrival times and burst times:
 | Process | Arrival Time | Burst Time |
 |---------|--------------|------------|
 | P1 | 0 | 3 |
 | P2 | 1 | 5 |
 | P3 | 2 | 1 |
 | P4 | 3 | 4 |
 Calculate the average turnaround time using Shortest Job First (SJF) scheduling.**
 >**average turnaround time is 5.5 as turnarounds are 3,12,2,5 resp**
>


**3. Consider the following processes with arrival times, burst times, and priorities (lower number
indicates higher priority):
 | Process | Arrival Time | Burst Time | Priority |
 |---------|--------------|------------|----------|
 | P1 | 0 | 6 | 3 |
 | P2 | 1 | 4 | 1 |
 | P3 | 2 | 7 | 4 |
 | P4 | 3 | 2 | 2 |
 Calculate the average waiting time using Priority Scheduling.**
 >**average waiting time is 3**
>


**4. Consider the following processes with arrival times and burst times, and the time quantum for
Round Robin scheduling is 2 units:
 | Process | Arrival Time | Burst Time |
 |---------|--------------|------------|
 | P1 | 0 | 4 |
 | P2 | 1 | 5 |
 | P3 | 2 | 2 |
 | P4 | 3 | 3 |
 Calculate the average turnaround time using Round Robin scheduling.** 
>**average turnaround time is 6.5 as turnaround times are 10,11,4,11 resp**
>

