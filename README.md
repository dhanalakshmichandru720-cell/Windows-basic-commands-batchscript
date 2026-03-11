# Ex08-Windows-basic-commands-batchscript

## Name : DHANALAKSHMI C
## REG NO: 212225230050

## AIM:
To execute Windows basic commands and batch scripting



## DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




## WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"
## COMMAND AND OUTPUT
```
mkdir my-folder
```
<img width="1010" height="136" alt="Screenshot 2026-03-11 082222" src="https://github.com/user-attachments/assets/9d7bda77-1bec-4df4-9f24-31175ca68695" />


Remove the directory "my-folder"
## COMMAND AND OUTPUT
```
rmdir my-folder
```
<img width="1076" height="107" alt="Screenshot 2026-03-11 082257" src="https://github.com/user-attachments/assets/dbb6223d-a581-439c-bc2c-bdbee71050f1" />


Create the file Rose.txt
## COMMAND AND OUTPUT
```
COPY CON Rose.txt
dir Rose.txt
```
<img width="1020" height="172" alt="Screenshot 2026-03-11 082645" src="https://github.com/user-attachments/assets/3b8d08d3-9a6c-4809-a57d-a30c79b3de86" />
<img width="1046" height="280" alt="Screenshot 2026-03-11 082709" src="https://github.com/user-attachments/assets/5f944368-cf78-423e-8340-62ed98595c15" />



Create the file hello.txt using echo and redirection
## COMMAND AND OUTPUT
```
echo “hello world” > hello.txt
type hello.txt
```
<img width="1046" height="164" alt="Screenshot 2026-03-11 082809" src="https://github.com/user-attachments/assets/2a8e9a33-8d64-433c-a13c-7101cdb88fc8" />



Copy the file hello.txt into the file hello1.txt
## COMMAND AND OUTPUT
```
copy hello.txt hello1.txt
```
<img width="850" height="287" alt="image" src="https://github.com/user-attachments/assets/67092ece-13f2-4a5e-af14-86314fcf3466" />


Remove the file hello1.txt
## COMMAND AND OUTPUT
```
del hello1.txt
```
<img width="673" height="194" alt="image" src="https://github.com/user-attachments/assets/d9c83680-9b3b-480a-adbd-7840d155818b" />



List out the file hello1.txt in the current directory
## COMMAND AND OUTPUT
```
dir hello1.txt
```
<img width="673" height="194" alt="image" src="https://github.com/user-attachments/assets/db2b7f13-f107-4031-b777-6cd5c469989d" />


List out all the associated file extensions 
## COMMAND AND OUTPUT
```
assoc | more
```
<img width="769" height="451" alt="image" src="https://github.com/user-attachments/assets/370afdb3-c55f-403c-961e-466f15368839" />



Compare the file hello.txt and rose.txt
## COMMAND AND OUTPUT
```
fc hello.txt Rose.txt
```
<img width="742" height="198" alt="image" src="https://github.com/user-attachments/assets/6fd1bbc4-ca75-4602-b03d-72f29d45fe29" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
<img width="781" height="469" alt="image" src="https://github.com/user-attachments/assets/e43561a0-9511-49ec-89a0-cfdeed5ef71a" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="712" height="217" alt="image" src="https://github.com/user-attachments/assets/f63b295a-8244-4df2-a119-b6343a303dfb" />

s each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="847" height="193" alt="image" src="https://github.com/user-attachments/assets/82bc0309-d746-4205-a8e7-4c396fd19d19" />


Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="729" height="225" alt="image" src="https://github.com/user-attachments/assets/57d5156f-e3a0-4369-8996-1aab3f37a88b" />



Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="744" height="406" alt="image" src="https://github.com/user-attachments/assets/54dce2cf-8339-417d-a5a1-59aa0f7bef33" />



# RESULT:
The commands/batch files are executed successfully.

