# Why is pressure not working in Adobe Illustrator on macOS?

There may be a few reasons why pressure is not working in Adobe Illustrator, from the brush not being setup to use pressure to macOS security settings. Please follow the steps below:
Security Settings:


First, macOS requires extra security settings for Adobe Illustrator and the Wacom Driver to use pen pressure if you are using macOS 10.13 or newer. (If you are using Adobe Illustrator 2021 see the note below)

Wacom Driver: First, make sure all the Wacom driver security settings are selected by following our guide article here. 
Adobe Illustrator: Next the security settings for Adobe Illustrator must be setup. Make sure Illustrator is not open while following these steps.

Open “System Preferences” >Security & Privacy > Privacy > Automation.
Make under Adobe Illustrator that "Tablet Driver" is selected.









Note: There is an issue with Adobe Illustrator 2021 that does not allow you to make the above selection in the system preferences. To resolve this issue you will need to uninstall the Wacom Driver and Adobe Illustrator, then reinstall the Wacom driver (following the steps from step 1) and then install the older 2020 version of Illustrator. If this version does not appear on the Creative Cloud application list, please reach out to Adobe Support.


 
Brush Settings:


In Illustrator the brush you are using must be set up to use pressure, some brushes do not have this turned on by default. The working space will need to be set to “Painting” to easily find the pen settings to check or change this setting.

Click on the top right icon and change the interface by "Painting" as seen on the screenshot below.




Now that the workspace is in Painting mode, all the brush settings are shown. Select the brush you wish to use.

You can also create a new calligraphic brush by clicking the "+" button. If you do, skip to step 4.


Once a brush is selected select the menu button at the top right side of the brush window and select "brush option"




Once the brush options menu opens you can find the three data points: Angle; Roundness and Size. By default, all three are set to "Fixed" as value which means there is no variation. To use pen pressure, change the setting for “Size” to "Pressure.”




Next set the variation range. The more points attributed the more the pressure variation will be when drawing. We recommend at least a variation 5 point to start.
Select OK to save the changes and test the brush.

---
Source: [https://support.wacom.com/hc/en-us/articles/4412354516247-Why-is-pressure-not-working-in-Adobe-Illustrator-on-macOS](https://support.wacom.com/hc/en-us/articles/4412354516247-Why-is-pressure-not-working-in-Adobe-Illustrator-on-macOS)
