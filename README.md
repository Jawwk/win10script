# win10script
This is a Windows 10 debloat script from multiple debloat scripts and gists from github with some additions by me.


## My Additions

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
         unpin start menu function 
         Disabled Edge from auto running and automatic updates for chromium edge and google chrome
         Print Spooler Manual launch
         Re-enable all script to undo script changes
	 Uninstall HPSmart
         

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
