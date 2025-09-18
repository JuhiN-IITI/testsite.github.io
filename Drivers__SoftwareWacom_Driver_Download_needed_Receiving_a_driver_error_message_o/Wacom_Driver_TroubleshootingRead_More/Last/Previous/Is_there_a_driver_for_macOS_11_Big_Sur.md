# Is there a driver for macOS 11, Big Sur?

Yes, the current driver supports macOS 11 Big Sur.


This OS has added many security features to keep the computer safe from applications not downloaded directly from the App store. If an app is downloaded from the internet or directly from a developer, i.e. the Wacom Driver, the OS continues to protect the Mac. These added protections require additional security settings to be adjusted. The settings will need to be adjusted to allow the app access to certain parts of the OS. Until these settings are accepted, the tablet functions such as the Pen and touch input may not work correctly.


Below are the steps to install the driver for a tablet on macOS 11.0.x and how to adjust the security settings needed.
Step 1: Compatibility


To be compatible with macOS 11.0 Big Sur, the device must be supported by the 6.3.40-* driver or newer. To check which devices are compatible, visit the Wacom Driver Page, open the driver release notes and select the "compatible products" link.


When installing the driver, the message "The Wacom Tablet Driver can't be opened because it is from an unidentified developer" may appear. This means the security settings for the computer are set only to allow downloads from the Apple app store. To install the Wacom Driver, the installation security settings on the computer will also need to be adjusted. For more information on security and the steps to allow unidentified developer installs visit Apple's support page here.
Step 2: Installing Driver

Download the current driver and run the installer.
During the install you will be prompted to add the required security settings. Make sure to add these settings, if you do not, the tablet and driver will not work correctly.
Next you must restart your computer for the driver to start working.
Once the driver has been installed, connect your device to the computer



Note: When prompted for permissions during the installation process, choose to allow.


Note: Adding permissions must be done within the first 30 minutes of installing the driver. If the driver was installed outside of the time window, please uninstall and reinstall the driver.


A tutorial walkthrough of the Driver installation process can also be found here.



Install Process Prior to Driver 6.3.42.
Step 2: Installing Driver

Download the current driver and run the installer.
During the install you will be prompted to add the required security settings. Make sure to add these settings, if you do not, the tablet and driver will not work correctly.
Next you must restart your computer for the driver to start working.
Once the driver has been installed, connect your device to the computer

Step 3: Security & Privacy Permissions


Follow these steps if you were not prompted for permissions, or if your pen or touch is not working correctly. If the pen or touch is not working after install, check these settings even if you were prompted to allow the permissions.

Go to the Apple menu, open System Preferences, and select Security & Privacy.
Go to the Privacy tab, select Accessibility then click on the lock at the bottom of the preferences to make changes. You will be asked to input your credentials.
On the list shown, make sure any Wacom component listed has a checkmark.

While you are here, ensure any known applications listed have a check as well. (For example, Photoshop will need to be selected to work correctly with the tablet, visit Adobe support guide for more information on adding this program, if it's missing.
If any Wacom component is listed here, and the pen or touch is still not working, "select" the Wacom items listed, and then click the "-" sign below the list to remove them. Next restart the computer and go to Step 4. 




Scroll down to "Input Monitoring" and add a checkmark for WacomTabletDriver and Firmware Updater


Scroll down to Files and Folders, Locate Wacom Desktop Center and turn on any checkmarks attached to Wacom Desktop Center.
Note: When you add an item in Input Monitoring a message will appear notifying you the application must quit before changes will work. Please do so, however, you must restart your computer after this as the tablet and driver will not work correctly until after the restart.

Step 4: If the issue continues or if no Wacom components are listed


If no Wacom components are listed, move the Security & Privacy preferences to the side, we will need to return here within a few steps.

Click on the desktop and press Command+Shift+G, open Finder, or click Go on the Menu Bar and select Go to Folder
Type: /Library/ PrivilegedHelperTools/ then press GO
Locate the com.wacom.IOManager.app
Making sure you are still allowed to make changes (lock is open), drag and drop the com.wacom.IOManger.app to the list under Accessibility in the Security & Privacy section. Ensure the new item is checked.

If this item will not check there may be an issue with your Mac OS and you need to contact Apple Support.


Close the preferences, restart your computer.
Next Scroll down to Files and Folders, Locate Wacom Desktop Center and turn on any checkmarks attached to Wacom Desktop Center.
Next under Automation also in the privacy tab in the Security & Privacy. Any Wacom components here should also have checkmarks. If the Wacom Desktop Center is not listed, it means it hasn’t requested control from the OS yet. To add the Wacom Desktop Center to Automation, follow the steps below.

Launch the Wacom Desktop Center
Select your device and go to any of the settings (such as pen settings)
A dialog will open, make sure to allow the app.
Close the preferences, restart your computer.
Go to the Privacy tab again, select Accessibility then click on the lock at the bottom of the preferences to make changes.
Uncheck the com.Wacom.IOManager, then log out of the user.
Login into the user again, open Accessibility and check the add the driver setting again

---
Source: [https://support.wacom.com/hc/en-us/articles/1500006336422-Is-there-a-driver-for-macOS-11-Big-Sur](https://support.wacom.com/hc/en-us/articles/1500006336422-Is-there-a-driver-for-macOS-11-Big-Sur)
