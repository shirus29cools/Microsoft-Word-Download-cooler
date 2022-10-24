THIS IS A VIRUS MADE BY ME!
IM NOT RESPONSIBLE FOR ANY DAMAGES!

Trojan.BAT.HappyPong is a dangerous virus that edit the registry. It can be ran on Windows Vista and up.
This virus cannot be run on Windows XP because it might have errors.

Name:HappyPong, HappyPong.exe, fukpong, fukpong.exe
Type: Trojan
Operating systems: Microsoft Windows
Creator: Kevin Reagan
Date: October 24th, 2022
Origin: Vietnam
Programming Language: Batch, VBScript, JavaScript
File type: .exe, .bat
Alias(es): Trojan.BAT.HappyPong, Trojan.Batch.HappyPong, Trojan.Win32.HappyPong,
Trojan.BAT.fukpong, Trojan.Batch.fukpong, Trojan.Win32.fukpong

Payloads:
When the virus is executed, it will show a message saying:
"fukpong.exe is not a valid Win32 application!"
If OK is pressed or the message is closed, it will wait 30 seconds then it will show its payloads. If the user end the
process (mshta.exe, HappyPong.exe) in the Task Manager before running, the virus will not show its payloads after 30
seconds.
After 30 seconds, it will restart File Explorer, then terminate mutiple programs like Task Manager. Then it will:
Create a .txt file in its location named "note.txt". The TXT file looks like an email. But it's not.
Create a hidden folder named "HappyPong" in C:\WINDOWS. The folder cannot be shown by Folder Options because it is hidden
by the Command Prompt (attrib command)
Create VBS, BAT, MP3 and HTA files in the HappyPong folder
Execute some files in the HappyPong folder
Then it will disable some programs (Task Manager, Control Panel, Run, Command Prompt - allowing batch files to run,...)
It also disables features like Aero Peek and most used apps in the Start Menu.
It also changes all files in the .exe file's location to .vbs (VMware files, VirtualBox files, Scratch files, bat and cmd files, HTML files, image files, system files and more)
It also changes AM or PM to "HAPPY"
It also changes the Taskbar color
It also disables the Windows Defender (only on supported OSes)
It also changes the search box text to "YOUR_COMPUTER_HAS_BEEN_TRASHED!" (only on Windows 10)
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
After a few seconds, it disables Desktop icons, network connections and Registry Editor and it change the lock screen background to an SCP-173 image (this payload may not work). It plays a Windows 7 Error Remix music on the background. It also change the username to "LOVEYOU". It also change the background to my profile picture (ugly, right?)
After 60 seconds, it shows a red screen. Then it speaks:
"A problem has been detected and windows has been suspended for the rest of your life!"
And a funny thing is... Every 60 seconds, it shows a red screen then it speaks. It does this eight times (for 8
minutes)
After 9 or 10 minutes, it terminates File Explorer, then it shows a message saying:
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
Please note that the computer will shut down every time when the user boot to their desktop and a message saying:
"SHUTDOWN BATTLE STARTING... FOREVER!" with no title
Safe Mode will be useless because there is no power options.

Signs:
Before executing the virus:
This virus is known as fake Microsoft Word
1. A zip file named "HAPPYPONG_SETUP_WINRAR 60 66 60 06"
2. Inside the zip file, there is a folder named "HAPPY", a txt file, and an exe file
3. Inside the HAPPY folder, it contains the "HAPPY0", "HAPPY1", "HAPPY10", "HAPPY100", "HAPPY1000", "HAPPY1001" and the "where are other folders" folders.
4. Inside "where are other folders", there is a file named READ THIS CAREFULLY or SOURCE CODE
5. The TXT file in HAPPYPONG_SETUP_WINRAR folder is named "Thank you for downloading Microsoft Word!"
6. The EXE file is named "HappyPong", and it has a word icon
7. The EXE file's version is 6.6.6.6, and the original filename is "fukpong.exe"
8. The EXE file is ran as administrator
After executing the virus:
1. A message in Windows XP or older appeared. The filename is HappyPong.exe, but it says fukpong.exe. At the end of the message, it must be a ".", not a "!" .
2. In the PC corner, there is a message saying "You must restart your computer to turn off User Account Control"
3. Explorer.exe restarted
4. imgur and scratch link opens automatically
5. Date changed to June 6 2006, (computer time) HAPPY.
6. Musics and voices play in the background
7. Red screen appears
8. Background changed and empty desktop
9. Cannot shutdown PC
10. Cannot access drives and folders
11. No clock or volume on taskbar
12. Explorer.exe terminated, and a message appears
13. PC Shutdown automatically
14. Logon message
15. Mutiple users in lock screen
16. PC shutdowns when password is entered

Rejected payloads:
1. Changing the password to "666" (Rejected because the code won't work)
2. Changing the time to 6:06AM (Rejected because the code won't work)
3. If the username is "Flora" or "Brendan", it will open a Scratch website
4. If the user has Outlook, it will send an email that has an image from Alear TG TF on DeviantArt (Rejected because
the VBS file won't work)
5. Spawn files on folders
6. Delete some folders in C:\Users\username
7. HKCU\Software\HappyPong key
8. After 69 seconds, it will run a meme version of MEMZ (Rejected because some versions of PowerShell will not download the FUK.exe file)
9. The StopExploring folder inside C:\WINDOWS\HappyPong
10. Rename all file named "HAPPY" to HAPPY.LOVEYOU(random number) (This is fixed)
11. Delete the SetupType key (Rejected because the VBS file won't work)
12. Block DeviantArt (the hosts file won't work)
13. NonEnum? (Rejected because the code won't work)
14. Enterkey.vbs (Rejected because the VBS file works, but do nothing)

Removal:
There are no known removal for this virus. The removal is very hard. You must download a tool like WMERT to remove this virus.

External links:
1. https://www.deviantart.com/gaminglover/art/fire-emblem-engage-alear-tg-tf-sequence-929787899
2. https://lhuong270767.wixsite.com/happy
3. https://www.youtube.com/watch?v=H4dGpz6cnHo
4. https://www.youtube.com/watch?v=5BZLz21ZS_Y
5. https://i.imgur.com/ilGkG6C.jpeg
6. https://scratch.mit.edu/users/brendancodingxd
7. https://scratch.mit.edu/users/queennotonline
