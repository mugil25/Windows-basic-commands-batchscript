# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:
a
Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:
### NAME : MUGIL M.
### REG NO: 212223230127


Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
mkdir %userprofile%\Desktop\MyLab

![WhatsApp Image 2024-05-08 at 15 18 37_5a8c269b](https://github.com/mugil25/Windows-basic-commands-batchscript/assets/148515771/c0941dcb-b72c-460b-883c-550e874c1173)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
dir %userprofile%\Desktop\MyLab
![WhatsApp Image 2024-05-08 at 15 18 52_2747df75](https://github.com/mugil25/Windows-basic-commands-batchscript/assets/148515771/9dcaf660-097e-4602-8d7a-b9ac01cad310)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
mkdir %userprofile%\Desktop\Backup
mkdir %userprofile%\Desktop\Backup

![WhatsApp Image 2024-05-08 at 15 19 17_ee6c1b72](https://github.com/mugil25/Windows-basic-commands-batchscript/assets/148515771/a0dcbbcb-eba6-4a4d-b675-8909f88d139d)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.


@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!




## OUTPUT
![WhatsApp Image 2024-05-08 at 15 24 46_6e3d06b1](https://github.com/mugil25/Windows-basic-commands-batchscript/assets/148515771/52d21786-9ee4-4db0-8d01-496698c88bc0)

## RESULT:

The commands/batch files are executed successfully.






