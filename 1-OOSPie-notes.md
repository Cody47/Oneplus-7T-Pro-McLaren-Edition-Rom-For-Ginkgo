*Waiting for GabrielHowardCI sync...*
# OxygenOS 9 for AB Devices - NOTES for Mi A1
## Important
- Android 10 GSI Notes: https://gist.github.com/TheGabrielHoward/1666186cc4f151de8f6bea4872c30e1a
- 9/10 GSI TELEGRAM GROUP: [@PsemiGSI](t.me/psemigsi)
- SOME NOTES ARE IN THE GROUP, I RECOMMEND JOIN
- **READ ALL** GUIDE BEFORE ASKING ON THE GROUP, YOU ARE WARNED

![ooospreview](https://www.xda-developers.com/files/2018/07/oxygenos-logo-feature.png)
----------------
### known Bugs
- SELinux is Permissive
- Deep Sleep (On some builds)

### How To Install
**CLEAN FLASH**

IMPORTANT: Treble needed
- Wipe data, cache, system and vendor (Format Data optional)
- Flash boot image
- Flash system image
- Flash vendor image
- Flash [Permissiver_v5](https://www.androidfilehost.com/?fid=6006931924117940902) or TissotManager > Patches > SELinux state > Permissive
- Reboot to system
- Once booted, install GMS Apk (check above)
- If you want, reboot to recovery and flash magisk and lagfix


**DIRTY FLASH**

To dirty flash (update) any boot, system or vendor image, do this:
- Wipe system, vendor and cache
- Flash boot.img
- Flash vendor.img
- Flash system.img
- Reboot system


### Notes
- For wifi, turn on hotspot first (though it is bugged so it won't turn ON), then turn on wifi. It will work.
- For in-call earphone sound, Go to the phone app>Tap on 3 dots at top right>Settings>Disabe Noise Cancellation
- For disabling hw buttons. Flash Navbar Enabler Magisk Module by @StallixDOWNLOADS

----------------

### System Image
Latest Oxygen OS: 9
- [**RECOMMENDED** - OxygenOS 9 **OP6** (August 26)](OxygenOS-AB-9-20190826-ErfanGSI.img.7z
841.1 MB)

### Vendor Image
- [**RECOMMENDED** - Vendor 20190731.img](https://drive.google.com/file/d/1n1TcOXpVtore5M7-lVpHv7IP9Q3z00Sv/view)
- [Vendor 20190501.img](https://drive.google.com/file/d/1Uuv9hL9bC-ApNfnLEbly7dFR_eeOCEcu/view)

### Boot Image
- [**RECOMMENDED** - Boot Image 20190501.img](https://drive.google.com/open?id=1aQMvuK5mV9dXMIWNqP9LFo9FwCPT5SV9)
- [Boot Image 20190730.img](https://drive.google.com/file/d/1ikjaPp_s5gY4U5rTBQSDGUPIKvXpF6Cg/view)

### Fixes for OOS
- Brightness Fix: [GDrive](https://drive.google.com/file/d/1-YvoKYlll1SIMbToDaO4MOeKOKZH8AiX/view?usp=drivesdk)
- POST GSI: [GDrive](https://drive.google.com/file/d/1-RNjlEHv1r0LNekpny5WLo6G1-ukIpp7/view?usp=drivesdk)
- InCallAudio Fix: [Mega](https://mega.nz/#!i0AREajJ!TZBfwxOf_fGdzlXKy7dFVEW4aPLGddZc9VqyiOc4eZY)
- RestartPowerOff Fix: [GDrive](https://drive.google.com/file/d/1-cNQZ5iHz9mSK9AIyfbR2MA6ikeqs3Tb/view?usp=drivesdk)
- NavBarEnabler (Magisk): [GDrive](https://drive.google.com/file/d/1Ws09GhcqIf90rws0hsOakV-mPfQhwAZL/view?usp=drivesdk)
- HDR Fix (TWRP): [GDrive](https://drive.google.com/open?id=1eCQG34rmxGnKPZ9XvVneqUcktO1XFoio)

**ROUNDED CORNERS FIX**
- oneplus-framework-res: [GDrive](https://drive.google.com/open?id=1tRzQUbEH2HecWa1xjW7Fey-5yjk99pZj)
Move this apk to System/priv-app/oneplus-framework-res folder and reboot

### Kernel
NOTE: Kernel is not necessary

For 4.9 Vendor (Flex's):
- [**NOT RECOMMENDED** - Moun 8.0 - Treble](https://github.com/mountaser/Moun_Kernel_Tissot/releases/download/8.0/Moun_Kernel_V8.0-Tissot-4.9-Custom-Treble.zip)
- [**NOT RECOMMENDED** - Extreme Kenrle 14.6+](https://t.me/eXtremeKernel_Channel)

### Treble TWRP (By CosmicDan)
- https://github.com/CosmicDan-Android/android_device_xiaomi_tissot/releases

--------------

### Magisk
In order to install Magisk on Pie, download stable [Magisk 19.3](https://github.com/topjohnwu/Magisk/releases/download/v19.3/Magisk-v19.3.zip) and flash in TWRP. once booted, if the app is not showing in the app drawer, install manually [Magisk Manager 7.3.2](https://github.com/topjohnwu/Magisk/releases/download/manager-v7.3.2/MagiskManager-v7.3.2.apk

### Camera
Arnova's Camera (5.1 & 6.2)
- Gcam 5.1: [Download](https://f.celsoazevedo.com/file/gcamera/GCam-5.1.018-Pixel2Mod-Arnova8G2-V8.3b1.apk)
- Gcam 6.2: [Download](https://t.me/TissotGCam/45206)

To Fix Camera (if broken), open terminal /termux)
```
pm install cameraname.apk
```
or adb
```
adb install cameraname.apk
```

### Disable Hardware Capacitive Buttons
In order to disable Capacitive Buttons flash this module in Magisk and reboot
- [**RECOMMENDED** - HWKeys-Disabler.zip](https://drive.google.com/file/d/1-7P1VW1TFDA4glCL2n2F)

### Wrong Pin/Password Fix
In order to fix Wrong Pin/Password, flash [Permissiver_v5](https://www.androidfilehost.com/?fid=6006931924117940902)

### Fix No Signal - No SIM
- [Fix "No Signal - No SIM"](https://telegra.ph/Fix-No-Signal---No-SIM-in-Pie-sGSI-01-06)

### Useful Modules
- [**TWRP** - Pixel Boot Logo](https://drive.google.com/file/d/1WbdCb5AciXBo9lxoGglMnPXJHhxxTNsw/view?usp=drivesdk)
---------------------

### OT Telegram Group
If u like the off-topic, here u are: https://t.me/psemiGSIOT

------------
<p align="center">
 Created & Maintained by Gabriel Howard | All Rights Reserved
 </p>