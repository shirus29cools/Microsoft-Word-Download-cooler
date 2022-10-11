THIS IS A VIRUS MADE BY ME!
IM NOT RESPONSIBLE FOR ANY DAMAGES!

Trojan.BAT.HappyPong is a dangerous virus that edit the registry. It can be ran on Windows XP and up.

Name:HappyPong, HappyPong.exe, fukpong, fukpong.exe
Type: Trojan
Operating systems: Microsoft Windows
Creator: Kevin Reagan
Date: October 11th, 2022
Origin: Vietnam
Programming Language: Batch
File type: .exe, .bat
Alias(es): Trojan.BAT.HappyPong, Trojan.Batch.HappyPong, Trojan.Win32.HappyPong,
Trojan.BAT.fukpong, Trojan.Batch.fukpong, Trojan.Win32.fukpong

Payloads:
When the virus is executed, it will show a message saying:
"fukpong.exe is not a valid Win32 application!"
If OK is pressed or the message is closed, it will wait 20 seconds then it will show its payloads. If the user end the
process (mshta.exe, HappyPong.exe) in the Task Manager before running, the virus will not show its payloads after 20
seconds.
After 20 seconds, it will restart File Explorer, then terminate mutiple programs like Task Manager. Then it will:
Create a .txt file in its location named "note.txt". The TXT file looks like an email. But it's not.
Create a hidden folder named "HappyPong" in C:\WINDOWS. The folder cannot be shown by Folder Options because it is hidden
by the Command Prompt (attrib command)
Create VBS, BAT, MP3 and HTA files in the HappyPong folder
Execute some files in the HappyPong folder
Then it will disable some programs (Task Manager, Control Panel, Run, Command Prompt - allowing batch files to run, Registry
Editor,...)
It also disable features like Aero Peek and most used apps in the Start Menu.
It also creates a bunch of user named "LOVEYOU(random number)"
Then it changes the default Internet Explorer page to an image of a Backrooms Entity from the video "The Backrooms -
Found Footage"
After 3 seconds, it opens a website with an image of red and orange balls fighting a robot monster (on my profile picture)
with text saying:
"Hello! Welcome to the happy pong game! Hope you like it!"
After 7 seconds, it will open a Scratch project (the pong game), a remaked version of dixiklo's.
Then it opens a VBS speaking:
"Hello! Welcome to happy pong game! Hope you like it!"
The voice forgot the "the" word.
After 5 seconds, it speask:
"Hey, why are not you answering?"
After another 5 seconds, it speaks:
"OK. I know you cannot speak to me. But now I will play some good music. Sound amazing?"
After a few seconds, it disables Desktop icons and network connections. It plays a Windows 7 Error Remix music
on the background. It also change the username to "LOVEYOU". It also change the background to my profile picture (ugly,
right?)
After 100 seconds, it shows a red screen. Then it speaks:
"A problem has been detected and windows has been suspended for the rest of your life!"
And a funny thing is... Every 100 seconds, it shows a red screen then it speaks. It does this eight times (for 8
minutes)
After 7 or 8 minutes, it terminates File Explorer, then it shows a message saying:
"Thank you for playing my game! But you are tricked! You cannot get your computer back! HAHAHAHAHAHAHAHAHA!!!!!
PREPARE FOR A SHUTDOWN BATTLE!!!!!"
Then it speaks:
"Hey! I am super happy to tell you that your computer has been trashed by HappyPong! Malware Bytes will not help you!
You just recieved a fake email from Daniel! Hehe get scammed noob!"
After 10 seconds, it will shut down the computer.
If the computer is turned on, the user will see a logon message saying:
"GET_READY_TO_BE_KISSED!"
"I_ALWAYS_LOVE_YOU!!!_PRESS_OK_AND_ENTER_YOUR_PASSWORD_TO_BE_KISSED_MY_FRIEND!!!_ILOVEYOU!!!_SOS!!!1"
After OK is pressed and their password is entered, the computer will shut down.
Please note that the computer will shut down every time when the user boot to their desktop.
Safe Mode will be useless because there is no power options.

