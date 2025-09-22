layout: page
title: "How do I uninstall (manually) and re-install the Wacom driver on macOS for a Pen Tablet, Pen Display, or Pen Computer?"
permalink: /Drivers__SoftwareWacom_Driver_Download_needed_Receiving_a_driver_error_message_o/Wacom_Driver_TroubleshootingRead_More/Last/How_do_I_uninstall_manually_and_re-install_the_Wacom_driver_on_macOS_for_a_Pen_T

# How do I uninstall (manually) and re-install the Wacom driver on macOS for a Pen Tablet, Pen Display, or Pen Computer?

NOTE:

This process will remove any Wacom preferences you may have configured. Please ensure you have backed up your preferences before proceeding.
A restart will be required after installing the driver, please ensure you have closed and saved all your work before following these instructions.
Make sure you know the username and password of an administrative user account of your computer.



Steps to be followed:

Disconnect the tablet from the computer.

Disconnect the USB cable.
If you are using a Wireless Kit, remove the USB dongle from your computer.
If your tablet is connected via Bluetooth, ensure that the tablet and the Bluetooth on your computer are turned OFF.
Try clearing preferences before going to the next step.


In the Finder, open the Applications => Wacom Tablet folder. 
Open the Wacom Tablet Utility. 
Under "Tablet Software", click Uninstall. macOS may ask you for an administrative user account credentials to complete this by clicking the unlock icon at the lower left of the menu. 
Once the software has been removed, restart the computer.
After removing the driver with the Wacom Tablet Utility, manually search for files and folders which may not have been properly removed.
While you’re on the desktop click on Go at the top, then on Computer. 
In the Finder window that opens, open your primary drive partition (by default this is named Macintosh HD).
Please check for Wacom related files and folders in the following locations on Macintosh HD and move them to the Trash:

Macintosh HD (or you Hard drive name)/Applications/Wacom Tablet 
Open the folder >Macintosh HD/Library/Application Support, and delete the following folder: /Tablet 
Open the folder >Macintosh HD/Library/Frameworks, and delete the following file: /WacomMultiTouch.framework
Open the folder >Macintosh HD/Library/Internet Plugins, and delete the following file: /WacomTabletPlugin.plugin
Open the folder >Macintosh HD/Library/Launch Agents, and delete the following files:

/com.wacom.wacomtablet.plist
/com.wacom.drivers.plist
/com.wacom.UpdateHelper.plist


Open the folder >Macintosh HD/Library/Extensions and delete the following file:Wacom Tablet.kext   
Open the folder >Macintosh HD/Library/LaunchDaemons, and delete the following files:     

/com.wacom.displayhelper.plist
/com.wacom.RemoveTabletHelper.plist
/com.wacom.TabletHelper.plist 


Open the folder >Macintosh HD/Library/PrivilegedHelperTools, and delete the following files:  ​​​​​​

/com.wacom.DataStoreMgr
/com.wacom.DisplayMgr
/com.wacom.UpdateHelper          









Open the folder >Macintosh HD/Library/PreferencePanes, and delete the following file: /WacomTablet.prefpane
Open the folder >Macintosh HD/Library/Preferences, and delete the following folder: /Tablet



Next, check for the following files in the Users folder. 

On OS X 10.7 Lion or later, the User Library folder has been hidden. To access the User Library, you need to click Go in the Finder as above, and hold down the Option(⌥ / 'Alt') key. You can now select 'Library'. 
Open the folder >Macintosh HD/User/<user>/Library/Caches, and delete the following files:  ​​​​​​

/com.wacom.RemoveWacomTablet
/com.wacom.Wacom-Desktop-Center
/com.wacom.Wacom-Display-Settings
/com.wacom.wacomtablet
/com.wacom.WacomTouchDriver


Open the folder >Macintosh HD/User/<user>/Library/Preferences, and delete the following files:  ​​​​​​

/com.wacom.Tablet-Mapping.plist
/com.wacom.wacomtablet.plist


If you ever had a Wacom Bamboo tablet installed on this computer, check your Applications folder for a folder named "Wacom", "Wacom Utility" or "Bamboo". This folder will contain the Wacom Utility application. Open this application and proceed from step 3 above. Check your Applications folder for any remaining files or folders named "Wacom" or "Bamboo" and move them to the Trash. Ensure you also remove the Bamboo Dock application as it is no longer supported and could cause problems.
Empty the Trash. After removing all these files and folders, there should not be any leftover Wacom driver files on your system.
Restart the computer.
Download and install the latest driver from:

http://www.wacom.com/drivers 
To ensure that the installation does not get blocked, please disconnect from the internet and disable the Mac OS firewall, and any additional security software you have installed.
Note for users of Legacy Products: 

Intuos 5, Intuos (2013 models), Cintiq 24HD, Cintiq Companion Hybrid, Cintiq Companion (DTH-W1300) The last driver compatible with your tablet is 6.3.46-2

https://cdn.wacom.com/u/productsupport/drivers/mac/professional/WacomTablet_6.3.46-2.dmg 



Intuos 4 The last driver compatible with your tablet is 6.3.41-2

https://cdn.wacom.com/u/productsupport/drivers/mac/professional/WacomTablet_6.3.41-2.dmg


Cintiq 21UX 2nd generation (DTK-2100) the last driver compatible with your tablet is 6.3.40-2

https://cdn.wacom.com/u/productsupport/drivers/mac/professional/WacomTablet_6.3.40-2.dmg


Intuos 3 or a 1st generation Cintiq 21UX (DTZ-2100) the latest driver compatible with your tablet is 6.3.15-3

http://cdn.wacom.com/u/productsupport/drivers/mac/professional/WacomTablet_6.3.15-3.dmg 








Open the downloaded DMG file, run the installer and follow the steps in the installation wizard.
Once the installation is complete, restart the system. Reconnect the tablet after you have logged back in. 

Note: Make sure your tablet is connected directly to your computer. Avoid using USB hubs, keyboard/monitor ports or docking stations, as they can cause inconsistent behavior.


Follow the Mac install Guide for additional permissions setup: Setting up the Wacom driver with macOS
Test your tablet by opening Wacom Desktop Center => Pen Settings or Apple => System Preferences => Wacom Tablet
Test all pen and button functionality before restoring any preferences that you may have backed up.
If your previously saved preferences are not working properly after you restore them, or you start to notice any malfunction, we recommend you reset the preferences again. If everything then works as expected your old preferences file might be corrupt, so you will need to re-create them manually or from an older backup.

---
Source: [https://support.wacom.com/hc/en-us/articles/1500006264541-How-do-I-uninstall-manually-and-re-install-the-Wacom-driver-on-macOS-for-a-Pen-Tablet-Pen-Display-or-Pen-Computer](https://support.wacom.com/hc/en-us/articles/1500006264541-How-do-I-uninstall-manually-and-re-install-the-Wacom-driver-on-macOS-for-a-Pen-Tablet-Pen-Display-or-Pen-Computer)
