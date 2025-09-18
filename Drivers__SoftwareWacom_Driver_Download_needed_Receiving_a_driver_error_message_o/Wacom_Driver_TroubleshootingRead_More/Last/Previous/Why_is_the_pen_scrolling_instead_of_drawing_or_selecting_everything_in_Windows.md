# Why is the pen scrolling instead of drawing or selecting everything in Windows?

Microsoft Windows updates (KB4093112 & KB4089848) have made large changes in the settings for Windows Ink. These changes affect all Pen and Touch devices, not just Wacom Tablets. Users have reported issues with these updates causing their pen not to act as expected in the application they are using. Some examples include, scrolling instead of drawing in Photoshop and not releasing a selection with the pen in Outlook or a web browser like Firefox and Chrome.


This issue has been fixed with the release of the Windows 10 April Update. To download and install this update, go to Settings > Update & Security > Windows Update and select Check online for updates from Microsoft Update.


 


Previous Solution Below:



Alternate Solution available on Wacom EU forum: http://forum.wacom.eu/viewtopic.php?f=5&t=1600  


Note: Current versions of Adobe Photoshop uses Windows Ink for Pen Pressure.
 Current versions of Adobe Photoshop by default needs Windows Ink turned on for Pen Pressure to work correctly. However, Adobe offers steps to manually change this settings to allow for customers to revert back to not using Windows Ink, please see here, just be sure to refer to the other tablets section if you have turned off Windows Ink in the Wacom Tablet Properties: https://helpx.adobe.com/photoshop/kb/tablet-support-faq-photoshop.html


To disable Windows Ink in the Wacom Tablet Properties

Open the Wacom Tablet Properties inside the Wacom Tablet folder in your Windows Start Menu





Select the Pen in the tool section





Select the Mapping tab under this tool.





Uncheck the check box for Windows Ink. This will turn Windows Ink off for the application selected in the Application section. In the example above All other is selected, this change will affect all applications other than Chrome, which will have its own settings. (To make application specific settings, see the steps below.)






We suggest only to make this change for the application experiencing the issue in.


To make application specific settings by adding the application being used to the application list by clicking on the “+” icon on the row for Application.




Once open, the list of all open applications will be listed for easy selection. If the application is not open, use the browse button to look for the desired application in the Windows program files folder.





Select the application desired, in this example Outlook, and click “OK.” Outlook will now be listed in the Application window.





Click on the application added to select it from the application pane, then select the Pen from the tool pane and click on mapping tab. Uncheck Windows Ink to turn off Windows Ink for this application only.

---
Source: [https://support.wacom.com/hc/en-us/articles/1500006344062-Why-is-the-pen-scrolling-instead-of-drawing-or-selecting-everything-in-Windows](https://support.wacom.com/hc/en-us/articles/1500006344062-Why-is-the-pen-scrolling-instead-of-drawing-or-selecting-everything-in-Windows)
