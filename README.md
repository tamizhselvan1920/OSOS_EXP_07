# Exp 7 : Find the string 

# AIM:
To find a string "home" in /etc/passwd and store it.  

# EQUIPMENTS REQUIRED:
Hardware: Minimum 4 GB RAM and 25 GB storage – essential for running services like Cockpit and handling system updates smoothly.
Software: Red Hat Enterprise Linux (RHEL) or any open-source Linux OS like Fedora or CentOS Stream – used for system administration and repository creation.

# PROCEDURE & COMMENTS:
1. grep "home" /etc/passwd: This command utilizes the grep utility, which stands for 
“global regular expression print.” It searches for the text “home” within the /etc/passwd file. 
Now, let’s break down what each part of this command does: 
◦ grep: The command itself. 
◦ "home": The search pattern enclosed in double quotes. In this case, we’re looking 
for lines containing the word “home.” 
◦ /etc/passwd: The file we’re searching within. The /etc/passwd file is a critical 
system file on Unix-like systems that stores information about user accounts. Each 
line in this file represents a user and contains details such as the username, user ID 
(UID), home directory, and default shell. 
◦ When you run this command, it scans through the /etc/passwd file and displays 
any lines that match the search pattern (i.e., lines containing “home”). Typically, 
these lines correspond to user accounts and their associated home directories. 
2. grep "home" /etc/passwd > /root/search.txt: This command builds upon the 
previous one but adds a redirection step. Let’s break it down: 
>: The greater-than symbol is used for output redirection. It takes the output produced by the 
grep command and saves it to a file. 
/root/search.txt: The target file where the output will be stored. In this case, it’s a file 
named search.txt located in the /root directory. 
So, instead of displaying the matching lines on the screen, this command redirects them to the 
specified file. If you examine the contents of search.txt, you’ll find the same information as 
displayed by the initial grep command.

# EXPECTED OUTPUT:


![Screenshot 2025-06-01 145739](https://github.com/user-attachments/assets/fa5f37af-61e6-4861-b207-299dcc7a9214)
# RESULT:
Thus the string has been found and stored successfully. 
