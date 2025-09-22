layout: page
title: "Why does the Cintiq Companion Hybrid (DTH-A1300) and Cintiq 13HD (DTK-1300) display a reduced picture size when connected to a PC or Mac?"
permalink: /Hardware_SupportHaving_trouble_with_a_Wacom_device_See_answers_to_many_frequentl/Troubleshoot_Wacom_HardwareRead_More/Pen_Computer/Cintiq_Companion_Hybrid/Why_does_the_Cintiq_Companion_Hybrid_DTH-A1300_and_Cintiq_13HD_DTK-1300_display_

# Why does the Cintiq Companion Hybrid (DTH-A1300) and Cintiq 13HD (DTK-1300) display a reduced picture size when connected to a PC or Mac?

A function called "Underscan," usually a setting of the graphics driver, causes the small picture display. You can fix this by following the relevant operating system instructions below:


Windows

Standard PCs and laptops: 
  
Locate the "Overscan" or "Underscan" settings in the graphics driver, then set the value to "0."
 
MacBook Pro Bootcamp Windows: 
  
The Apple Bootcamp driver for Windows doesn’t have a specific setting to correct "Overscan" or "Underscan," thus you’ll need to change the setting manually: 
    
Paste the following key in the registry: HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Contro l\video{####....}\0000
Then create a new DWORD:"DigitalHDTVDefaultUnderscan" = dword 0x0000
Note: If here are several {####....} options, choose the one with most of the AMD settings.
 
 



OS X:

Simply change the "Overscan" setting in the OS X Display on the control panel.

---
Source: [https://support.wacom.com/hc/en-us/articles/1500006273161-Why-does-the-Cintiq-Companion-Hybrid-DTH-A1300-and-Cintiq-13HD-DTK-1300-display-a-reduced-picture-size-when-connected-to-a-PC-or-Mac](https://support.wacom.com/hc/en-us/articles/1500006273161-Why-does-the-Cintiq-Companion-Hybrid-DTH-A1300-and-Cintiq-13HD-DTK-1300-display-a-reduced-picture-size-when-connected-to-a-PC-or-Mac)
