layout: page
title: "Is there a compatible driver for Mac OS 10.14 Mojave?"
permalink: /Drivers__SoftwareWacom_Driver_Download_needed_Receiving_a_driver_error_message_o/Wacom_Driver_TroubleshootingRead_More/Last/Previous/Is_there_a_compatible_driver_for_Mac_OS_1014_Mojave

# Is there a compatible driver for Mac OS 10.14 Mojave?

Yes, however the current Wacom driver no longer supports Mac OS 10.14.x . The last driver to support this legacy operating system was Driver 6.3.46-2. You can download the older driver by going to the Wacom driver page, and selecting "Older versions."


 


Mac OS 10.14.x added many security features to keep the computer safe from applications not downloaded directly from the App store. If an app is downloaded from the internet or directly from a developer, i.e. the Wacom Driver, the OS continues to protect the Mac. These added protections require additional security settings to be adjusted. The settings will need to be adjusted to allow the app access to certain parts of the OS. Until these settings are accepted, the tablet functions such as the Pen and touch input may not work correctly. 
Below are the steps to install the driver for a tablet on Mac OS 10.14 and how to adjust the security settings needed.


Step 1: Compatibility
To be compatible with MacOS 10.14 Mojave, the device must be supported by the 6.3.31-4 driver or newer. To check which devices are compatible, visit the Wacom Driver Page and select “compatible produces” link.
When installing the driver, the message “The Wacom Tablet Driver can’t be opened because it is from an unidentified developer.” This means the security settings for the computer are set only to allow downloads from the Apple app store. To install the Wacom Driver, the installation security settings on the computer will also need to be adjusted. For more information on security and the steps to allow unidentified developer installs visit Apple’s support page here.


Step 2: Installing
Download the current driver. Once the driver has been installed, connect your device to the computer.
Note: If prompted for permissions during the installation process, choose to allow.
Security & Privacy Permissions
Follow these steps if you were not prompted for permissions, or if your pen or touch is not working correctly. 
Note: If the pen or touch is not working after install, check these settings even if you were prompted to allow the permissions.

Go to the Apple menu, open System Preferences, and select Security & Privacy.
Go to the General tab, click the allow button located at the bottom for Wacom Technology Corp.
Go to the Privacy tab, select Accessibility then click on the lock at the bottom of the preferences to make changes. You will be asked to input your credentials.
On the list “allow the apps below to control your computer”, make sure any Wacom component listed has a checkmark. While you are here, ensure any known applications listed have a check as well. (For example, Photoshop will need to be selected to work correctly with the tablet, visit Adobe support guide for more information on adding this program if missing. 
If no Wacom components are listed, move the Security & Privacy preferences to the side, we will need to return here within a few steps.

Click on the desktop and press Command+Shift+G, open Finder, or click Go on the Menu Bar and select Go to Folder
Type: /Library/Application Support/Tablet/ then press GO.
Locate com.wacom.IOManger.app
Making sure you are still allowed to make changes (lock is open), drag and drop the item to the list under Accessibility in Security & Privacy. Ensure the new item is checked.
Close the preferences, restart your computer.


Next check under Automation also in the privacy tab in the Security & Privacy preferences. Any Wacom components here such as the Wacom Desktop Center or the WacomTabletDriver.app and WacomTouchDriver.app should have checkmarks. If a component is not listed, it means it hasn’t requested control yet.
To add the WacomTabletDriver.app and WacomTouchDriver.app:

Click on the desktop and press Command+Shift+G, open Finder, or click Go on the Menu Bar and select Go to Folder
Type: Applications/Wacom Tablet/.Tablet then press GO. You may need to force Finder to show hidden files by pressing CMD + Shift + ”.”
Drag and drop the WacomTabletDriver.app and WacomTouchDriver.app to the list under Automation in the Security & Privacy section. Ensure the new item is checked.


To add the Wacom Desktop Center to Automation, follow the steps below.

Launch the Wacom Desktop Center
Select your device and go to any of the settings (such as pen settings)
A dialog will open, make sure to allow the app.
Close the preferences, restart your computer.





Note when Upgrading OS: When upgrading 10.14 to a new service pack, i.e. 10.14.3 to 10.14.4 you may need to the force the system to accept the security settings again.

Go to the Privacy tab again, select Accessibility then click on the lock at the bottom of the preferences to make changes.
Uncheck the Wacom Touch Driver, then log out of the user.
Login into the user again, open Accessibility and check the add the driver settings again.



Note: Mac OS only allows the security settings to be changed within the first 30 minutes of installing the application. If the issue continues, please over install the driver with the current driver (even if you already have the current driver installed). Once installed, go to Apple Menu>System Preferences> Security and Privacy. If needed a prompt to allow the missing permissions should be shown. Click the lock icon at the lower left to allow changes to the settings, then select the allow button.

---
Source: [https://support.wacom.com/hc/en-us/articles/1500006266921-Is-there-a-compatible-driver-for-Mac-OS-10-14-Mojave](https://support.wacom.com/hc/en-us/articles/1500006266921-Is-there-a-compatible-driver-for-Mac-OS-10-14-Mojave)
