# win10script
This is the Ultimate Windows 10 Script from a creation from multiple debloat scripts and gists from github. I also added Chocolatey and other tools to the script that I install on every machine.
- One command run standard: 
	powershell -nop -c "iex(New-Object Net.WebClient).DownloadString('https://git.io/JJgmB')"
- One command run gaming: 
	powershell -nop -c "iex(New-Object Net.WebClient).DownloadString('https://git.io/JJ54A')"
- One command run interactive: 
	powershell -nop -c "iex(New-Object Net.WebClient).DownloadString('https://git.io/JJjTa')"
## ChrisTitusTech Additions

- Dark Mode
- One Command to launch and run
- Chocolatey Install
- O&O Shutup10 CFG and Run
- Added Install Programs
- Added Debloat Microsoft Store Apps
- Uninstalling OneDrive (This all the scripts)
- Installs: Chocolatey, Notepad++, MPC-HC, 7-Zip and Java

## Modifications
I encourage people to fork this project and comment out things they don't like! Here is a list of normal things people change:
- Standard: 
	- Installs: Chocolatey, Notepad++, MPC-HC, 7-Zip and Java
	- Enables Clipboard History
	- Enables Dark Mode
- Gaming: 
	- Checks if your graphics card is NVIDIA or AMD and installs GeForce Experience or AMD Adrenalin accordingly.
	- Installs: Chocolatey, Notepad++, MPC-HC, 7-Zip, Java, Discord Canary, Steam, Legendary from: https://github.com/derrod/legendary
	- Enables Dark Mode
	- Enables Clipboard History
	- Offers to install Playnite, Playnite is an open source video game library manager with one simple goal: To provide a unified interface for all of your games. 
		Check out Playnite at https://playnite.link/ or https://github.com/JosefNemec/Playnite
- Interactive: 
	- Installs: Chocolatey, Notepad++, MPC-HC, 7-Zip and Java.
	- Let's you choose which Office Suite and Web Broser you want to install.
	- Offers the option to enable Dark Mode or not.
	- Offers the option to enable Clipboard history or not.

Comment any thing you don't want out... Example:

```
########## NOTE THE # SIGNS! These disable lines This example shows UACLow being set and Disabling SMB1
### Security Tweaks ###
	"SetUACLow",                  # "SetUACHigh",
	"DisableSMB1",                # "EnableSMB1",

########## NOW LETS SWAP THESE VALUES AND ENABLE SMB1 and Set UAC to HIGH
### Security Tweaks ###
	"SetUACHigh",
	"EnableSMB1",
```
