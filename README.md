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
<img width="593" height="37" alt="image" src="https://github.com/user-attachments/assets/40fa549a-4241-4f1c-be9b-3e3acf94525c" />
Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="567" height="40" alt="image" src="https://github.com/user-attachments/assets/ad4cd315-2146-42d0-92f7-db19062a4c79" />


Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="695" height="502" alt="image" src="https://github.com/user-attachments/assets/b298a876-95f5-45dd-84d2-87fcd8ad3832" />
Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="596" height="107" alt="image" src="https://github.com/user-attachments/assets/8126d890-74d7-446b-8a51-88bdee0a9670" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="585" height="134" alt="image" src="https://github.com/user-attachments/assets/587d4c9b-76e2-45ab-a6fb-38d411494d5d" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="547" height="30" alt="image" src="https://github.com/user-attachments/assets/bd95398b-0c38-4d8e-bbdf-eb96d3e82150" />
List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="429" height="36" alt="image" src="https://github.com/user-attachments/assets/971b571e-a873-4e0e-97d0-c1228dac444b" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="584" height="777" alt="image" src="https://github.com/user-attachments/assets/0bcf478c-2903-4c06-9146-610872fc8a0f" />
Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="643" height="235" alt="image" src="https://github.com/user-attachments/assets/2f1ab9ee-590f-44f9-be60-3f2cb11a71a8" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".
## OUTPUT
<img width="474" height="106" alt="image" src="https://github.com/user-attachments/assets/ea9535d1-777a-484a-9fcb-235ce16adbaf" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.

## OUTPUT

<img width="725" height="343" alt="image" src="https://github.com/user-attachments/assets/b0dcfef0-afca-4ebf-98bb-d1ab745ba327" />

Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="492" height="215" alt="image" src="https://github.com/user-attachments/assets/201d6283-55df-4745-a42c-b179e683837c" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="533" height="160" alt="image" src="https://github.com/user-attachments/assets/705a46da-b8d5-46df-bd72-9b371572fd93" />

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="502" height="540" alt="image" src="https://github.com/user-attachments/assets/660a7431-243e-42fd-86cc-f9a160eb6186" />


# RESULT:
The commands/batch files are executed successfully.

