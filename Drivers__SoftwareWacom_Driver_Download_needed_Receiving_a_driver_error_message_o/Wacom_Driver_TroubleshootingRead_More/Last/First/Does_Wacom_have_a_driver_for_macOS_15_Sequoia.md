# Does Wacom have a driver for macOS 15 (Sequoia)?

The current driver supports macOS 15 (Sequoia). 


You can access Wacom Tablet Settings from the Settings icon in the Dock or by selecting the Apple menu, System Settings, and Wacom Tablet. Please continue to use Wacom Center to register your product, check for updates, and access your bundle Software offers.


Below are the steps to install the tablet driver on macOS 15.0.x and how to adjust the necessary security settings.
Step 1: Compatibility


To be compatible with macOS 15, the device must be supported by the 6.4.7-* driver or newer. To check which devices are compatible, visit the Wacom Driver Page, open the driver release notes, and select the "compatible products" link.


The message "The Wacom Tablet Driver can't be opened because it is from an unidentified developer" may appear when installing the driver. This means the computer's security settings are set only to allow downloads from the Apple app store. To install the Wacom Driver, the computer's installation security settings will also need to be adjusted. For more information on security and the steps to allow unidentified developer installs, visit Apple's support page here.
Step 2: Installing Driver

Download the current driver and run the installer.
During the install you will be prompted to add the required security settings. Make sure to add these settings, if you do not, the tablet and driver will not work correctly.
Next you must restart your computer for the driver to start working.
Once the driver has been installed, connect your device to the computer



Note: When prompted for permissions during the installation process, choose to allow.


Note: Adding permissions must be done within the first 30 minutes of installing the driver. If the driver was installed outside the time window, please uninstall and reinstall the driver.
System Prompts:

The system will prompt you to allow accessibility access, click the "Open System Settings."




Click the slider to allow com.wacom in accessibility.




Next, a prompt to allow "WacomTabletDriver: to receive keystrokes, will appear, click the "Open System Settings" box again.




Click the slider to allow WacomTabletDriver in Input Monitoring. You will be prompted to "Quit and Reopen" the settings; please do so.

Allow in the Background if prompted.







Finally, some Wacom devices, like the Wacom Cintiq Pro tablets may be prompted to allow the use of a "hub." Click allow to continue using your device.







 



     At this point your Wacom device should be operational.  If its not, then first try restarting you Mac,  after that please try following Step 3. 


 
Step 3: Login Items


The first thing that you would want to make sure of, is that the Wacom items are allowed in this section. If the aren't, your tablet won't be registered by your Mac. For this we want to make sure the driver is allowed to run in the background.


Please go to:     Open Settings > General > Login Items > Here listed under "Allow in the Background" you should have a "Wacom" option (mentioning 4 items), please make sure this is turned ON




With that turned On, please restart your computer as your tablet may no be recognized until the next Login takes place.

If you are still encountering issues after doing the above, please move to Step 4.



Step 4: Security & Privacy Permissions



Note: Adding permissions must be done within the first 30 minutes of installing the driver. If the driver was installed outside the time window, please uninstall and reinstall the driver by starting back from Step 2 before attempting to follow further steps.


 


If your pen or touch is not working correctly, at this point we want to make sure to check these settings manually to ensure that permissions are properly in place.


That said, at this stage you should at least be able to open the "Wacom Tablet" panel inside of your System Settings (on the bottom right side).  If instead you are getting an error message when trying to open the "Wacom Tablet" panel then we suggest to Contact our Wacom Support Team, but if on the other hand you are not getting an error message, but rather experiencing the cursor not moving or the pen not clicking for example, then following the next steps is likely to correct the issue. If so please continue with the next steps:



Go to the Apple menu, open System Settings, and select Privacy and Security.

Under Privacy, select Accessibility 

You will be asked to input your credentials. On the list shown, make sure any Wacom component listed has the slider turned on.

While you are here, ensure any known applications listed have a check as well. (For example, Photoshop will need to be selected to work correctly with the tablet, visit Adobe support guide for more information on adding this program, if it's missing.
If any Wacom component is listed here, and the pen or touch is still not working, "select" the Wacom items listed, and then click the "-" sign below the list to remove them. Next restart the computer and go to Step 5. 




Scroll down to "Input Monitoring" and add the slider for WacomTabletDriver.


Note: When you add an item in Input Monitoring a message will appear notifying you the application must quit before changes will work. Please do so, however, you must restart your computer after this as the tablet and driver will not work correctly until after the restart.



Step 5: If the issue continues or if no Wacom components are listed


If no Wacom components are listed, move the Security & Privacy preferences to the side, we will need to return here within a few steps.

Click on the desktop and press Command+Shift+G, open Finder, or click Go on the Menu Bar and select Go to Folder
Type: /Library/PrivilegedHelperTools/ then press GO
Locate the com.wacom.IOManager.app
Making sure you are still allowed to make changes (button is open), drag and drop the com.wacom.IOManger.app to the list under Accessibility in the Security & Privacy section. Ensure the new item is checked.

If this item will not check there may be an issue with your Mac OS and you need to contact Apple Support.


Close the preferences, restart your computer.
Next Scroll down to Files and Folders, Locate Wacom Center and turn on any checkmarks attached to Wacom Center.
Next under Automation also in the privacy tab in the Security & Privacy. Any Wacom components here should also have checkmarks. If the Wacom Desktop Center is not listed, it means it hasn’t requested control from the OS yet. To add the Wacom Center to Automation, follow the steps below.

Launch the Wacom Center
Select your device and go to any of the settings (such as pen settings)
A dialog will open, make sure to allow the app.
Close the preferences, restart your computer.
Go to the Privacy tab again, select Accessibility then click on the button at the bottom of the preferences to make changes.
Uncheck the com.Wacom.IOManager, then log out of the user.
Login into the user again, open Accessibility and check the add the driver setting again

To manually add the WacomTabletDriver into the Input Monitoring area:

Click on Plus Icon
 Go to Applications
Within Wacom, Tablet Folder, click on SHIFT COMMAND and Period. (This will enable the hidden folders, and the DOT Tablet folder will appear.)
Click on the Dot Tablet folder, select Wacom Tablet Driver, and click open.
You will be promptedto quit and restart.

---
Source: [https://support.wacom.com/hc/en-us/articles/25915509197335-Does-Wacom-have-a-driver-for-macOS-15-Sequoia](https://support.wacom.com/hc/en-us/articles/25915509197335-Does-Wacom-have-a-driver-for-macOS-15-Sequoia)
