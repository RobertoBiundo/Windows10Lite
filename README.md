# Windows10ProLite
A guide to create a Windows 10 Pro Install ISO with no bloatware

Last script version: Windows 10 Pro Fall 2017 Creators Update

This script is intended for Software Developers, Graphics Designers and Gamers that want the minimun Windows 10 functionality without all the bloatware provided by Microsoft. 

WARNING: Please read the list of removed software before you continue
WARNING: I'm not responsible for missing files, time, job, etc. Use this at your own risk

NOTE: This script only supports english language and US-International Keyboard

# Before you install keep in mind that
1. You will NOT receive Windows Updates at all after the instalation.
2. All special hardware most be installed manually (Ex. Video Card Drivers, Touch screens and a small part of touch devices)
3. There is no protections (No windows defender). You are on your own. Be responsible
4. There are no browsers. No Edge or Internet Explorer 11. Copy the install file for your browser of choice in a pendrive and run it form there.
5. NTLite is required


# How-To use
1. Go to Microsoft and download Windows 10 Install media creation tool
https://www.microsoft.com/en-us/software-download/windows10
2. Go to NTLite web page and download the latest version (version v1.5.0.5632 was used for testing)
https://www.ntlite.com/download/
3. Download the required script from this repo
4. Open the Windows 10 Install Media Creaation Tool
5. Select your Windows 10 - English - x64
6. Select ISO format (do not create a bootable disk)
7. Download make take a long time depending on your internet.
8. Open the downloaded ISO file by double clicking on it (using the default windows tools)
9. Copy all the contents of the file to a folder of your choice (a desktop folder is a good idea)
10. Copy the xml file downloaded in step 3 to the same folder
11. Open NTLite
12. Click on Add > Image Folder
13. Add the folder extracted in step 9
14. Right-Click on Windows 10 Pro and select load (this process takes a long time)
15. Right click on the file in the right side and select load (the one downloaded from this repo and recognized by NTLite)
16. Go to apply and the Process (an iso file will be generated in your desktop NTLite.iso)
17. Create a bootable USB using your favorite diskUtility. Rufus is recomended
https://rufus.akeo.ie/

# Test before you use
It is recomended that you use your favorite Virtual Machine to install the resulting ISO file.
This will help you identify the usefulness of this Windows install for your particular case before formating your computer.

# Known Issues
- If your tiles are not working (Pin to start not working) create a new user using PowerShell and Delete the original one. Try this as soon as you finish your install
- If your bluethooth is not working try Added your devices trough Control Panel and not Windows Settings

# Extras
Remove fodlers from Windows Explorer MyPC Using the script
Remove All User Folders From This PC 64-bit.reg

# Under development
A way to create a new Lite install disk for every mayor release that allows you to update your current installation.
