# windows-1.20
this is my own windows version i made. runs in powershell. tutorial in README. and its open source to. you just double click the file and therse the code!
Thank you for trying out the first version of this PowerShell-based operating system.

▶️ Step 1: How to Run the OS
Once you have the script file on your computer, running it is simple:
Navigate to the folder where you saved win120.ps1.
Right-click on the script file.
Select Run with PowerShell.

🛠️ Step 2: Troubleshooting Red Text/Crashes
If you are seeing a red text error or the terminal window closes immediately when you try to launch the OS, Windows is blocking the script for security reasons. Follow these steps to fix that:
A. Unblock the File (The Quick Fix)
Windows automatically blocks files downloaded from the internet. You need to manually "trust" the file.
Right-click on your script file again.
Select Properties.
In the General tab, look at the bottom for a Security section.
Check the box that says Unblock.
Click Apply or OK.
Try running the OS again now. If it works, you are done!

B. Change the Execution Policy (If "Unblock" Fails)
If the script still shows red text, your computer's security settings are set very strictly. You can adjust this setting just for your user account.
Search for "PowerShell" in your Start Menu.
Right-click on Windows PowerShell and select Run as Administrator.
In the blue Administrator window, copy and paste this exact command and press Enter:
powershell
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser


The terminal will ask "Do you want to change the execution policy?". Type Y (for Yes) and press Enter again.
Close and reopen PowerShell, then follow the instructions in Step 1 to run the OS.
