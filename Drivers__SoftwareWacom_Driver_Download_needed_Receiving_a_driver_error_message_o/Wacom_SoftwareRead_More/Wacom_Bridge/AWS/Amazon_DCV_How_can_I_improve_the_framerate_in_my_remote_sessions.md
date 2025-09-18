# Amazon DCV: How can I improve the framerate in my remote sessions?

The framerate of the Server greatly impacts the creative experience on Wacom Bridge. To adjust the framerate from the default (25 fps), an administrator needs to adjust the registry on the Server.


a. Open Registry Editor to: “ Computer\HKEY_USERS\S-1-5-18\Software\GSettings\com\nicesoftware\dcv\display ”


b. Add a DWORD 32bit value named “target-fps” and set its value to 0 (decimal).


c. If “target-fps” already exists, change its value to “0.” This sets the framerate to the highest possible for the Server GPU.


d. Restart Server.


e. Reconnect.

---
Source: [https://support.wacom.com/hc/en-us/articles/28273736059287-Amazon-DCV-How-can-I-improve-the-framerate-in-my-remote-sessions](https://support.wacom.com/hc/en-us/articles/28273736059287-Amazon-DCV-How-can-I-improve-the-framerate-in-my-remote-sessions)
