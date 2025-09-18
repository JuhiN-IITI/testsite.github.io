# How should I troubleshoot "Clean My Mac" issues that can disrupt Wacom components and services?

On a computer that has Clean My Mac installed, the Wacom Tablet app sometimes may fail to work when trying to open the Wacom Center or any other Wacom Driver Application such as the Wacom Display Settings or Wacom Tablet Utility. The application will hang, giving a rainbow "beach ball", causing the user to need to force quit the app. Another side effect may be in the apple System Preferences the Wacom Tablet Section will not load properly or will show a "pref pane" error.



In most of the cases the issue could is caused by "Optimization" apps, mainly CleanMyMac which it's an app that will perform changes on the Permissions of the MacOS File System and the Applications which will be started upon computer Boot-up. This applications may prevent the Wacom Tablet Driver components to load properly by changing the Application Launch Permissions or the ownership of the Application's files, in purpose of "speeding up" the MacOS Startup, but this don't allow the components to be started up after, since the permissions are never reverted back.



Most of the time, this situation can be reverted by setting up the Wacom Components as allowed in CleanMyMac as follows: 
Disconnect your tablet, then open CleanMyMac, under the "Optimization" section there is a list of apps, launching upon the OS starting to work. Some could be deactivated, so simply be sure to allow all of the components with the name "Wacom" on them (ex. WacomTabletDriver, WacomTouchDriver, WacomTabletSpringboard, com.wacom.IOManager...). Once you've allowed them, restart the computer and plug in your tablet, wait 30 seconds and test by opening the Wacom Tablet section on the computer's System Preferences.





 


If this doesn't work the File/Launch permissions might be changed beyond reversal and you might require to reinstall the driver as instructed here: How do I uninstall (manually) and re-install the Wacom driver on macOS for a Pen Tablet, Pen Display, or Pen Computer?

---
Source: [https://support.wacom.com/hc/en-us/articles/9255930218903-How-should-I-troubleshoot-Clean-My-Mac-issues-that-can-disrupt-Wacom-components-and-services](https://support.wacom.com/hc/en-us/articles/9255930218903-How-should-I-troubleshoot-Clean-My-Mac-issues-that-can-disrupt-Wacom-components-and-services)
