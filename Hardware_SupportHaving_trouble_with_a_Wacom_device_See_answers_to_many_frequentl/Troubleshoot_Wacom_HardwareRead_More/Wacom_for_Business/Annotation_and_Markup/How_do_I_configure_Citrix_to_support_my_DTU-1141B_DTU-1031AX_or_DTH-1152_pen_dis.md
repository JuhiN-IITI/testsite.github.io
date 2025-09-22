layout: page
title: "How do I configure Citrix to support my DTU-1141B, DTU-1031AX or DTH-1152 pen display?"
permalink: /Hardware_SupportHaving_trouble_with_a_Wacom_device_See_answers_to_many_frequentl/Troubleshoot_Wacom_HardwareRead_More/Wacom_for_Business/Annotation_and_Markup/How_do_I_configure_Citrix_to_support_my_DTU-1141B_DTU-1031AX_or_DTH-1152_pen_dis

# How do I configure Citrix to support my DTU-1141B, DTU-1031AX or DTH-1152 pen display?

The exact configuration set up with vary slightly depending on which version of Citrix you are using.


For Citrix Versions 7.6.3 and later, the following steps must be completed:

The security setting in Citrix Studio must be set to allow USB redirection. You can find more information on USB redirection here: https://support.citrix.com/article/CTX203592
The Wacom pen driver (ver 6.3.23-1 or later) needs to be installed on the delivered OS
On the client, the registry needs to be edited and the Wacom VID and the product PID added:



 






Device




Vendor ID




Product ID






STU-430 




056a




00a4






STU-540 




056a




00a8






DTU-1031AX




056a




039F






DTU-1141B




056a




0359






DTH-1152




056a




Pen: 035A


Touch: 0368






 

Also on the client side:

The Wacom pen driver needs to be installed (the same version as the driver installed on the delivered OS)
The video display driver needs to be installed.

DTU-1031AX – Use the MCT video Driver, available here. Enter product model DTU-1031AX in search query and hit enter. Then, at the bottom of the page, the MCT Driver download will be available under the “Other Resources” header
DTU-1141B – The DTU-1141B utilizes a DisplayLink video driver. DisplayLink drivers are included in all recent versions of Windows 10, but if you are using an older version of Windows, you can download the required drivers here. Enter product model DTU-1141B in search query and hit enter. Then, at the bottom of the page, the Display Link driver download will be available under the “Other Resources” header







 


For Citrix version 6.5 – 7.5:

The security setting in Citrix Studio must be set to allow COM port redirection
The Wacom pen driver (ver 6.3.23-1 or later) needs to be installed to the delivered OS
On the client, the Wacom pen driver needs to be installed (the same version as the driver on the delivered OS)
The tablet mode needs to be changed from USB to VCP



 


To increase performance in Citrix:


Citrix recommends increasing the number of cores allocated to the VM. Our testing shows that dedicating three or more cores will eliminate lag.


The following link also provides several configuration changes that can be made to improve performance: USB device policy settings

---
Source: [https://support.wacom.com/hc/en-us/articles/5097830467479-How-do-I-configure-Citrix-to-support-my-DTU-1141B-DTU-1031AX-or-DTH-1152-pen-display](https://support.wacom.com/hc/en-us/articles/5097830467479-How-do-I-configure-Citrix-to-support-my-DTU-1141B-DTU-1031AX-or-DTH-1152-pen-display)
