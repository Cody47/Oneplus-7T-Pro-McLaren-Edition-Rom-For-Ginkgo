#OxygenOS Pie for Mi A1

##INSTRUCTIONS

1. Your device should have treble partitions. (Tissot Manager > Repartition)
2. Wipe system, data, cache and vendor

3. Flash OOS GSI port by @Khode_Erfan 
4. Flash vendor image for tissot
5. Flash any treble compatible 3.18 kernel
6. Flash Magisk (Optional)
7. Go to Tissot Manager > Patches > Change SeLinux to Permissive Mode

8. Reboot to Recovery
9. Mount system and vendor
10. Flash OOS-POST-GSI by me. It also includes camera fix by @Khode_Erfan

11. Reboot to system.
12. If you have no-incall sound, flash acdb_p_gsi.zip. Thanks to flex for acdb fix

##BUGS
1. Hotspot (Working by an app but with No internet access)  2. Power Menu Toggles (As they don't work, you have to restart with long pressing power button and to go to recovery long press power+vol.up)  3. Other bugs can be there.NOTES
1. For wifi turn on hotspot first (though it is bugged so it won't turn ON), then turn on wifi. It will work.  2. For in-call earphone sound, Go to the phone app>Tap on 3 dots at top right>Settings>Disabe Noise Cancellation.  3. For disabling hw buttons. Flash Navbar Enable Magisk Module by @StallixDOWNLOADS

##DOWNLOADS
- System Image: https://mega.nz/#!ydgmwCIA!dMJIjAXgAFzunI8eJ4u42_g7gCpqXnwhpCCytEXy_w0
- Vendor: https://sourceforge.net/projects/pixeldust-treble/files/vendor/

POST-sGSI: https://mega.nz/#!OtRDyahA!3-nRCL8AHe_zJ5b1f8WSyaMOedgkuEb5f-7e1XfKekQInCallAudio Fix: https://mega.nz/#!i0AREajJ!TZBfwxOf_fGdzlXKy7dFVEW4aPLGddZc9VqyiOc4eZY

NavBarEnabler (Magisk): https://drive.google.com/file/d/1Ws09GhcqIf90rws0hsOakV-mPfQhwAZL/view?usp=drivesdk