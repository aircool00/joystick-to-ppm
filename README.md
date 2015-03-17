This is a port of Flytron's Compufly to Java for cross platform use. There have also been enhancements made to the original to support multiple usb sources. The goal is to make a versatile computer based system to control RC Land, Sea, Aircraft and other projects. Using the software with Flytron's USB2PPM hardware solution to get PPM to a RC transmitter. Everything is kind of setup for my CH Products set up with joystick throttle and rudder at the moment. The Current version is set up for Windows with a batch file to launch. we are working on getting that into a universal .jar


To get started


Run start.bat for x86

Run startx64.bat for x64


Requirements:


Compufly USB2PPM: http://flytron.com/programmers/56-compufly-usbtoppm-converter.html

Windows XP/Vista/7 USB drivers : http://www.flytron.com/pdf/CP210x_VCP_Win_XP_S2K3_Vista_7.zip

Works with v1 and v2

DirectX Joystick Driver Information for Windows Vista and Windows 7 users

Microsoft removed the DirectX Joystick Driver DLL(dx8vb.dll) from the windows core on these versions. If you using 
these versions you have to register the driver DLL by your self.

Registering DX8VB.DLL

Copy dx8vb.dll file from our compufly.zip file to SysWOW64 folder of windows

Run the command prompt as "run as administrator"

go to SysWOW64 folder on command prompt (type "cd c:windowssyswow64")

Type "regsrv32 dx8vb.dll"

press enter and see the "succeeded" message.


Note:


Some if not most info relating to Flytron's Compufly has been copied from Flytron's Website www.flytron.com

All original code is from Flytron's Compufly Software
