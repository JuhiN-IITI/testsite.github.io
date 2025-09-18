# How to enable a specified application to run with the NVIDIA graphics processor

Some Applications may show lower than expected graphics performance than expected when running Optimus graphics. Optimus graphics is a hybrid video solution that combines integrated Intel graphics and discrete NVIDIA graphics.  When running an application, the driver can determine which video processor to use but may not be able to do so in all instances.  If you want a particular application to run with the NVIDIA processor, it may be necessary to change settings or create a video profile for that application.  NOTE:  Please update the Iris Pro or Intel HD Graphics Drivers BEFORE proceeding with the steps below. 


There are different ways to force a program to run with the NVIDIA processor.
 These settings are controlled from the NVIDIA Control Panel which can be accessed from the Windows Control Panel or by right clicking on an empty area on the Windows desktop.  In the NVIDIA Control Panel, click on the “Manage 3D Settings” link on the left side of the window. 

You can create a profile for a particular application to run under NVIDIA. 


Follow the instructions below to change the default graphics processor:  
  
Open the NVIDIA Control Panel.
Click the Manage 3D Settings link.
Click the Programs Settings tab.
Check to see if your application is already listed in the “Select a program to customize:” drop down menu.
If listed, make the appropriate changes.
If not listed, create a new profile by clicking the “Add” button, then navigate to the program that you want to create a profile for.
Set the appropriate settings and then click OK when finished
 






2. You can set NVIDIA as the global default graphics processor and enable the context menu to allow one to manually choose which GPU to use.  By setting NVIDIA as the default, programs will use this graphics processor when they run.  If the context menu is enabled, regardless of which graphics processor is set to default, one can select which processor to use by right-clicking the program or shortcut and selecting the appropriate graphics processor.

Follow the instructions below to change the default graphics processor:  
  
Open the NVIDIA Control Panel. 
Click the Manage 3D Settings link. 
Click the Global Settings tab. 
In the Preferred graphics processor drop down menu, select “High-performance NVIDIA processor). 
 
Follow the instructions below to enable the Context menu: 
  
Open the NVIDIA Control Panel. 
Click the Desktop menu from the menu bar.
Select Add “run with graphics processor” to Context Menu.
To use, right click on the program or shortcut and select the graphics processor to use.
 



​​​​​​​

---
Source: [https://support.wacom.com/hc/en-us/articles/1500006265741-How-to-enable-a-specified-application-to-run-with-the-NVIDIA-graphics-processor](https://support.wacom.com/hc/en-us/articles/1500006265741-How-to-enable-a-specified-application-to-run-with-the-NVIDIA-graphics-processor)
