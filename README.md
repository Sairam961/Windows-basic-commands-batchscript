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
<img width="508" height="65" alt="image" src="https://github.com/user-attachments/assets/dd61db72-8c9b-4d40-b0b2-4629a25c18ef" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="507" height="65" alt="image" src="https://github.com/user-attachments/assets/83a69b5a-94b8-48e5-9cb4-5812ba0e2d2c" />

Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="773" height="483" alt="image" src="https://github.com/user-attachments/assets/010bb59b-7859-4f7e-8316-b50f0758d60d" />

Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="785" height="78" alt="image" src="https://github.com/user-attachments/assets/18117561-c323-4288-9af3-a97cd43ba912" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="648" height="83" alt="image" src="https://github.com/user-attachments/assets/780c610a-1c67-49df-91f6-13c8783687b5" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="530" height="74" alt="image" src="https://github.com/user-attachments/assets/de6f458c-c077-4197-a46e-401d82bdae15" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="620" height="235" alt="image" src="https://github.com/user-attachments/assets/ac7fc2fd-9d7a-448d-8a05-fd853ddcf5c0" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="847" height="894" alt="image" src="https://github.com/user-attachments/assets/202716b4-2a47-4660-8d02-f7b815d9385f" />

Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="695" height="288" alt="image" src="https://github.com/user-attachments/assets/37c22b61-ee2b-4796-8ed1-9755c8404779" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

## OUTPUT
<img width="338" height="320" alt="image" src="https://github.com/user-attachments/assets/4d1c3b08-f374-4735-a4e8-80c149325c1f" />
<img width="554" height="112" alt="image" src="https://github.com/user-attachments/assets/ee3e2a57-d68d-4272-8ba1-c2f4d801466d" />

Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.

## OUTPUT
<img width="732" height="641" alt="image" src="https://github.com/user-attachments/assets/b106f919-e54d-42f6-bd2c-61417f9c6204" />
<img width="767" height="268" alt="image" src="https://github.com/user-attachments/assets/e41eba31-2d4f-4ef2-83df-f1a018917102" />

Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.

## OUTPUT
<img width="368" height="294" alt="image" src="https://github.com/user-attachments/assets/3262d9e5-b599-458d-b53a-775b0c9964c2" />
<img width="625" height="226" alt="image" src="https://github.com/user-attachments/assets/78dce4e4-3d68-4e85-9854-cb4fd1b4a378" />

Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="444" height="357" alt="image" src="https://github.com/user-attachments/assets/e8ce0ba0-7cb3-4c83-a127-23abb914b5b1" />
<img width="503" height="120" alt="image" src="https://github.com/user-attachments/assets/6232868e-e8c4-4915-81fe-8612b520a17e" />

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.

## OUTPUT
<img width="498" height="697" alt="image" src="https://github.com/user-attachments/assets/8788e9e3-0865-4516-bac8-7d2d97dac945" />
<img width="726" height="524" alt="image" src="https://github.com/user-attachments/assets/8caee8ac-77e9-4c1d-af63-c49c02b9f0a2" />

# RESULT:
The commands/batch files are executed successfully.

