# win10script
This is a Windows 10 debloat script from multiple debloat scripts and gists from github with some additions by me.

Open up a powershell window and paste one of the commands for what you want to do.

# DEBLOAT PASTE = 
```powershell -nop -c "iex(New-Object Net.WebClient).DownloadString('https://git.io/JTw1y')"```

# UNDO PASTE = 
powershell -nop -c "iex(New-Object Net.WebClient).DownloadString('https://git.io/JTwMk')"

This debloat script is edited for my guide to optimize computer for gaming: https://docs.google.com/document/d/14s_rcDk_CPQGHj2dec5-444rSgZj6BthzoTj-bzBtkU/edit?usp=sharing

## My Additions to this script

- Added Choice Prompts for: 
         O&O Shutup,
         OneDrive,
         Xbox Apps,
         Powerplan,
         Windows Theme,
         Microsoft Office,
         Meltdown & Spectre,
         Photos App,
         YourPhone App,
         Cortana,
         Windows Update,
         Movies & Tv,

 - Turned off auto install of: 
         Adobe,
         Media Player Classic,
         7zip,
         Chocalatey,
         Notepad ++,

 - Changed Options: 
         FastStartup,
         RemoteDesktop,
         Restart,
         LinuxSubsystem,
         Indexing,
         Defender,
         DefenderCloud,
         UpdateMSRT,
         VideosFromThisPC,
         VideosFromExplorer,
         UpdateDriver,
         SmartScreen,
         Cortana,
         StartMenuTiles,
         TitusProgs,
         Adobe,
         7Zip,
         Notepadplusplus,
         MediaPlayerClassic,
         MeltdownCompatFlag,

- Extra: 
         unpin start menu function,
         Disabled Edge from auto running and automatic updates for chromium edge and google chrome,
         Print Spooler Manual launch,
         Re-enable all script to undo script changes,
	 Uninstall HPSmart,


## Modifications
I encourage people to fork this project and comment out things they don't like!

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
