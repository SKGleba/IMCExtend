# IMCExtend
MBR Magic by SKGleba

![ref0](https://cdn.discordapp.com/attachments/466454495258476545/466873102870118400/IMG_20180712_010439.jpg)

# This guide applies ONLY to Playstation Vita 2XXX models and Playstation TV, commonly called "Slim" and "PSTV".
# Introduction:
This mod allows you to _permanently_ extend the internal ux0 storage to 1.5GB by modifying boot data regions.
The only downside is that the ur0 partition will be trimmed down to 1GB.

![ref1](https://cdn.discordapp.com/attachments/466454495258476545/466873056250429441/IMG_20180711_222431.jpg)

# Installation:
1) Download and install the provided VPK file. If you are using ENSO NSKBL hack, make sure that the correct enso installer is installed.

2) Make a backup of all important ur0 files (they should be safe, but better to be sure)

3) Open IMCExtend, accept the agreement, navigate to "Options->Backup", and select "Backup vd0". Eventually you may backup tm0/id_data too. Dumps are saved to ux0:data/%name%.img

4) Disable all unnecessary plugins and reboot.

5) Now, we will install the mod. Open IMCExtend, accept the agreement and select "Extend internal ux storage"
  
6) A prompt asking if you are sure that you want to flash IMCExtend will appear. After preesing "Yes" the installer will start the flash process.

7) DO NOT TOUCH THE DEVICE UNTIL IT FINISHES

8) After flashing, the following screen should appear:
![ref6](https://cdn.discordapp.com/attachments/466454495258476545/466462385499275274/IMG_20180711_063154.jpg)

9) If you are a user of ENSO NSKBL hack - launch the enso installer and install enso, otherwise - reboot.

10) If your vita reboots fine - thats it! You just permanently extended internal ux0 storage on your vita/tv.

# FAQ:
 - Q: What do you mean by "permanent"? Does it stay after fw update/reinstall?
   - A: Yes, the only way to remove the mod is to uninstall via the provided manager.
 - Q: Can I update when a new firmware comes out?
   - A: No, you should wait for someone to confirm that it works/or that it breaks the vita.
 - Q: My device is stuck on bootlogo/health warning/spinning circle, help!
   - A: If enso logo - reinstall the firmware, If sony logo/health warning/spinning circle - remove sony mc, boot to safemode, select "Format Memory Card". Alternatively, system restore may help.
 - Q: Why the vita does a soft reboot when i remove/insert the mc?
   - A: Patches are applied. (TBH idk, something related to the parser)
 - Q: How can i restore a backupped partition image?
   - A: "Options->Restore"
 - Q: Im getting a critical error at boot, and i cant restore the firmware via safemode.
   - A: Something happened while the installer was running, its a unrecoverable BRICK.
 - Q: Is this tool compatible with XXXXX?
   - A: No
 - Q: You did a great job! How can i help/donate you?
   - A: paypal.me/skgleba (thx! ^_^)
 
 # Useful notes:
- You can not use unofficial enso mods that are not listed as "supported".
- I recommend doing a backup of ur0:
- For any serious issue/help DM me on twitter (twitter.com/skgleba)
