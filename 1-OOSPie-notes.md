*Waiting for GabrielHowardCI sync...*
# OxygenOS Pie for Mi A1
## Important
- PIXEL P sGSI [GIST](https://gist.github.com/TheGabrielHoward/71d22d6d7c6bb71d02a37f8cc5dc8d3f)
- P/Q sGSI TELEGRAM GROUP: [@PsemiGSI](t.me/psemigsi)
- SOME NOTES ARE IN THE GROUP, I RECOMMEND JOIN
- **READ ALL** GUIDE BEFORE ASKING ON THE GROUP, YOU ARE WARNED

----------------
### known Bugs
- SELinux is Permissive
- Deep Sleep
- FIX AVAILABLE - Hotspot (Working by an app but with No internet access)
- FIX AVAILABLE - Power Menu Toggles (As they don't work, you have to restart with long pressing power button and to go to recovery long press power+vol.up)
- FIX AVAILABLE - Brightness is too low

### How To Install
- Your device should have treble partitions. (Tissot Manager > Repartition)
- Wipe system, data, cache and vendor
- Flash OOS System Image 
- Flash vendor Image
- Flash boot Image (for flex's vendor)
- Flash any treble compatible kernel
- Flash Magisk (Optional)
- Go to Tissot Manager > Patches > Change SeLinux to Permissive Mode
- Reboot to Recovery
- Mount system and vendor
- Flash OOS-POST-GSI and all fixes (Check Downloads)
- Reboot to system.

### Notes
- For wifi, turn on hotspot first (though it is bugged so it won't turn ON), then turn on wifi. It will work.
- For in-call earphone sound, Go to the phone app>Tap on 3 dots at top right>Settings>Disabe Noise Cancellation
- For disabling hw buttons. Flash Navbar Enabler Magisk Module by @StallixDOWNLOADS

## Downloads
### System Image
Latest Oxygen OS Build (Android 9)
- [OxygenOS (July 01)](https://mirrors.lolinet.com/firmware/gsi/OxygenOS-AB-9-20190701-ErfanGSI.img.7z)

### Vendor Image
- [**RECOMMENDED** - Vendor 20190501.img](https://drive.google.com/open?id=1Uuv9hL9bC-ApNfnLEbly7dFR_eeOCEcu)

### Boot Image
For 20190501 flex's vendor
- [**RECOMMENDED** - Edited Boot Image 20190501.img](https://t.me/PsemiGSI/19770)
- [Boot Image 20190501.img](https://drive.google.com/open?id=1aQMvuK5mV9dXMIWNqP9LFo9FwCPT5SV9)

### Other Fixes
- Brightness Fix: [GDrive](https://drive.google.com/file/d/1-YvoKYlll1SIMbToDaO4MOeKOKZH8AiX/view?usp=drivesdk)
- POST GSI: [GDrive](https://drive.google.com/file/d/1-RNjlEHv1r0LNekpny5WLo6G1-ukIpp7/view?usp=drivesdk)
- InCallAudio Fix: [Mega](https://mega.nz/#!i0AREajJ!TZBfwxOf_fGdzlXKy7dFVEW4aPLGddZc9VqyiOc4eZY)
- RestartPowerOff Fix: [GDrive](https://drive.google.com/file/d/1-cNQZ5iHz9mSK9AIyfbR2MA6ikeqs3Tb/view?usp=drivesdk)
- NavBarEnabler (Magisk): [GDrive](https://drive.google.com/file/d/1Ws09GhcqIf90rws0hsOakV-mPfQhwAZL/view?usp=drivesdk)