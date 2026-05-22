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

## COMMAND AND OUTPUT
<img width="1920" height="111" alt="1" src="https://github.com/user-attachments/assets/77f6223c-4b5c-4b50-81f0-ca0a41b3338d" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="1920" height="102" alt="2" src="https://github.com/user-attachments/assets/ac2d186c-2244-48dc-a2be-77ab7b69859a" />


Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="1920" height="105" alt="3" src="https://github.com/user-attachments/assets/01a0b2c5-620b-45e8-8eae-4cfdaef1fe8e" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="1920" height="113" alt="4" src="https://github.com/user-attachments/assets/e737bf45-c933-4e24-b758-5c805333d400" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="1920" height="131" alt="5" src="https://github.com/user-attachments/assets/f39b4443-29dc-4d1e-a197-404560640352" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="1920" height="105" alt="6" src="https://github.com/user-attachments/assets/57d63d98-62b0-4faf-aa94-149e6738397e" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="1920" height="250" alt="7" src="https://github.com/user-attachments/assets/17baeb12-8cd3-4680-bb8c-b4da115e79fc" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="1920" height="773" alt="8" src="https://github.com/user-attachments/assets/21535be8-13df-46d3-b08b-e1c709b87099" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="1920" height="210" alt="9" src="https://github.com/user-attachments/assets/440d5765-faca-46d0-acb9-5e78934acbf3" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="1482" height="75" alt="10" src="https://github.com/user-attachments/assets/d331c066-1660-4ec6-88dc-d8c88887e88f" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT


<img width="1482" height="212" alt="11" src="https://github.com/user-attachments/assets/bdfea7d5-dbde-4ad6-bb86-1abe81f843dd" />


Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
<img width="1482" height="168" alt="12" src="https://github.com/user-attachments/assets/347d4ce0-2dfb-4b21-891d-48e56c1c7f11" />




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="1482" height="66" alt="13" src="https://github.com/user-attachments/assets/6e3c7c49-3ce9-4cad-bb20-5306a15a75db" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="1483" height="204" alt="14" src="https://github.com/user-attachments/assets/b6d7ec22-d340-4d96-80c0-fa2defa56eb4" />


# RESULT:
The commands/batch files are executed successfully.

