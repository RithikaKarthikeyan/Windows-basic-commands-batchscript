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
<img width="585" height="198" alt="Screenshot 2026-05-26 112738" src="https://github.com/user-attachments/assets/4d05cbbb-2023-4266-a89d-5a192883baed" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="585" height="198" alt="Screenshot 2026-05-26 112738" src="https://github.com/user-attachments/assets/1b2a4972-c0ac-4baa-9259-bb12676556db" />


Create the file file.txt

## COMMAND AND OUTPUT
<img width="627" height="141" alt="Screenshot 2026-05-26 112745" src="https://github.com/user-attachments/assets/9aa29ddd-ddc0-4313-a013-15215330c049" />
<img width="678" height="225" alt="Screenshot 2026-05-26 112752" src="https://github.com/user-attachments/assets/771792c9-7927-442a-b9cd-45391d6def79" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="651" height="112" alt="Screenshot 2026-05-26 112909" src="https://github.com/user-attachments/assets/5ed63685-0a88-45b3-91a1-87e9296508af" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="616" height="138" alt="Screenshot 2026-05-26 112916" src="https://github.com/user-attachments/assets/22198b6b-ed77-4553-ade5-6dede418684f" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="514" height="224" alt="Screenshot 2026-05-26 113245" src="https://github.com/user-attachments/assets/154789f4-afa4-477e-bfe1-0bdec3ef1e4b" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="514" height="224" alt="Screenshot 2026-05-26 113245" src="https://github.com/user-attachments/assets/da98266a-e0a9-40d8-b297-5f0bf935800e" />

List out all the associated file extensions 

## COMMAND AND OUTPUT

<img width="565" height="756" alt="Screenshot 2026-05-26 113302" src="https://github.com/user-attachments/assets/6366577d-6492-4945-a177-8d78bc2211a3" />

Compare the file hello.txt and file.txt

## COMMAND AND OUTPUT
<img width="574" height="278" alt="Screenshot 2026-05-26 113311" src="https://github.com/user-attachments/assets/5dd74b62-835e-45c2-b4fb-f5139403fc47" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="553" height="101" alt="Screenshot 2026-05-26 113548" src="https://github.com/user-attachments/assets/60fd948f-afc0-47cd-b9f5-26ba1294c937" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="682" height="286" alt="Screenshot 2026-05-26 113733" src="https://github.com/user-attachments/assets/40e51486-a17f-4b45-a81f-16e164f4c4d9" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.



## OUTPUT
<img width="583" height="176" alt="Screenshot 2026-05-26 113945" src="https://github.com/user-attachments/assets/ec473bd0-f548-44cf-b8ee-9543fe548e3c" />




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="784" height="212" alt="Screenshot 2026-05-26 113954" src="https://github.com/user-attachments/assets/cace4b75-bdb8-4849-adfe-2ec0a3e878e5" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="523" height="421" alt="Screenshot 2026-05-26 114058" src="https://github.com/user-attachments/assets/05920c97-78cb-4b95-aacd-cb634c03caf5" />


# RESULT:
The commands/batch files are executed successfully.

