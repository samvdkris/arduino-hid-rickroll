# Arduino HID rickroll

How to use it:
- OPTIONAL: Change the mp3 file in rickroll.vbs (line 5). If you do this, you'll have to change the rickroll.vbs download link in arduino-hid-rickroll.ino (line 31)
- OPTIONAL: If you *REALLY* want to be an asshole, you can comment line 39 out (arduino-hid-rickroll.ino) and uncomment line 40. This adds the VBS file to startup.
- Uncomment either line 40 or line 49 to 49 (depending on if your Arduino has a button soldered on it or not)
- Upload the code to your Arduino.
- ???
- Profit!

I also included the duckyscript version in case you're using a rubber ducky.

To stop it, just close `Microsoft ® Windows Based Script Host` in task manager or reboot the computer. If you want to (slightly) un-asshole yourself and remove the VBS file from startup, execute `reg delete HKLM\Software\Microsoft\Windows\CurrentVersion\Run /v TotallyNotShadyStartupItem` as administrator.

Please note that this will only work if the user is an admin.