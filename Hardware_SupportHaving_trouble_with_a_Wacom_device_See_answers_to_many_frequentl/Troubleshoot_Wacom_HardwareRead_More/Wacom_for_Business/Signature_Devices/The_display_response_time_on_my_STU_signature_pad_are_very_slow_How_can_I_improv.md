# The display response time on my STU signature pad are very slow. How can I improve it?

The Wacom STU- 520, STU-530, STU-540 and STU-541 signature tablets have a high color display, which enables transfers of full screen color image data to the device. Since color images are much larger than the monochrome images used by other signature pad manufacturers, they may take considerably more time to transfer.


By installing a driver and using all of the available bandwidth of USB, you can significantly improve transfer performance. On Windows, applications can use WinUSB, a generic driver that’s pre-installed on Microsoft Windows. WinUSB consists of a kernel-mode driver (Winusb.sys), and a user-mode dynamic link library (Winusb.dll) that exposes WinUSB functions. These include the bulk transfer of data across USB, which greatly reduces transfer time.


You can access the driver on our download page.


Wacom Product Resources


For details of which of our signature pads require the STU driver please see here: https://developer-docs.wacom.com/display/DevDocs/STU+Driver

---
Source: [https://support.wacom.com/hc/en-us/articles/1500006268341-The-display-response-time-on-my-STU-signature-pad-are-very-slow-How-can-I-improve-it](https://support.wacom.com/hc/en-us/articles/1500006268341-The-display-response-time-on-my-STU-signature-pad-are-very-slow-How-can-I-improve-it)
