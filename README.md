# RDS-Password
Local_WLAN_Borrower
Author:
YEETBOY0330 (Original concept and code)
ChatGPT (OpenAI) (Refined PowerShell script and adjustments)
Description:
This script allows you to extract Wi-Fi passwords from a Windows machine and save them to a .txt file on your USB device. It is designed to work with the USB Rubber Ducky and uses the included PowerShell script (1.ps1) to pull the stored Wi-Fi credentials from the system.

Setup:
1. Download and Prepare:
Download the 1.ps1 script and place it in the root of your USB drive.
In the inject.txt file (which is used by the USB Rubber Ducky), update the following:
Line 57: Change "DUCKY" to the label of your USB drive (the label of your USB drive can be seen in Windows under the "This PC" section).
Line 59: Change 1.ps1 to the name of the PowerShell script on your USB drive (ensure the script name matches exactly).
2. Modify PowerShell Script (1.ps1):
Open the 1.ps1 file.
On line 2, change "DUCKY" to the label of your USB drive (the label you identified earlier).
3. Deploy:
Place the modified inject.txt and 1.ps1 on the USB Rubber Ducky.
Once the Rubber Ducky is plugged into a Windows target system, it will execute the script, extract Wi-Fi passwords (if available), and save them to a .txt file on your USB drive.
Notes:
PowerShell Execution Policy: The Rubber Ducky script uses the -ExecutionPolicy Bypass flag to allow the PowerShell script to run without being blocked by security settings. Make sure the system allows running unsigned PowerShell scripts.
Windows Compatibility: This script is designed to work on Windows 10 and 11 systems.
Privacy Notice: Use this script responsibly and with permission. Unauthorized access to systems is illegal.
Credits:
YEETBOY0330 for the original concept and code.
ChatGPT (OpenAI) for refining the PowerShell script and improving compatibility.