Removal:
DO NOT RESTART, LOGOFF OR SHUT DOWN YOUR COMPUTER, YOU MAY NOT BE ABLE TO USE THE COMPUTER AGAIN!!!
You must create a .bat file to remove the virus.
It will be a long removal.
First, delete the TXT file (if you don't want)
Second, create a .bat file with this code:

reg ADD HKLM\Software\Microsoft\Windows\CurrentVersion\Policies\System /v EnableLUA /t REG_DWORD /d 1 /f
reg ADD HKCU\Software\Microsoft\Windows\CurrentVersion\Policies\System /v DisableTaskMgr /t REG_DWORD /d 0 /f
reg ADD HKLM\Software\Policies\Microsoft\Windows\System /v DisableGPO /t REG_DWORD /d 0 /f
reg ADD HKCU\Software\Policies\Microsoft\Windows\System /v DisableCMD /t REG_DWORD /d 0 /f
reg ADD HKLM\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v NoControlPanel /t REG_DWORD /d 0 /f
reg ADD HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\Explorer /v NoViewOnDrive /t REG_DWORD /d 0 /f
reg ADD HKLM\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced /v HideFileExt /t REG_DWORD /d 0 /f
reg ADD HKLM\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v NoStartMenuPinnedList /t REG_DWORD /d 0 /f
reg ADD HKLM\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v NoStartMenuMFUprogramsList /t REG_DWORD /d 0 /f
reg ADD HKLM\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v NoStartMenuMorePrograms /t REG_DWORD /d 0 /f
reg ADD HKLM\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v NoFolderOptions /t REG_DWORD /d 0 /f
reg ADD HKLM\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v NoRun /t REG_DWORD /d 0 /f
reg ADD HKLM\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v NoSecurityTab /t REG_DWORD /d 0 /f
reg ADD HKLM\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v NoSetTaskbar /t REG_DWORD /d 0 /f
reg ADD HKLM\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v NoPinningToTaskbar /t REG_DWORD /d 0 /f
reg ADD HKLM\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v TaskbarNoPinnedList /t REG_DWORD /d 0 /f
reg ADD HKLM\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v NoSaveSettings /t REG_DWORD /d 0 /f
reg ADD HKCU\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v NoWinkeys /t REG_DWORD /d 0 /f
reg ADD HKCU\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v NoLogoff /t REG_DWORD /d 0 /f
reg ADD HKCU\Software\Microsoft\Windows\CurrentVersion\Policies\System /v DisableChangePassword /t REG_DWORD /d 0 /f
reg ADD HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System /v shutdownwithoutlogon /t REG_DWORD /d 1 /f
reg ADD HKCU\Software\Microsoft\Windows\CurrentVersion\Policies\System /v DisableLockWorkstation /t REG_DWORD /d 0 /f
reg ADD HKCU\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v NoClose /t REG_DWORD /d 0 /f
reg ADD HKCU\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v HideClock /t REG_DWORD /d 0 /f
reg ADD HKCU\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v NoStartMenuMyGames /t REG_DWORD /d 0 /f
reg ADD HKCU\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v NoStartMenuMyMusic /t REG_DWORD /d 0 /f
reg ADD HKCU\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v NoStartMenuNetworkPlaces /t REG_DWORD /d 0 /f
reg ADD HKLM\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v NoDrives /t REG_DWORD /d 0 /f
reg ADD HKLM\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v NoUserNameInStartMenu /t REG_DWORD /d 0 /f
reg ADD HKLM\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v StartMenuLogOff /t REG_DWORD /d 0 /f
reg ADD HKLM\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v NoStartMenuSubFolders /t REG_DWORD /d 0 /f
reg ADD HKLM\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v NoCommonGroups /t REG_DWORD /d 0 /f
reg ADD HKLM\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v NoFavoritesMenu /t REG_DWORD /d 0 /f
reg ADD HKLM\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v NoRecentDocsMenu /t REG_DWORD /d 0 /f
reg ADD HKLM\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v NoSetFolders /t REG_DWORD /d 0 /f
reg ADD HKLM\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v NoAddPrinter /t REG_DWORD /d 0 /f
reg ADD HKLM\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v NoFind /t REG_DWORD /d 0 /f
reg ADD HKLM\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v NoSMHelp /t REG_DWORD /d 0 /f
reg ADD HKLM\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v NoChangeStartMenu /t REG_DWORD /d 0 /f
reg ADD HKLM\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v NoSMMyDocs /t REG_DWORD /d 0 /f
reg ADD HKLM\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v NoSMMyPictures /t REG_DWORD /d 0 /f
reg ADD HKLM\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v NoStartMenuMyDocuments /t REG_DWORD /d 0 /f
reg ADD HKLM\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v NoStartMenuMyDownloads /t REG_DWORD /d 0 /f
reg ADD HKLM\Software\Policies\Microsoft\Windows\Personalization /v NoLockScreen /t REG_DWORD /d 0 /f
reg ADD HKLM\Software\Policies\Microsoft\WindowsStore /v RemoveWindowsStore /t REG_DWORD /d 0 /f
reg ADD HKLM\Software\Policies\Microsoft\WindowsStore /v DisableStoreApps /t REG_DWORD /d 0 /f
reg ADD HKLM\Software\Policies\Microsoft\MicrosoftEdge\Main /v AllowPreLaunch /t REG_DWORD /d 1 /f
reg ADD HKLM\SYSTEM\CurrentControlSet\Services\NlaSvc\Parameters\Internet /v EnableActiveProbing /t REG_DWORD /d 1 /f
reg ADD HKCU\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v HideSCAVolume /t REG_DWORD /d 0 /f
reg ADD HKCU\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v HideSCANetwork /t REG_DWORD /d 0 /f
reg ADD HKCU\Software\Policies\Microsoft\Windows\Explorer /v DisableNotificationCenter /t REG_DWORD /d 0 /f
reg ADD HKCU\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v HideSCAPower /t REG_DWORD /d 0 /f
reg ADD HKLM\Software\Policies\Microsoft\Windows\System /v DontDisplayNetworkSelectionUI /t REG_DWORD /d 0 /f
reg ADD HKCU\Software\Policies\Microsoft\MMC /v RestrictToPermittedSnapins /t REG_DWORD /d 0 /f
reg ADD HKCU\Software\Microsoft\Windows\CurrentVersion\Policies\System /v HideFastUserSwitching /t REG_DWORD /d 0 /f
reg ADD HKCU\Software\Microsoft\Windows\CurrentVersion\Policies\System /v DisableRegistryTools /t REG_DWORD /d 0 /f
reg ADD HKCU\Software\Microsoft\Windows /v SearchboxTaskbarMode /t REG_DWORD /d 1 /f
reg ADD HKCU\Software\Microsoft\Windows\DWM /v EnableAeroPeek /t REG_DWORD /d 1 /f
reg ADD HKLM\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v NoNetworkConnections /t REG_DWORD /d 0 /f 
reg ADD HKLM\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v NoDesktop /t REG_DWORD /d 0 /f
attrib -r -h -s C:\WINDOWS\HappyPong
attrib -r -h -s C:\Users\%username%\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup\SHUTDOWN.bat
wmic useraccount where name='%username%' set FullName='your username'
wmic useraccount where name='%username%' rename 'your username'
taskkill /f /im explorer.exe
taskkill /f /im wscript.exe
start explorer.exe

Once the BAT file is executed, you wil have to delete the HappyPong folder in C:\WINDOWS. Then delete the file named
"SHUTDOWN.bat" in C:\Users\your username\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup.
Third, press Windows Key+R
Fourth, type "regedit", press OK
Fifth, navigate to HKEY_LOCAL_MACHINE\Software\Microsoft\Windows\CurrentVersion\Policies\System, then look for the
"legalnoticecaption" and "legalnoticetext" key, then change the value data to blank.
Sixth, navigate to HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main (if you have Internet Explorer),
then look for the "Start Page" key, change the value data to https://www.msn.com/vi-vn?ocid=iehp
Seventh, navigate to HKEY_CURRENT_USER\Control Panel\International, then look for the s1159 and s2359 key, then
change the value data to AM and PM (AM for s1159 and PM for s2359)
Eighth, delete the EXE file.
Nineth, go to Settings > Accounts > Family & other users, under Other users, select any user named "LOVEYOU(random)". 
Next to Account and data, select Remove. Note that this will take several minutes to delete a bunch of users.
And the last one, restart your computer. Then you're done!
I hope this helped you, and I'm not responsible if this does not work!
