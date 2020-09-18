# Windows Liquifier
 > Windows Liquifier - Your open-source Windows Swiss Army Knife

## What does it do?

'Windows Liquifier' is another name for Matt's Custom Recovery and Utilities using DISM (C.R.U.D.) for Windows Preinstallation Environment (Windows PE).
Basically, the Windows Liquifier is a series of Windows batch script files run on the start of Windows PE.

The Windows Liquifier can wipe local hard drives, install Windows 10 Home and Pro, and (probably the coolest) can create a local administrator for almost any Windows installation.
All of these processes are linked together by a main menu of sorts, which is a batch script that runs on the start of Windows PE.

## Bugs/Issues

At the moment of v0.1 release, the detectbios.bat file does not work as intended. There may be some other minor bugs, so feel free to submit a bug report.

## Installation

The Windows Liquifier is intended to be downloaded as an .img file, so the user can easily burn the image onto a USB flash drive (recommended), a DVD (maybe), or onto a hard drive (unlikely).

**Requirements:**
 - Access to a Windows computer
 - A stable internet connection
 - You may need to have administrator access to install a program necessary for imaging the drive

### Installation Steps

**Step 1:** Download and install Win32 Disk Imager from https://sourceforge.net/projects/win32diskimager/

**Step 2:** Download either the lighter image, which has no installation files for Windows, or the full image, which does include installation files for Windows. Check the releases page here: https://github.com/HanYolo55/windows-liquifier/releases

**Step 3:** Write an image using Win32 Disk Imager write function.

**Step 4:** Boot into the drive by going to your computer's BIOS and select your device. For most devices, pressing F12 or F10 will get you into the Boot Devices menu at boot. For more information, go to Google and look for your computer's model number.

**Step 5:** It should take about 15 seconds to about a minute max to boot into Windows PE. Follow the prompts, and you're done! Good luck and have fun.

