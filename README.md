# PS-Script-Bedrock-Server-Update-Backup
Powershell Script for automatic updating a bedrock server and backup the Worlds folder

This script will check for new updates for the bedrock server. If an update is found it will stop the server, backup the worlds, backup config files, download, extract, install the update, restore the config files and restart the server. If there are no new updates, the script will stop the server, backup the worlds, and restart the server. If there has been no changes to the world saves since the last backup, the script will skip the backup.

INSTRUCTIONS:

(1)  PASTE THIS SCRIPT IN NOTEPAD AND SAVE IT IN YOUR SERVER DIRECTORY WITH .PS1 FILE EXTENSION (ex C:\Users\USER\Minecraft Server\Bedrock Server\UpdateBackupScript.ps1)

(2) CHANGE $gameDir VARIABLE TO YOUR SERVER DIRECTORY AND SAVE THE SCRIPT

(3) RIGHT CLICK THE .PS1 FILE AND CHOOSE "RUN WITH POWERSHELL" TO TEST IT, MAKE SURE IT WORKS

(4) CREATE POWERSHELL TASK IN WINDOWS TASK SCHEDULER TO RUN PERIODICALLY (WHEN NOBODY IS LIKELY TO BE CONNECTED TO SERVER)

If you like this script, consider buying me a coffee

Buy Me A Coffee https://bmc.link/virtuallyg
