# How do I configure VMWare Horizon to support my DTU-1141B, DTU-1031AX or DTH-1152 pen display?

For VMWare Horizon you will need to:

Follow VMWare's standard instructions for USB redirection, for both the pen and touch portion of the tablet where applicable.



 


Wacom tablet pen and touch hardware uses Wacom’s Vendor ID (VID), 0x056a.  Product IDs (PIDs) can be found in Device Manger or below.






Device




Vendor ID




Product ID






DTU-1031AX




0x056a




0x039F






DTU-1141B




0x056a




0x0359






DTH-1152




0x056a




Pen: 0x035A


Touch: 0x0368






 

Install the latest version of the Wacom pen driver on the delivered OS. Get the latest driver here: https://www.wacom.com/en-us/support/product-support/drivers#latest.
On the client side:

Install the Wacom pen driver (the same version as the driver installed on the delivered OS).





Get the latest driver here: https://www.wacom.com/en-us/support/product-support/drivers#latest.


Type your display model into the search bar and begin your search to see the displayed page below:




Install the relevant 3rd party display driver on the local client based on your device.

DTU-1031AX – The MCT USB display driver will need to be installed on the local Client. Visit our driver page here. Enter product model DTU-1031AX in search query and hit enter. Then, at the bottom of the page, the MCT Driver download will be available under the “Other Resources” header
DTU-1141B – The DTU-1141B utilizes a DisplayLink video driver. DisplayLink drivers are included in all recent versions of Windows 10, but if you are using an older version of Windows, you can download the required drivers by visiting our driver page here. Enter product model DTU-1141B in search query and hit enter. Then, at the bottom of the page, the Display Link driver download will be available under the “Other Resources” header
DTH-1152 – No third-party display driver is needed.

---
Source: [https://support.wacom.com/hc/en-us/articles/5097838807959-How-do-I-configure-VMWare-Horizon-to-support-my-DTU-1141B-DTU-1031AX-or-DTH-1152-pen-display](https://support.wacom.com/hc/en-us/articles/5097838807959-How-do-I-configure-VMWare-Horizon-to-support-my-DTU-1141B-DTU-1031AX-or-DTH-1152-pen-display)
