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

<img width="831" height="443" alt="image" src="https://github.com/user-attachments/assets/a41f94d1-d1c5-493f-8048-f21ea999d51d" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT
rmdir my-folder

<img width="641" height="278" alt="image" src="https://github.com/user-attachments/assets/edb5dbe7-e1dd-4ebf-b74c-b633f98e020c" />

Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="838" height="495" alt="image" src="https://github.com/user-attachments/assets/1d5d91a7-b639-409b-a7f4-c993f5ba9e56" />

Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="800" height="141" alt="image" src="https://github.com/user-attachments/assets/cc72dc15-01c3-43f2-8e1e-d1adde1d15fb" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="918" height="167" alt="image" src="https://github.com/user-attachments/assets/33ce02f4-8d3f-4104-8d85-c68224ae1f1b" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="506" height="59" alt="image" src="https://github.com/user-attachments/assets/4ecf92e2-cb8a-4294-a4f2-fe61258ab88a" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="570" height="226" alt="image" src="https://github.com/user-attachments/assets/8d9451a3-7a0d-4c04-8b55-1c8dd8fb3a9d" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="792" height="928" alt="image" src="https://github.com/user-attachments/assets/9ccfae04-e855-4610-be6a-766c33c4ec74" />

Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="835" height="313" alt="image" src="https://github.com/user-attachments/assets/72a60f10-3171-460f-a902-b9de84bd87ab" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

## OUTPUT
<img width="318" height="382" alt="image" src="https://github.com/user-attachments/assets/613dc767-7041-4ea8-a849-7e8abaac71c7" />
<img width="663" height="118" alt="image" src="https://github.com/user-attachments/assets/661adeb0-c433-45bc-8606-97223416d157" />

Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.

## OUTPUT
<img width="814" height="703" alt="image" src="https://github.com/user-attachments/assets/7fa3416b-9ebb-49ae-ab8e-853a59ccbaba" />
<img width="764" height="298" alt="image" src="https://github.com/user-attachments/assets/16a3c1d1-a1cf-48f3-aee9-fcfeb4912821" />

Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.

## OUTPUT
<img width="502" height="452" alt="image" src="https://github.com/user-attachments/assets/6cea133f-14e4-4900-83b0-88f339223883" />
<img width="575" height="230" alt="image" src="https://github.com/user-attachments/assets/9521d6d3-f8fd-41f4-8b44-dc42909c48d2" />

Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="507" height="386" alt="image" src="https://github.com/user-attachments/assets/8532f812-f522-4e38-9b8b-b5ffe748ff41" />
<img width="565" height="123" alt="image" src="https://github.com/user-attachments/assets/698bc5d7-5033-4683-8f33-d511fc1cf987" />

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.

## OUTPUT
<img width="711" height="832" alt="image" src="https://github.com/user-attachments/assets/167f870f-7617-49f8-a033-93ee8ee8691d" />
<img width="655" height="552" alt="image" src="https://github.com/user-attachments/assets/16695240-7076-4999-9c9d-22e8bec1441e" />

# RESULT:
The commands/batch files are executed successfully.

