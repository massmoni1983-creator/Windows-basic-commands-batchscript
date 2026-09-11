# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

<img width="1849" height="144" alt="1" src="https://github.com/user-attachments/assets/99610933-b3db-4ed1-8d59-6f6c71c05009" />


## COMMAND AND OUTPUT

Remove the directory "my-folder"

<img width="1821" height="121" alt="2" src="https://github.com/user-attachments/assets/258eaedd-d83d-4ced-84c9-c479e2fe6d15" />


## COMMAND AND OUTPUT


Create the file Rose.txt

<img width="1697" height="415" alt="3" src="https://github.com/user-attachments/assets/208b53cf-59a2-4c93-a251-940f1caad457" />


## COMMAND AND OUTPUT


Create the file hello.txt using echo and redirection

<img width="1736" height="117" alt="4" src="https://github.com/user-attachments/assets/f2104916-c6bf-43b4-98ff-fa625ef2469f" />


## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt

<img width="1707" height="145" alt="5" src="https://github.com/user-attachments/assets/ac56e173-3fd2-4900-b9bd-37d0f1762e7f" />


## COMMAND AND OUTPUT

Remove the file hello1.txt

<img width="1771" height="49" alt="6" src="https://github.com/user-attachments/assets/86305681-2dc5-42cd-bbe6-26f2881d9aaa" />


## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

<img width="1758" height="183" alt="7" src="https://github.com/user-attachments/assets/ed71b1a9-f2b2-4231-902b-882df1d6e98d" />


## COMMAND AND OUTPUT

List out all the associated file extensions 

<img width="1715" height="819" alt="8" src="https://github.com/user-attachments/assets/7c8783f9-a381-4d33-8bde-03c6ef511f1d" />


## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt

<img width="1358" height="170" alt="9" src="https://github.com/user-attachments/assets/883f7ce9-a594-4552-ab80-0ca2c8763075" />


## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="1806" height="69" alt="10" src="https://github.com/user-attachments/assets/b1b5e141-468c-47c4-b5c6-445042c8a8e5" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="1821" height="203" alt="11" src="https://github.com/user-attachments/assets/88e71cf7-49ae-49f6-ba21-d561048a254a" />


Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="1423" height="167" alt="12" src="https://github.com/user-attachments/assets/b73add39-b802-4278-8b79-1878dea90436" />


Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="1812" height="84" alt="13" src="https://github.com/user-attachments/assets/75297d79-179d-49bc-af66-8c10fdbe499b" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="1712" height="372" alt="14" src="https://github.com/user-attachments/assets/4797a969-7a01-44cd-8d25-6db2e8e36fcb" />




# RESULT:
The commands/batch files are executed successfully.

