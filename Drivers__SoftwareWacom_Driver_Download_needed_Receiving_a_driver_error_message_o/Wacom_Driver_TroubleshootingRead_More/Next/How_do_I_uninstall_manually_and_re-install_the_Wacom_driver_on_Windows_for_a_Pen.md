layout: page
title: "How do I uninstall (manually) and re-install the Wacom driver on Windows for a Pen Tablet, Pen Display, or Pen Computer?"
permalink: /Drivers__SoftwareWacom_Driver_Download_needed_Receiving_a_driver_error_message_o/Wacom_Driver_TroubleshootingRead_More/Next/How_do_I_uninstall_manually_and_re-install_the_Wacom_driver_on_Windows_for_a_Pen

# How do I uninstall (manually) and re-install the Wacom driver on Windows for a Pen Tablet, Pen Display, or Pen Computer?

NOTE:

This process will remove any Wacom preferences you may have configured. Please ensure you have backed up your preferences before proceeding.
A restart will be required after installing the driver, please ensure you have closed and saved all your work before following these instructions.
Make sure you know the username and password of the administrative user account of your computer.



To reinstall the Wacom driver, follow the steps below: 
Note: Wacom Pen Computer owners will need to skip step 1. This applies to Companion 1/ 2 and MobileStudio Pro devices.

Disconnect the tablet from the computer

Disconnect the USB cable.
If you are using a Wireless Kit, remove the USB dongle from your computer.
If your tablet is connected via Bluetooth, ensure that the tablet and the Bluetooth on your computer are turned OFF..
Try clearing preferences before going to step 2. 


Open the Control Panel => Programs and Features.


​


Uninstall any Tablet, Wacom Tablet or Bamboo entries from this list. 




Restart the computer.
Manually search for files and folders which may not have been properly removed. If you find any files or folders delete them and empty the recycle bin after you finish.
To delete the files below you will need to unhide your system folders.
To unhide your system folders go to Control Panel => Folder Options (Windows 7 and 8) => File Explorer Options (Windows 10)

Go to the View tab and under Advanced Settings, click Show hidden files, folders and drives, click Apply once you're done and press OK.

Files to look for:

C:\Program Files\Tablet
C:\Users\<user>\AppData\Roaming\WTablet
C:\Users\<user>\AppData\Local\Temp\wactemp
C:\Users\<user>\AppData\Local\Wacom
The following files are in the folder C:\Windows\System32\
WacDriverDLCoinst.dll
Wacom_Tablet.dll
Wacom_Touch_Tablet.dll
WacomMT.dll
WacomTabletUserDefaults.xml
WacomTouchUserDefaults.xml
Wacom_Tablet.dat





If you have previously used a Wacom Bamboo tablet, please also check your programs folder for any file or folder named "Wacom" or "Bamboo" and remove these files or folders, repeating steps 2 & 3.
After you have followed these steps there should not be any leftover Wacom files on your system.
Once the software is completely removed restart the computer.
Once the computer has restarted, download and install the latest driver for your device from:

https://www.wacom.com/support/product-support/drivers

Note for users of Legacy Products: 



Please use the Wacom Driver Page to identify the correct driver for your Wacom Model.









To ensure that the installation does not get blocked, please disconnect from the internet and disable the Windows firewall, and any additional security software you have installed.
Run the downloaded installer and follow the steps.
Once the installation is complete and the system has performed the automatic restart after the driver installation, reconnect the tablet. 


Note: Make sure your tablet is connected directly to your computer. Avoid using USB hubs, keyboard/monitor ports or docking stations, as they can cause inconsistent behavior. This does not apply to Wacom Pen Computers.


Test your tablet

Open the Wacom Tablet properties: => Start => All Programs/All Apps => Wacom/ Wacom Tablet folder => Wacom Preferences/Wacom Tablet Properties. If you receive an error message, please take a screenshot.
Test all pen and button functionality before restoring any preferences that you may have backed up.


If your previously saved preferences are not working properly after you restore them, or you start to notice any malfunction, we recommend you reset the preferences again. If everything then works as expected your old preferences file might be corrupt, so you will need to re-create them manually or from an older backup.

---
Source: [https://support.wacom.com/hc/en-us/articles/1500011495022-How-do-I-uninstall-manually-and-re-install-the-Wacom-driver-on-Windows-for-a-Pen-Tablet-Pen-Display-or-Pen-Computer](https://support.wacom.com/hc/en-us/articles/1500011495022-How-do-I-uninstall-manually-and-re-install-the-Wacom-driver-on-Windows-for-a-Pen-Tablet-Pen-Display-or-Pen-Computer)
