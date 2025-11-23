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
mkdir my-folder

<img width="362" height="180" alt="image" src="https://github.com/user-attachments/assets/b5125c4d-a2c6-43fa-9e68-628f898745dc" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT
rmdir my-folder

<img width="425" height="140" alt="image" src="https://github.com/user-attachments/assets/fe35c58c-dfca-4caf-94c9-9b39c5f55e3d" />


Create the file Rose.txt

## COMMAND AND OUTPUT
COPY CON Rose.txt
dir Rose.txt

<img width="431" height="264" alt="image" src="https://github.com/user-attachments/assets/df5a647b-af13-40c7-b527-2acace878d6a" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
echo “hello world” > hello.txt
type hello.txt

<img width="531" height="93" alt="image" src="https://github.com/user-attachments/assets/e8e4ed14-0411-4860-820e-a51d5a95aeb1" />


Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
copy hello.txt hello1.txt

<img width="508" height="88" alt="image" src="https://github.com/user-attachments/assets/bf760ae4-fc7c-41cc-84dd-058a1a10efe3" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
del hello1.txt

<img width="514" height="121" alt="image" src="https://github.com/user-attachments/assets/5aa2e80e-6b69-4e41-9d25-f50f4f6a7f2a" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
dir hello1.txt

<img width="419" height="61" alt="image" src="https://github.com/user-attachments/assets/f2d7f05d-cc6a-4968-bdfd-d59f2abf85e6" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
assoc | more

<img width="413" height="360" alt="image" src="https://github.com/user-attachments/assets/9749d549-a3fa-47ca-bc9b-a6f2379f3979" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
fc hello.txt Rose.txt

<img width="459" height="119" alt="image" src="https://github.com/user-attachments/assets/8b706a72-484d-44ea-a1d9-13184d765904" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".


## OUTPUT

<img width="298" height="79" alt="image" src="https://github.com/user-attachments/assets/cfaef732-ba28-4d37-9482-9f0bd504fe1a" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.


## OUTPUT

<img width="380" height="132" alt="image" src="https://github.com/user-attachments/assets/fd4c0146-5962-472e-927b-c68a9d057b6f" />

Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.

## OUTPUT

<img width="265" height="117" alt="image" src="https://github.com/user-attachments/assets/a5c0af5e-ad45-4ea3-910e-4c4c34697da3" />


Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="418" height="129" alt="image" src="https://github.com/user-attachments/assets/c6a1e642-88ca-4e57-90b1-dc1abc2b856a" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="348" height="247" alt="image" src="https://github.com/user-attachments/assets/db83a55e-61f0-448f-b860-6a7b4f0d95f4" />


# RESULT:
The commands/batch files are executed successfully.

