Powershell
==========
Remove ccmcache - deletes the content of c:\windows\ccmcache

Get-ADUser - Gets AD User info and gives options on changing password and account expiry date

Clear Profiles & ccmcache - Gives menu options for removing profiles and ccmcache on remote machine

Repalce Default Folder - Remotley Renames C:\Users\Default to Default.old and then repalces it with another copy of the folder

Multi Account Change - Changes the password and expiry date on multi accounts in a text document

Support Scripts - Incorporates Get-ADUser, Clear Profiles & ccmcache, Repalce Default Folder and Multi Account Change in one place to make life easier

Computer Details - Gets a list of rooms then computer names in each room and runs a report on each computer to get HD & Memory information then outputs in to a CSV like so:
Room	Asset	    Memory	Slots Avalible	Slots Used	HD Space Free GB	Notes
A001 	PC-12345 	4	      0 of 4 	        4 of 4 	    96.7/148.7 	      NO EMPTY SLOTS AVAILABLE!
