# vJoy
Virtual Joystick

Note 04/16/20: If you are wanting a newer version I just signed a version that has newer force feedback stuff.
https://github.com/njz3/vJoy/

For much more go to vJoy web site: http://vjoystick.sourceforge.net

To build the project:

1. Pull the project

2. Run batch file BuildAll.bat

Caution:
You will need to install Visual Studio 2015 (Free)
To build the entire project including the driver you need to install the SDK and puchase a license to sign drivers.

Justin's notes:
1. Install Visual Studio 2013
2. Install Visual Studio 2015 Update 3
3. Install Windows 10 SDK 1511
4. Install Windows 10 WDK 1511
5. Install Windows 10 SDK 1607
6. Install Windows 10 WDK 1607
7. Install DotNet Framework 3.5 SP1
8. Install DotNet Framework 3.5 SDK (6.0.6001.18000.367-KRMSDK_EN.iso)
9. Install Innosetup 5
10. Place the DigiCert Utility on the desktop.
11. Copy the cfg_support_v1.lib file from C:\Program Files (x86)\Windows Kits\10\Lib\10.0.14393.0\km\x86 and x64 to C:\Program Files (x86)\Windows Kits\10\Lib\10.0.10586.0\km\x86 and x64

# What vJoy does

vJoy reates a virtual joystick that can be controlled by code. Various applications read a real joystick (or for example keyboard input), and send that output to the vJoy virtual stick.  It can only create virtual DirectInput sticks (including many flight sticks etc), not XInput (Xbox) controllers.

A common use scenario is for application writers who want to emulate joystick behaviour or want a PPJoy replacement.

## Features

- Virtual Device and device driver 32/64 bit
- Driver is signed
- Configurable:
  - Up to 8 axes
  - Up to 128 buttons and optional 4 POV Hat Switch
- Unified x86+x64 installer
