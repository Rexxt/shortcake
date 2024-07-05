# Shortcake
Autounattend files for Windows 10/11.

~~**ℹ Only 64-bit Intel/AMD systems are supported.**~~

Shortcake files aim to minimize Microsoft bloatware and system requirements, while enhancing user experience and shipping commonly used software out of the box, further reducing setup times.

Shortcake leaves user freedom where is due (region and language, disk partitioning...)

## Editions
Multiple different editions of Shortcake are available:

* `w10-generic-home`: for Windows 10 (Home generic key - requires activation).
* `w10-generic-pro`: for Windows 10 (Pro generic key - requires activation).
* `w11-generic-home`: for Windows 11 (Home generic key - requires activation). Disables system requirement checks.
* `w11-generic-pro`: for Windows 11 (Pro generic key - requires activation). Disables system requirement checks.
* `w11-generic-home-nointernet`: for Windows 11 (Home generic key - requires activation). Disables system requirement checks and allows Windows 11 to be installed without an internet connection.
* `w11-generic-pro-nointernet`: for Windows 11 (Pro generic key - requires activation). Disables system requirement checks and allows Windows 11 to be installed without an internet connection.

## Default admin password
The default administrator password is `shortcake*admin!2024`. After installing Windows, the operating system should boot into the account by default. **Change the password as soon as you enter the account.** Use this first logon to create new users on the machine.

## Operations
* User setup is done on first boot, when the computer enters the administrator account.
* (Windows 11) System requirement checks are disabled.
* (Windows 11 No Internet) Internet connection is no longer required to setup your computer.
* Long paths are enabled by default.
* Unsigned PowerShell scripts are enabled.
* Windows Update will not reboot if a user is signed in.
* App suggestions (silent download and install) are disabled (no more Candy Crush installing in the background!).
* Telemetry is explicitly disabled by default.
* Some bloatware will not be installed by default:
  * 3D Viewer
  * ClipChamp
  * (Windows 11) Copilot
  * Cortana
  * Family
  * Get Help
  * Internet Explorer
  * Mail and Calendar
  * Maps
  * Math Input Panel
  * News
  * Office 365
  * OneDrive
  * Outlook for Windows
  * Paint 3D
  * People
  * Power Automate
  * Quick Assist
  * Skype
  * Solitaire Collection
  * Teams
  * Tips
  * To Do
  * Windows Media Player (classic)
  * Wordpad
  * Your Phone
* Some software will be installed by default (if you are connected to the Internet):
  * 7-Zip
  * Firefox
  * Notepad++
  * LibreOffice
  * PowerShell
  * Python 3.11
