# Invoke-AutoIt

Loads the AutoIt DLL and PowerShell assemblies into memory and executes the specified keystrokes.

This was mainly created to bypass some application restrictions when it came to sending keystroke input via sendkeys(), sendinput() or sendmessage().
e.g. Windows's Remote Desktop Client ;)

# Notes for Red/Blue Teamers
 This script isn't completely opsec safe as it does drop the AutoIt DLL to disk in the user's Appdata\Local\Temp Directory.