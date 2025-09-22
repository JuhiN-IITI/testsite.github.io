layout: page
title: "Using Wacom Tablets With Virtualized Environments"
permalink: /Drivers__SoftwareWacom_Driver_Download_needed_Receiving_a_driver_error_message_o/Wacom_Driver_TroubleshootingRead_More/Next/Using_Wacom_Tablets_With_Virtualized_Environments

# Using Wacom Tablets With Virtualized Environments

Can Wacom tablets be used on virtual machines?


Yes. Any virtualized operating system that supports Wacom drivers will work with Wacom hardware. This includes both Windows and Linux, either on local networks or across the internet.
 
Will all Wacom hardware features work on virtual machines?


In general, hardware features will work on virtualized machines. There are some limitations on tablets using Linux. You can learn more about using Wacom tablets on Linux here.
 
What resolution will Wacom tablets run at on virtual machines?


Wacom currently supports up to 4k resolution over virtual machines, depending on the software and settings being used.
 
Will Wacom tablets work when multiple operating systems are being used in the virtualization processes?


Yes. For example, our hardware will still work if you use a host computer using Mac that needs to connect to a server and a virtual machine (also known as the guest) that uses Linux. Most combinations of server software and operating systems will work.


Please note that some configuration involving the hand-off of data may need to happen for this to work smoothly. If you have specific questions, you can review our documentation for developers here. You can also reach out to our Enterprise team. 
 
How does Wacom hardware connect to virtual machines? (USB Redirection)


Many solutions used to connect tablets to a virtual machine rely on a process known as USB redirection. When a tablet plugs into a USB port on a host computer, that port is assigned to the virtual machine (also known as the guest). This process will generally prevent the tablet from being used by applications on the host (local) as long as the guest is actively running.


If a tablet is not automatically connecting to a virtual machine, it may be an issue in the settings of your virtualization software, or you are using an outdated version of the software.


It is also possible that the virtual machine software you are using might use a process other than UBS redirection, such as a proprietary solution by the vendor. If you are having issues, it is always a good idea to check your vendor's specific approach.


This is clearly an important issue for the people who use Wacom tablets in virtualized environments. They need zero perceptible lag and resilient, highly reliable connections. Wacom is committed to improving stability and functionality for devices connected to virtual machines.
 
If I am a software vendor, can I work with Wacom to help solve virtualization issues?


Yes! Please reach out to our enterprise team here and provide as much detail as possible. 


 
What I need isn't here!


If you have any other questions about Wacom enterprise or using our products using virtualization, please reach out. We work with direct customers and virtual software providers to tackle issues and ease bottlenecks.

---
Source: [https://support.wacom.com/hc/en-us/articles/4418580738967-Using-Wacom-Tablets-With-Virtualized-Environments](https://support.wacom.com/hc/en-us/articles/4418580738967-Using-Wacom-Tablets-With-Virtualized-Environments)
