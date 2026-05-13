# New session - 2026-05-07T17:46:44.293Z

**Session ID:** ses_1fc736f3affe6WOhbATEn5dG1g
**Created:** 5/7/2026, 11:46:44 PM
**Updated:** 5/7/2026, 11:54:34 PM

---

## User

how to set a 50/50 split screen on i3?

---

## Assistant (Plan · Big Pickle · 8.6s)

_Thinking:_

The user is asking how to set a 50/50 split screen in the i3 window manager. This is a simple, well-known i3 configuration question. Let me provide a direct, concise answer.

In i3, you typically use `$mod+v` for vertical split and `$mod+h` for horizontal split (or `split v` / `split h` commands). To get a 50/50 split:

1. Position your windows (or use `layout toggle split` to ensure split layout isn't tabbed or stacked)
2. By default, new windows in a split container get equal space.

The key commands:
- `$mod+v` - split vertically (windows stack top/bottom, each 50%)
- `$mod+h` - split horizontally (windows side by side, each 50%)

If you mean setting a default 50/50 split upon launching, you can add to your i3 config:
```
workspace 1 layout splith
```

Or to enforce equal sizing, use:
```
layout default split
```

But actually, the simplest answer is: just use `$mod+Enter` to open a terminal, then `$mod+v` or `$mod+h` (or `$mod+Shift+Enter` depending on bindings) to split, and open another terminal.

Let me give the most practical answer.

In i3, to split the current container into two equal halves:

- **Horizontal 50/50** (side by side): `$mod+h` then open a second window  
- **Vertical 50/50** (top/bottom): `$mod+v` then open a second window  

By default, i3 gives each window in a split container equal space. If they become uneven, reset with `$mod+e` (toggle split layout) or resize manually with `$mod+r` then arrow keys.

For a permanent default on a workspace, add to your i3 config:
```
workspace 1 layout splith
```

---

## User

best OS and Kernel for redmi4a for fastest + best batterylife

---

## Assistant (Plan · Big Pickle · 6.1s)

_Thinking:_

The user is asking about the best OS and kernel for a Redmi 4A (also known as Xiaomi Redmi 4A, codename "rolex") for fastest performance and best battery life. This is a question about Android custom ROMs and kernels.

Let me search for current information about this.

**Tool: websearch**

**Input:**
```json
{
  "query": "best custom OS ROM Redmi 4A rolex performance battery life 2026",
  "numResults": 8
}
```

**Output:**
```
Title: [ROM][10.0]REDMI 4A] Pixel Experience Plus Unofficial [AOSP][rolex] | XDA Forums
URL: https://xdaforums.com/t/rom-10-0-redmi-4a-pixel-experience-plus-unofficial-aosp-rolex.4079399/
Published: 2020-04-08T14:52:11.000Z
Author: N/A
Highlights:
PixelExperience Plus for Redmi 4a [rolex] What is this? Pixel Experience Plus is an AOSP based ROM with minimal customisation, with Google apps included and all Pixel goodies (launcher, wallpapers, icons, fonts, bootanimation) Our mission is to offer the maximum possible stability and security, along with essential and useful features for the proper functioning of the device Based on Android 10.0 Whats working? Wifi Face Unlock RIL Mobile data GPS Camera Flashlight Camcorder Bluetooth FMRadio Lights Sound / vibration Known issues Nothing yet You tell me DON'T FLASH GAPPS, THEY'RE ALREADY INCLUDED Download Donate Liked my work? Give me a beer Stay tuned Our Telegram channel Our blog​
[...]
- Android OS version: 10.0.0_r33
- Security patch level: April 2020
- Build author/Device Maintainer: Manohar Singh
- Device kernel code: https://github.com/Thagoo/Triton_kernel_xiaomi_msm8917
- Source code: https://github.com/PixelExperience
- ROM Developer: jhenrique09

​
[...]
As far as i know, this is a new feature. And bit by bit, it will be implemented into other roms soon. Also, it works very smooth. Takes 1-2 seconds.
[...]
@adi153 thanks for this build! But why gapps is so old? E.g. Chrome is 74 from mostly year ago. Please mention in first post that encryption of device causes boot loop. Also, I can't find an option to enable battery indication in %
[...]
I installed this ROM, and tried to root using magisk via twrp. severally i always stuck on bootloop condition. i tried vversion 20.0 20.3 20.4 of magisk. orange twrp and pitch black the result still not booting.
[...]
I installed this ROM, and tried to root using magisk via twrp. severally i always stuck on bootloop condition. i tried vversion 20.0 20.3 20.4 of magisk. orange twrp and pitch black the result still not booting.
[...]
Try using the version of TWRP from the link below. https://drive
[...]
google.com
[...]
is different than wipe data, i hope you
[...]
[RECOVERY] [OFFICIAL] TWRP 3.2.1-0 for Xiaomi Redmi 4A [rolex] [20171210]
[...]
[ROM][8.1.0_r52][OFFICIAL] AospExtended ROM V5.8 for Redmi 4A/5A [ROLEX/RIVA]
[...]
- ECr34T1v3
[...]
May 1, 2018
- 34 35 36
[...]
] Pixel Experience [A
[...]
][2019/12/12][DISCONTINUED]
[...]
10.0
[...]
] Lineage
[...]
17.
[...]
[ROM][UNOFFICIAL] LineageOS 15.1 for Xiaomi Redmi 4A &amp; 5A [UNIFIED][OTA]
[...]
PixelExperience Plus for Redmi 4a [rolex] What is this? Pixel Experience Plus is an AOSP based ROM with minimal customisation, with Google apps included and all Pixel goodies (launcher, wallpapers, icons, fonts, bootanimation) Our mission is to offer the maximum possible stability and security, along with essential and useful features for the proper functioning of the device Based on Android 10.0 Whats working? Wifi Face Unlock RIL Mobile data GPS Camera Flashlight Camcorder Bluetooth FMRadio Lights Sound / vibration Known issues Nothing yet You tell me DON'T FLASH GAPPS, THEY'RE ALREADY INCLUDED Download Donate Liked my work? Give me a beer Stay tuned Our Telegram channel Our blog​
[...]
- Android OS version: 10.0.0_r33
- Security patch level: April 2020
- Build author/Device Maintainer: Manohar Singh
- Device kernel code: https://github.com/Thagoo/Triton_kernel_xiaomi_msm8917
- Source code: https://github.com/PixelExperience
- ROM Developer: jhenrique09

​
[...]
As far as i know, this is a new feature. And bit by bit, it will be implemented into other roms soon. Also, it works very smooth. Takes 1-2 seconds.

---

Title: List of Best Custom ROM for Xiaomi Redmi 4A [Updated]
URL: https://www.getdroidtips.com/custom-rom-xiaomi-redmi-4a/
Published: 2017-12-07T12:21:04.000Z
Author: Mohammed Huwais
Highlights:
List of Best Custom ROM for Xiaomi Redmi 4A [Updated] 

 

Do you want to Install any Custom ROM for Xiaomi Redmi 4A (Rolex) device? then you are at the right place. Here we will list all the Custom ROM for Xiaomi Redmi 4A. If you have a Xiaomi Redmi 4A device, then you may be knowing that this device runs on Android OS. Well, the biggest advantage of Android is that it is an open-source project. This allows every community to develop and Customize ROM for their phone.
[...]
To begin with, Xiaomi Redmi 4A was launched in November 2016. The smartphone came out of the box with Android 6.0.1 Marshmallow. In this guide, we will show you which are the best custom ROM for Xiaomi Redmi 4A available now.
[...]
Best Custom ROM for Xiaomi Redmi 4A
[...]
Here is the list of Best Custom ROM for Xiaomi Redmi 4A. To Install Any Custom ROM for Xiaomi Redmi 4A, you need TWRP Recovery on your device. Once you have installed TWRP, you can easily start installing Custom ROM or any mods on your Xiaomi Redmi 4A device. Here is the guide to Install TWRP Recovery on Xiaomi Redmi 4A.
[...]
If you have TWRP, then you can simply flash one of the best custom ROM for Xiaomi Redmi 4A here. As we said, there are many custom ROM out there to choose from. Not every Custom ROM is meant to be stable to use as a daily driver. You can read the description and the features that come with the custom ROM given below for Xiaomi Redmi 4A devices.
[...]
Android 15 is the latest version of Google’s mobile operating system, offering a
[...]
of new features and improvements. It focuses on enhancing user privacy, security, and performance.
[...]
key highlights include advanced theft protection, private spaces for sensitive
[...]
and enhanced photography tools.
[...]
15 is expected
[...]
and more secure user experience
[...]
AOSP Extended ROM is based on the AOSP Source code which brings a lot of various cherry-picked commits from multiple other projects. Being based on AOSP, it provides a smooth and lag-free experience out of the box. The developer of AOSP Extended has promised to add many new features and make it even better for future updates.
[...]
### ArrowOS
[...]
ArrowOS is a new Custom ROM and it is AOSP inspired open-source project started with the aim of keeping things simple, clean, and neat. The ROM brings almost the same feature which is very useful for ROM customization and in the end aims to deliver smooth performance with better battery life.
[...]
Dirty Unicorns ROM is one
[...]
AOKP
[...]
### ViperOS:
[...]
ViperOS is a new Custom Firmware based on the AOSP code but has its own custom mods. This ROM is quite famous for its custom-made features from all CM, Lineage, Slim, Omni AOSPA, etc. The ROM was developed when Google released the code for Android 7.1 Nougat. Now it has become one of the most stable Custom firmware with many features and customization. It offers a great balance between battery and performance.
[...]
### CrDroid ROM:
[...]
crDroid is designed to increase performance and reliability over stock Android for your device also attempting to bring many of the best features existent today. We’re mainly based on Lineage OS so use custom kernels compatible with them!
[...]
### Resurrection Remix:
[...]
Resurrection Remix is a combination of the stability provided by CM and features from Slim, Omni, and original Remix builds providing an awesome combination of performance, customization, power, and the newest features brought directly to your device. This ROM is ultimately full-featured, stable, and combined with the best features of open source ROMs. The ROM is also providing a lot of awesome original Resurrection Remix ROM add-on s in the builds which include the best of performance, customization, power, and the newest features of your device!
[...]
### Paranoid Android:
[...]
Paranoid Android is one popular custom ROM built with many new innovative features, a slick user interface, improved performance, and battery backup.

---

Title: Redmi 4A – rolex
URL: https://cyanogenmods.org/forums/forum/xiaomi/redmi-4a-rolex/
Published: 2024-05-25T15:08:11.000Z
Author: N/A
Highlights:
Download LineageOS 16 for Redmi 4A
[...]
LineageOS 14.1 for Redmi 4A (rolex) Nougat 7.1 ROM
[...]
LineageOS 15.1 for Xiaomi Redmi 4A- rolex- Oreo 8.1 ROM Download
[...]
Download crDroid Android 10 ROM for Redmi 4a (Rolex)
[...]
Download Havoc OS 3 Android 10 ROM for Redmi 4a [Rolex]
[...]
Carbon ROM Android Pie for Redmi 4A – Android 9
[...]
Pixel Experience Android 9 Pie for Xiaomi Redmi 4A
[...]
How to Install AOSP Oreo for Redmi 4A – Android 8.1
[...]
How to Install Resurrection Remix OREO for Redmi 4A – Android 8.1
[...]
LineageOS 13 for Redmi 4A – Download and Installation Guide

---

Title: List of Redmi 4A (Rolex) Custom Roms | XDA Forums
URL: https://xdaforums.com/t/list-of-redmi-4a-rolex-custom-roms.3774162/
Published: 2018-04-06T13:31:33.000Z
Author: N/A
Highlights:
---------------------------------------------------------------- Liquid Remix 9.1 Unofficial XDA Thread---------------------------------------------------------------------------------------------------------------- AOSCP - Cypher Project Unofficial ROM by Eric---------------------------------------------------------------------------------------------------------------- [ROM][8.1.0][UNOFFICIAL] COLT OS 2.1 [ROLEX] XDA Thread---------------------------------------------------------------------------------------------------------------- [Unified][RIVA][ROLEX][UNOFFICIAL][VOLTE][OREO][8.1.0_r30]XenonHD XDA Thread---------------------------------------------------------------------------------------------------------------- [ROM][8.1.0_r20][OFFICIAL] MoKee 81.0 for Redmi 4A [Rolex] XDA Thread---------------------------------------------------------------------------------------------------------------- [ROM][8.1.0]Android Open Source Illusion Project
[...]
Rolex][UNOFFICIAL] XDA Thread---------------------------------------------------------------------------------------------------------------- [8.1.0_r26] Sudamod 4.1 Unofficial XDA by Aryan---------------------------------------------------------------------------------------------------------------- MiracleDROID 1.0 Unofficial ROM by Aryan---------------------------------------------------------------------------------------------------------------- OmniROM Unofficial XDA Thread---------------------------------------------------------------------------------------------------------------- Bootleggers ROM Unofficial XDA Thread
[...]
[UNOFFICIAL] XDA Thread ROM Link
[...]
------------------------------------------------------------------------------------------------ AOSPA - Paranoid Android ROM Link---------------------------------------------------------------------------------------------------------------- [ROM][8.1][UNIFIED][OFFICIAL] ToxycOS for Redmi 4A/5A [1.0] XDA Thread ROM By Eric---------------------------------------------------------------------------------------------------------------- COSMIC OS OREO | UNOFFICIAL ROM Link Guide: Wipe, Flash Rom, flash Gapps, Flash Magisk, Reboot ---------------------------------------------------------------------------------------------------------------- CARBON CR 6.1 NOCT OREO [8.1.0_r26][CLANG] | UNOFFICIAL XDA By Carlos Guide: Wipe, Flash Rom, flash Gapps, Flash Magisk, Reboot ---------------------------------------------------------------------------------------------------------------- LineageOS 15.1 (Unofficial) by 33bca aka Offain XDA Thread---------------------------------------------------------------------------------------------------------------- AICP by Aryan OREO | UNOFFICIAL : XDA Thread---------------------------------------------------------------------------------------------------------------- DirtyUnicorns build by Murli | UNOFFICIAL ROM Link---------------------------------------------------------------------------------------------------------------- [ROM] [OREO] [UNOFFICIAL] Validus OS [STABLE] XDA Thread ROM Link---------------------------------------------------------------------------------------------------------------- Infinity Kernel for Oreo Roms: Flash Kernel https://xdaforums.com/redmi-4a/development/infinity-kernel-v3-2-redmi-4a-rolex-t3775549---------------------------------------------------------------------------------------------------------------- ---------------------------------------------------------------------------------------------------------------- Nougat ROMs: LineageOS Rom: https://androidfilehost.com/?fid
[...]
746010030569967699 CRDroid https://androidfilehost.com/?fid=818070582850493743 Viper OS https://www.androidfilehost.com/?fid=7460100305
[...]
51104 Resurrection Remix https://androidfilehost.com/?fid=818070582850494211 Atomic OS Nougat https
[...]
Use AEX Extended, battery drain is amazing
[...]
Bootleggers proved best battery friendly and stable rom so far. Cheers

---

Title: [ROM][9.0.0_r46][OFFICIAL] AospExtended ROM V6.7 for Redmi 4A [ROLEX] | XDA Forums
URL: http://forum.xda-developers.com/t/rom-9-0-0_r46-official-aospextended-rom-v6-7-for-redmi-4a-rolex.3867054/
Published: 2018-11-14T13:54:25.000Z
Author: N/A
Highlights:
AOSP Extended is an AOSP based ROM which provides stock UI/UX with various customizations features along with the Substratum theme engine. The project has been made by cherry-picking various commits from various other projects. Being based on AOSP it provides a smooth and lag-free experience out of the box. We will constantly try to add more features and make it even better in future updates. A ROM by a user, for a user. #StayAOSP #ExtendYourDevice #BeExtended
[...]
XDA:DevDB Information AospExtended Pie Official (rolex), ROM for the Xiaomi Redmi 4a Contributors ECr34T1v3, muralivijay, ataberkozen Source Code: https://github.com/ECr34T1v3 ROM OS Version: 9.x Pie ROM Kernel: Linux 3.x ROM Firmware Required: MIUI 9.2.6.0 Global Based On: AOSP Version Information Status: Stable Current Stable Version: 1.5 Stable Release Date: 2018-12-17 Current Beta Version: 1.1 Beta Release Date: 2018-11-11 Created 2018-11-14 Last Updated 2019-09-02
[...]
Build 2019/08/23: -Merged: New version of AospExtended (v6.7) Changelog in https://blog.aospextended.com/AospExtended-v6.7-Changelog-Merged: August Security Patch (9.0.0_r46) It has been 2 years officially maintaining AEX, i am following new paths for my life. I will no longer compile officially, but I will always be available. Thanks for all, guys <3 Unofficial ROMs and projects: https://ecr34t1v3.github.io Build 2019/07/11: -Merged: July Security Patch (9.0.0_r44) -Merged: SELinux Enforcing -Reworked: Device Tree No-Commonized (Thanks to nick) -Reworked: Doze settings (Ambient display) -Readded: Dirac Settings (Increased Sound) -Fixed: Quickswitch support -Enabled: Incall music -Enabled: AGPS Recommended: Clean Flash (because is new device tree)
[...]
Q: Which TWRP do I use? A: Use latest TWRP for ROLEX from HERE Q: Which GApps do I use? A: Flash OpenGApps Pico (recommended version). Link HERE Q: Is there a bug in ROM?? A: No. It is stable. Maybe there is a problem (if you have it, let me know which one I will correct), but it is stable for daily use. Q: Do I have to wipe data if coming from another ROM? A: Yes, I will not be providing help/support to users that haven't wiped data when coming from another ROM. Q: How often will I be getting updates? A: The plan is for weeklies, if unavoidable circumstances come up, please don't spam the thread. I will release a build as soon as one is ready. Q: Does VoLTE/VoWiFi work? A: Yes, works. Q: Is the ROM official? A: Yes, Official, and updates OTA available. Q: I use Telegram, where can I find help on that platform? A: There is a common AEX Group Chat for all devices, the link is HERE Q: Does SafetyNet pass and is the SELinux Enforcing? A: Yes, SafetyNet does pass and SELinux is Enforcing.
[...]
AOSP Extended is an AOSP based ROM which provides stock UI/UX with various customizations features along with the Substratum theme engine. The project has been made by cherry-picking various commits from various other projects. Being based on AOSP it provides a smooth and lag-free experience out of the box. We will constantly try to add more features and make it even better in future updates. A ROM by a user, for a user. #StayAOSP #ExtendYourDevice #BeExtended
[...]
Build 2019/08/23: -Merged: New version of AospExtended (v6.7) Changelog in https://blog.aospextended.com/AospExtended-v6.7-Changelog-Merged: August Security Patch (9.0.0_r46) It has been 2 years officially maintaining AEX, i am following new paths for my life. I will no longer compile officially, but I will always be available. Thanks for all, guys <3 Unofficial ROMs and projects: https://ecr34t1v3.github.io Build 2019/07/11: -Merged: July Security Patch (9.0.0_r44) -Merged: SELinux Enforcing -Reworked: Device Tree No-Commonized (Thanks to nick) -Reworked: Doze settings (Ambient display) -Readded: Dirac Settings (Increased Sound) -Fixed: Quickswitch support -Enabled: Incall music -Enabled: AGPS Recommended: Clean Flash (because is new device tree)
[...]
GApps do
[...]
: Flash OpenG

---

Title: [ROM][10]Evolution X 4.5 for Redmi 4A[rolex] | XDA Forums
URL: https://xdaforums.com/t/rom-10-evolution-x-4-5-for-redmi-4a-rolex.4130829/
Published: 2020-07-09T04:53:32.000Z
Author: N/A
Highlights:
[ROM][10]Evolution X 4.5 for Redmi 4A[rolex] | XDA Forums
[...]
# [ROM][10]Evolution X 4.5 for Redmi 4A[rolex]
[...]
Evolution X 4.5 for the Redmi 4A [rolex]
[...]
Evolution X is a flashable custom ROM to bring a true Pixel feel to your Android Device at first glance, with many additional configurations at your disposal. We aim to provide frequent builds with monthly security patches from the latest aosp sources!​
[...]
Themes - RGB Accent Picker - Dark Theme Styles (color Bucket) - 17 System Fonts - 6 System Icon Shapes - 4 Statusbar Icon Styles - 2019 Pixel Live Wallpapers - Custom QS Header Images - New Tint Style Toggle - QS Opacity & Color Configs - QS Backround Image Blur Statusbar - Clock Options - Battery Bar - Carrier Label Settings - Network Traffic Activity - Rounded
[...]
Config - System UI Tuner - 7 Battery Icon Style - Battery Percent Show/Hide Config - Old Mobile Style Network
[...]
- 4G/LTE Icon Toggle
[...]
7 Custom VoLTE Icons
[...]
Notification light Config
[...]
Notification - Kill
[...]
QS Footer Text Toggle & Custom
[...]
Icon Toggle -
[...]
- User Switcher Icon Toggle - QS Edit Icon Toggle Power Menu - Restart -
[...]
Restart - Screenshot - Flashlight - Airplane - Settings - Lock Down - Users - Logout - Visibility On Lockscreen Configs Gestures - AOSP Gestures - Swipe To Screenshot - Status Bar Brightness Control - Screen Off Power Button Torch - Double Tap To Sleep Status Bar - Double Tap to Sleep Lockscreen - Toggle To Hide Navbar Pill - Back
[...]
Toggle - Screen
[...]
Launch Music App On Headset Connection - Wake On Charge - Charging Animation - Screenshot Type (Full/Drag) - Dashboard Condition/Suggestion Toggle - Doze Brightness Configs - Default USB Config - Disable Device Identifier Restrictions - Accidental Wake Up Prevention - Sensor Block Per Package - Signature Spoofing Support - Time In State Monitor - Doze Settings - Legacy App Scalling - Alarm Blocker - Wakelock Blocker
[...]
First Time Install / Clean Flash - Make sure you're running the latest TWRP - Boot into recovery - Flash BUILD.zip - Flash TWRP.zip - Wipe Cache - Format data - Reboot to recovery (optional) - Flash Magisk.zip (optional) - Reboot to system & #KeepEvolving[/SIZE] Update / Dirty Flash - Boot into recovery - Flash BUILD.zip - Flash TWRP.zip - Reboot to recovery (optional) - Flash Magisk.zip (optional) - Wipe Cache - Reboot to system & #KeepEvolving Download Donate me!/ Official Chat/ Device Support​
[...]
- ROM Developer: Gaurav
- Kernel Source: [url]https://github.com/Nick89786/android_kernel_xiaomi_msm8917 [/url]
- ROM Source: [url]https://github.com/Evolution-X [/url]
- Build Author: Gaurav
- [*]Android version: 10 [*]Evolution version: 4.5 [*]Security patch level: July, 2020

​
[...]
Evolution X 4.5 for the Redmi 4A [rolex]
[...]
Evolution X is a flashable custom ROM to bring a true Pixel feel to your Android Device at first glance, with many additional configurations at your disposal. We aim to provide frequent builds with monthly security patches from the latest aosp sources!​
[...]
First Time Install / Clean Flash - Make sure you're running the latest TWRP - Boot into recovery - Flash BUILD.zip - Flash TWRP.zip - Wipe Cache - Format data - Reboot to recovery (optional) - Flash Magisk.zip (optional) - Reboot to system & #KeepEvolving[/SIZE] Update / Dirty Flash - Boot into recovery - Flash BUILD.zip - Flash TWRP.zip - Reboot to recovery (optional) - Flash Magisk.zip (optional) - Wipe Cache - Reboot to system & #KeepEvolving Download Donate me!/ Official Chat/ Device Support​
[...]
- ROM Developer: Gaurav
- Kernel Source: [url]https://github.com/Nick89786/android_kernel_xiaomi_msm8917 [/url]
- ROM Source: [url]https://github.com/Evolution-X [/url]
- Build Author: Gaurav
- [*]Android version: 10 [*]Evolution version: 4.5 [*]Security patch level: July, 2020

​

---

Title: Xiaomi Redmi 4a ROMs, Kernels, Recoveries, & Other - XDA Forums
URL: https://xdaforums.com/f/xiaomi-redmi-4a-roms-kernels-recoveries-other.7304/
Published: N/A
Author: N/A
Highlights:
Improve your Xiaomi Redmi 4a's battery life, performance, and look by rooting it and installing a custom ROM, kernel, and more.
[...]
[ROM][rolex][UNOFFICIAL] LineageOS 14.1 for Redmi 4A [06/04/2018]
[...]
[ROM][16.0][OFFICIAL][Non-RDP][Rolex/Riva] crDroid 12.x
[...]
[ROM][PORT][8.1.0] Samsung Experience 9.5 for Redmi 4A (ROLEX)
[...]
[RECOVERY] [OFFICIAL] TWRP 3.2.1-0 for Xiaomi Redmi 4A [rolex] [20171210]
[...]
[KERNEL][P/9-Q/10] GoGreen Rolex[HM4A]
[...]
[ROM][15.0][OFFICIAL][Non-RDP][Rolex/Riva] crDroid 11.x
[...]
[UNOFFICIAL][RECOVERY][Rolex/Riva] OrangeFox Recovery Project [12/06/22] [R11.1_1][FDE+FBE]
[...]
[ROM][10.0][rolex] Pixel Experience [AOSP][2019/12/26][DISCONTINUED]
[...]
[ROM][11][ROLEX/RIVA] PixelExperience [AOSP] [UNOFFICIAL]
[...]
[ROM][8.1.0_r52][OFFICIAL] AospExtended ROM V5.8 for Redmi 4A/5A [ROLEX/RIVA]
[...]
[ROM][9.0][rolex] Pixel Experience [AOSP][2019/12/12][DISCONTINUED]
[...]
[ROM][14.0][OFFICIAL][Non-RDP][Rolex/Riva] crDroid 10.x
[...]
[ROM][13.0][OFFICIAL][Rolex/Riva] crDroid 9.x
[...]
[UNIFIED][RIVA][ROLEX][ROM][OFFICIAL][STABLE] DotOS 2.3
[...]
Triton-kernel [EAS] [Treble] [android-10^][4.9] [Redmi4A | Redmi5A]
[...]
[Kernel]CafOCProject Pie Based M kernel [Discontinued]

---

Title: Cardinal - AOSP 8.1 rolex (4A)&nbsp;-&nbsp;MIUI CZ&amp;SK
URL: https://www.miuios.cz/cardinal-aosp-8-1-rolex-4a-24006
Published: N/A
Author: MIUI CZECH & SLOVAK | www.miuios.cz
Highlights:
Cardinal - AOSP 8.1 rolex (4A) - MIUI CZ&SK
[...]
### Cardinal - AOSP 8.1 rolex (4A)
[...]
Redmi 4A [rolex] / Redmi 4 [prada] / Redmi 4 Prime [markw] / Redmi 4X [santoni]
[...]
### Cardinal - AOSP 8.1 rolex (4A)
[...]
Zkouším tuhle ROM Pre zobrazenie URL sa musíte prihlásiť (TWRP, gapps a Magisk 16.4) pro 4A a zatím téměř absolutní spokojenost včetně výdrže. (TWRP) Jinak jsem poslední dobou (hlavně s 5A, které je ještě o poznání slabší než 4A ve všech směrech) vypozoroval testováním prazvláštní věc a sice, že Global ROM mi vydrží o hodně více baterie než místní EU verze (U Redmi 3 jsem flashoval rok a půl každý týden a neměl jsem problém),smysl mi to moc nedává,ale je to,alespoň umých founů, fakt. Bordel dělá hlavně to 5A, co se 4A týče, které mám čerstvě, tam se poslední weekly 9.6 odtud chovala velmi dobře!! Bootloader se mi odemkl na můj xiaomi účet ihned (narozdíl od 5A, kde jsem čekal s tímtéž 3 týdny!). Takže suma sumárum - v této cenové hladině (tzn. té nejnižší - 2100Kč :) ) - s rolexem velká spokojenost.
```

**Tool: websearch**

**Input:**
```json
{
  "query": "best kernel Redmi 4A rolex battery life performance custom ROM",
  "numResults": 8
}
```

**Output:**
```
Title: Infinity Kernel
URL: https://teaminfinity.github.io/
Published: N/A
Author: N/A
Highlights:
### A custom kernel for both Xiaomi Redmi 4A and Xiaomi Redmi 5A.
[...]
Infinity Kernel is a custom kernel for Xiaomi Redmi 4A and Xiaomi Redmi 5A.
[...]
It's main goal is to maintain a good battery life without sacrificing (if not improving) performance.
[...]
Xiaomi Redmi 5A users need not to worry. They can just use the one that says Redmi 5A.
[...]
For Redmi 4A users, here are the details:
[...]
Fabian uses different drivers than Murali's drivers.
[...]
If you are using: a Treble ROM Any AEX version that has a version number equal or higher than 20180602 or the LineageOS 15.1 that is published on XDA, use the Fabian version.
[...]
Any other ROM/If you aren't sure, try the Murali one first. If it doesn't boot, try the Fabian one.
[...]
Stable 15.1M FOR OREO - FOR REDMI 4A (MURALI TREE) Stable v5.1F FOR OREO - FOR TREBLE + REDMI 5A AND REDMI 4A (FABIAN TREE) Stable 5.5 FOR NOUGAT - FOR REDMI 4A - MIUI NOT SUPPORTED
[...]
These versions only support Xiaomi Redmi 4A.
[...]
Stable v5 FOR OREO - FOR TREBLE + REDMI 5A AND REDMI 4A (FABIAN TREE) Stable 15M FOR OREO - FOR REDMI 4A (MURALI TREE) Stable v3.7 FOR OREO - FOR TREBLE + REDMI 5A AND REDMI 4A (FABIAN TREE) Stable 14M FOR OREO - FOR REDMI 4A (MURALI TREE) Stable v3.6 FOR OREO - FOR TREBLE + REDMI 5A AND REDMI 4A (FABIAN TREE) Stable v3.5 FOR OREO - FOR TREBLE + REDMI 5A AND REDMI 4A (FABIAN TREE) Beta 13.1M FOR OREO - FOR REDMI 4A (MURALI TREE) Stable 13M for Oreo FOR OREO - FOR REDMI 4A (MURALI TREE) Test 1 for Oreo FOR OREO - FOR REDMI 4A (MURALI TREE TEST VERSION) Stable v3.4 FOR OREO - FOR TREBLE + REDMI 5A AND REDMI 4A (FABIAN TREE) Stable v3.2 FOR OREO - FOR TREBLE + REDMI 5A AND REDMI 4A (FABIAN TREE) Stable v3.1 FOR OREO - FOR TREBLE + REDMI 5A AND REDMI 4A (FABIAN TREE) Stable v3 FOR OREO - FOR TREBLE + REDMI 5A AND REDMI 4A (FABIAN TREE) Stable v2 FOR OREO - FOR TREBLE + REDMI 5A AND REDMI 4A (FABIAN TREE) Test Build 12.2M for Oreo FOR OREO - MURALI Test Build 12.1M for Oreo FOR OREO - MURALI Test Build 12M for Oreo FOR OREO - MURALI Test Build 9.7F for Oreo FOR OREO - FABIAN / TREBLE V1 Test Build 11M for Oreo FOR OREO - MURALI Test Build 9.9.7.6M for Oreo FOR OREO - MURALI Test Build 9.9.7M for Oreo FOR OREO - MURALI Test Build 9.9.6M for Oreo FOR OREO - MURALI Test Build 9.9.5M for Oreo FOR OREO - MURALI Test Build 9.9.3M for Oreo FOR OREO - MURALI Test Build 9.9.2M for Oreo FOR OREO - MURALI Test Build 9.9M for Oreo FOR OREO - MURALI Test Build 9.8M for Oreo FOR OREO - MURALI Test Build 9.7M for Oreo FOR OREO - MURALI Test Build 9.2F for Oreo FOR OREO - FABIAN Test Build 9.3M for Oreo FOR OREO - MURALI Test Build 9.1F for Oreo FOR OREO - FABIAN Test Build 6 for Oreo FOR OREO Test Build 5 for Oreo FOR OREO Test Build 4 for Oreo FOR OREO Test Build 3 for Oreo FOR OREO Version 5.0 FOR NOUGAT Version 4.5 FOR NOUGAT Version 4.0 FOR NOUGAT Version 3.2 FOR NOUGAT

---

Title: Xiaomi Redmi 4a ROMs, Kernels, Recoveries, & Other
URL: https://xdaforums.com/f/xiaomi-redmi-4a-roms-kernels-recoveries-other.7304
Published: 2017-12-29T00:00:00.000Z
Author: N/A
Highlights:
**
3D PrintingAndroid AutoAndroid ModsAndroid TVApps & GamesThemesWear OSSmartwatchesWindows 11XDA Computing
[...]
* Terms and rules
* Privacy
* Security
You are using an out of date browser. It may not display this or other websites correctly.
You should upgrade or use analternative browser.
# Xiaomi Redmi 4a ROMs, Kernels, Recoveries, &amp; Other
Improve your Xiaomi Redmi 4a's battery life, performance, and look by rooting it and installing a custom ROM, kernel, and more.
* **Home
* Forums
* Xiaomi
* Xiaomi Redmi 4a
•••
#### Breadcrumb
* **Home
* Forums
* Xiaomi
* Xiaomi Redmi 4a
Filters
#### Show only:
Loading…
###
[...]
[ROM][PORT][8.1.0] Samsung Experience 9.5 for Redmi 4A (ROLEX)
* blacklisted.rock
* Jan 15, 201923
Replies43
Views28K
[...]
✭imnotfish✭
Monday at 4:07 PM
✭imnotfish✭
darshan1205
[RECOVERY] [OFFICIAL] TWRP 3.2.1-0 for Xiaomi Redmi 4A [rolex] [20171210]
* darshan1205
* Mar 20, 2017567
Replies131
Views188K
[...]
Sep 3, 2025
[...]
bendang90
DevilUsr
[KERNEL][P/9-Q/10] GoGreen Rolex[HM4A]
* DevilUsr
* Jan 22, 202023
Replies56
Views15K
[...]
electronic\_dream
[...]
iusmac
[ROM][15.0][OFFICIAL][Non-RDP][Rolex/Riva] crDroid 11.x
* iusmac
* Feb 13, 2025
Replies7
Views4K
[...]
iliolerkes
[...]
iusmac
[UNOFFICIAL][RECOVERY][Rolex/Riva] OrangeFox Recovery Project [12/06/22] [R11.1\_1][FDE+FBE]
* iusmac
* Jun 14, 2022
Replies14
[...]
Views12
[...]
0vaP
[...]
dandyfarid
[ROM][10.0][rolex] Pixel Experience [AOSP][2019/12/26][DISCONTINUED]
* dandyfarid
* Nov 23, 2019101112
Replies223
Views57K
[...]
STMondal
Thago
[ROM][11][ROLEX/RIVA] PixelExperience [AOSP] [UNOFFICIAL]
* Thago
* Feb 13, 2021
Replies16
Views14K
[...]
$
ECr34T1v3
[ROM][8.1.0\_r52][OFFICIAL] AospExtended ROM V5.8 for Redmi 4A/5A [ROLEX/RIVA]
* ECr34T1v3
* May 1, 2018343536
Replies703
Views130K
[...]
dandyfarid
* **Poll
[ROM][9.0][rolex] Pixel Experience [AOSP][2019/12/12][DISCONTINUED]
* dandyfarid
* Apr 10, 2019242526
Replies503
Views96K
[...]
Dimas Hideyoshi
iusmac
[ROM][14.0][OFFICIAL][Non-RDP][Rolex/Riva] crDroid 10.x
* iusmac
* May 1, 2024
Replies5
Views5K
[...]
brinerustle
[...]
iusmac
[ROM][13.0][OFFICIAL][Rolex/Riva] crDroid 9.x
* iusmac
* Oct 31, 20222
Replies35
Views20K
[...]
[UNIFIED][RIVA][ROLEX][ROM][OFFICIAL][STABLE] DotOS 2.3
* GuestD2807
* Jun 12, 201823
Replies43
Views24K
[...]
Thago
Triton-kernel [EAS] [Treble] [android-10^][4.9] [Redmi4A | Redmi5A]
* Thago
* Apr 3, 202023
Replies50
Views14K
[...]
024
[...]
tantos8
[...]
DevilUsr
[Kernel]CafOCProject Pie Based M kernel [Discontinued]
* DevilUsr
* May 14, 20192
Replies23
Views5K
[...]
ka91pp
[...]
adi153
[[ROM][10.0]REDMI 4A] Pixel Experience Plus Unofficial [AOSP][rolex]](https://xdaforums.com/t/rom-10-0-redmi-4a-pixel-experience-plus-unofficial-aosp-rolex.4079399/)
* adi153
* Apr 8, 20202
Replies29
Views32K
[...]
27,
[...]
024
[...]
garembe
Thago
[ROM][OFFICIAL] Nitrogen-OS [11] [ROLEX/RIVA]
* Thago
* Dec 16, 20202
Replies25
Views15K

---

Title: [ROLEX/RIVA] [KERNEL] [OREO/NOUGAT] Infinity Kernel
URL: https://xdaforums.com/t/rolex-riva-kernel-oreo-nougat-infinity-kernel.3798817/
Published: 2018-06-02T15:55:41.000Z
Author: caghandemir
Highlights:
* **
* #1
[...]
3ed7aa4fb.jpg
The Infinity Kernel is a custom kernel for Redmi 4A (rolex) and Redmi 5A (riva).
For Redmi 4A and Redmi 5A, from Team Infinity!
**Based on Fabian's device tree, only to be used on ROMs compiled with Fabian's device tree + Treble.**
Code:
[...]
**Configuring the kernel:**
[...]
Please use "alucard" governor instead of "interactive".
Other than that, we can't give any other advice. We already have our recommendations set as default.
[...]
**OREO VERSION:**
[...]
"ondemand" CPU governor is pretty broken but it shouldn't be used anyway.**"interactive" is the way to go.**
[...]
We couldn't find any other, tell us if you do!
[...]
**Changelog:**
[...]
Contributors**
caghandemir,#Malpa73,SouradeepB, Yousef Algadri, Muralidharan Kumaresan, Myroynaldig, Ryan Andri, Carlos Arriaga, Aryan, MacTavish, Wzedlare
[...]
**Source Code:**https://github.com/TeamInfinity/Infinity\_Kernel\_FN
**Kernel Special Features:**Alucard hotplug, exFAT and NTFS Support, Overclock up to 1.61GHz, charging upto 2A.
[...]
**Version Information**
**Status:**Stable
**Current Stable Version:**v2
**Stable Release Date:**2018-06-02
**Created**2018-06-02
**Last Updated**2018-06-02
[...]
**Reactions:
[...]
> > Fresh flash, no kernel setups, default settings; interactive governor + alucard hotplug + cfq as I/O sched with 128kb readahead + max/min cpu at 1651/960 MHz, gpu max/min at stock values + 400Mhz initial gpu speed.
[...]
Better battery life for sure, you won't even feel the difference in battery life. Performancewise, if you change the governor to alucard, plus tweak more settings (change I/O sched to zen) you'll get more juice and response, than stock ootb settings which suffers from staggering and slow response.
[...]
Batterywise and temperature wise, I feel it's better than stock.
[...]
Kernel v5.5 for
[...]
working great on Riva running cr droid 3.8 nogut
[...]
Only 2 bugs , battery always shows 100%and charging
[...]
Reverted back to v2. v3.1 had issues on performance. Super slow response, staggering here and there, choppy multitasking when switching from one app to another, plus slow gaming performance (which didn't happen on v2). Even unlocking the device from screen off (the moment where the pattern dots shows) suffers stagger.
[...]
Governor: alucard (tried interactive with manual settings
[...]
Hotplug: alucard (tried turning it off
[...]
Max CPU freq: 1651 Mhz
[...]
Min CPU freq: 200 Mhz (tried returning it to stock min, no changes)
[...]
I/O sched: cfq (tried zen
[...]
Wi-Fi
[...]
> > crDroid is based on ChalapathiRevanth's tree, not Fabian's. That's why you're facing lags and a LED issue. For now, Redmi 5A users can only use Infinity Kernel on Fabian's tree (Treble included). We may release a version for ChalapathiRevanth's tree in the future, but not now.
[...]
The Infinity Kernel is a custom kernel for Redmi 4A (rolex) and Redmi 5A (riva).
[...]
For Redmi 4A and Redmi 5A, from Team Infinity!
[...]
**Based on Fabian's device tree, only to be used on ROMs compiled with Fabian's device tree + Treble.**
[...]
"ondemand" CPU governor is pretty broken but it shouldn't be used anyway.**"interactive" is the way to go.**
[...]
> Yeah I guessed so, I tested turning on Simple GPU, then Adreno Idler with interactive as CPU governor and in 2 hours of being idle, I woke up my 5A and suddenly the performance dropped rock bottom to the point where I couldn't open Kernel Adiutor to deactivate them, which ended on me force rebooting my phone (holding power button, which I don't like to do because it has it'
[...]
> > If you flashed a ROM that's UNIFIED for 4A and 5A, it defintely means it's a (semi) Treble ROM. You can use Infinity Kernel on it.
[...]
A pure Treble ROM is where you've flashed a GSI (Generic System Image) or GSI zip that you've downloaded in the Treble dev section threads.
[...]
For 5A, to be able to use pure treble (not semi treble), you must flash the UNIFIED vendor partition created by 33bca inthisthread.

---

Title: [KERNEL][ROLEX][Aosp-Miui][7.1.x-up] Night-Core kernel for Redmi 4a
URL: https://xdaforums.com/t/kernel-rolex-aosp-miui-7-1-x-up-night-core-kernel-for-redmi-4a.3832828/
Published: 2018-08-23T05:56:15.000Z
Author: Vony C
Highlights:
Night-Core kernel for
[...]
eRZEBDN.jpg
**Night-Core kernel for Redmi 4A**
**Numpang ngeshare pak**​
**I am not responsible for bricked devices, dead sd cards, explosions, nuclear wars, alarm applications getting failed, pleaseread the first 3 posts (features, faq, settings) carefullybefore flashing this kernel to make sure everything goes well with your installation.
This kernel will focus onquality over quantity, I will add only those features which don't cause instability and really improve performance or battery life of our device. I like to test my changes properly before release and keepstability the topmost priority, I don't guarantee weekly or nightly builds, updates will be given whenever required.
**
**Some Kernel Features**
**Features**
* Compile Gcc 7.2.x
* Overclocked Cpu to3878Mhz
* Tune-up Bus : Cpu-Gpu-memory
* Cpu boost and input boost
* Better battery life and performance
* Wireguard support
* Supports spectrum profiles
* Boeffla wakelock blocker
* Overclocking and underclocking
* Overclocked Display
* Disabled CRC check for better io
* lz4 & lz0 compression support available
* DTS eagle(New driver)
* msm ultra sound and tweakings
* NTFS, exFAT, F2FS, EXT filesystems support
* Fixed wrong gpu frequency reflected in sysfs
* Adding Octa-core,dual-core driver
* Adding 9 TCP
* Works on Unified Rom based on Fabian's trees And Miui rom
* Msm hotplug
**Requirements**
* Must be on Pie-Oreo based ROM based on Fabian's Unified Tree
* Miui Global stable (miuipro,stock rom,miui eu etc)
**How to flash**
[...]
* Boot into recovery mode
* Select zip kernel
* Flash the zip
* Reboot
[...]
DOWNLOAD LINKS REMOVED BY MOD UNTIL KERNEL SOURCE IS AVAILABLE
**Credits and thanks**
[...]
will it work for
[...]
ui 10 global ?
[...]
Freezing after boot
[...]
[RECOVERY] [OFFICIAL] TWRP 3.2.1-0 for Xiaomi Redmi 4A [rolex] [20171210]
[...]
darshan1205
[...]
* Mar 20, 2017
[...]
Replies130
[...]
ECr34T1v3
[...]
[ROM][8.1.0\_r52][OFFICIAL] AospExtended ROM V5.8 for Redmi 4A/5A [ROLEX/RIVA]
* ECr34T1v3
* May 1, 2018343536
Replies703
[...]
Views124K
[...]
ECr34T1v3
[ROM][9.0.0\_r46][OFFICIAL] AospExtended ROM V6.7 for Redmi 4A [ROLEX]
* ECr34T1v3
* Nov 14, 2018111213
Replies245
[...]
Vony C**
[...]
eRZEBDN.jpg
[...]
**Night-Core kernel for Redmi 4A**
**Numpang ngeshare pak**​
**I am not responsible for bricked devices, dead sd cards, explosions, nuclear wars, alarm applications getting failed, pleaseread the first 3 posts (features, faq, settings) carefullybefore flashing this kernel to make sure everything goes well with your installation.
This kernel will focus onquality over quantity, I will add only those features which don't cause instability and really improve performance or battery life of our device. I like to test my changes properly before release and keepstability the topmost priority, I don't guarantee weekly or nightly builds, updates will be given whenever required.
**
**Some Kernel Features**
**Features**
* Compile Gcc 7.2.x
* Overclocked Cpu to3878Mhz
* Tune-up Bus : Cpu-Gpu-memory
* Cpu boost and input boost
* Better battery life and performance
* Wireguard support
* Supports spectrum profiles
* Boeffla wakelock blocker
* Overclocking and underclocking
* Overclocked Display
* Disabled CRC check for better io
* lz4 & lz0 compression support available
* DTS eagle(New driver)
* msm ultra sound and tweakings
* NTFS, exFAT, F2FS, EXT filesystems support
* Fixed wrong gpu frequency reflected in sysfs
* Adding Octa-core,dual-core driver
* Adding 9 TCP
* Works on Unified Rom based on Fabian's trees And Miui rom
* Msm hotplug
**Requirements**
* Must be on Pie-Oreo based ROM based on Fabian's Unified Tree
* Miui Global stable (miuipro,stock rom,miui eu etc)
**How to flash**
[...]
* Boot into recovery mode
* Select zip kernel
* Flash the zip
* Reboot
[...]
DOWNLOAD LINKS REMOVED BY
[...]
KERNEL SOURCE IS

---

Title: [EOL][KERNEL] [ROLEX] Teamlions-Extended  For Xiaomi Redmi 4A [OREO/PIE] | XDA Forums
URL: https://xdaforums.com/t/eol-kernel-rolex-teamlions-extended-for-xiaomi-redmi-4a-oreo-pie.3905727/
Published: 2019-02-28T17:35:25.000Z
Author: N/A
Highlights:
Teamlions-Extended Kernel is a basic common kernel with some useful basic features based on FrancoKernel source for Xiaomi Redmi 4A by teamlions. Our kernel support both android oreo and pie Features:- * Added interactivex governor * Added dancedance governor * Added nightmare governor * Enabled 300HZ timer for better performance and battery backup * Added adreno idle support * optimized wakelock and deepsleep * Added state notifier support * optimized booting time * backported smb358-charger driver from ido ( 10% otg and charging speed improvement ) * optimized display driver * Builded with latest linaro 7.3.x Gcc . ( For better performance) . * Legendary battery life * Bypasses the verified boot flag for Android Pay compatibility. * Idle power consumption reduced to the absolute minimum (if you have wakelocks from 3rd party apps you're obviously on your own) * Added power EFFICIENT driver (Saves more battery life) * Added WIREGUARD driver (good internet connectivity) * Optimized Cpufreq * Added back Sound control driver(boost your speaker audio level) * Updated Wakelock blocker driver * Optimized performance * Improved Bluetooth connectivity * memory Management improvement * Optimized interactive gov * Optimized display & graphics * Optimized Zram * Enabled Xbox, logitech, analogue Joystick Support * Qnovo Quick charging Support * Ported land led driver (better led indicactor for all rolex variants) * Under clock cpu to 200mhz supported * No overlocked cpu . so safe to use our kernel as daily driver And much more check our kernel commits changes https://github.com/Teamlions/android_kernel_Teamlions-extended.git Downloads : sourceforge XDA:DevDB Information Teamlions-Extended, Kernel for the Xiaomi Redmi 4a Contributors muralivijay, franciscofranco Kernel Special Features: Version Information Status: Beta Current Beta Version: 0.1 Beta Release Date: 2019-02-27 Created 2019-02-28 Last Updated 2019-12-20
[...]
our smb358 sets
[...]
and battery blasting . So
[...]
phone charge will
[...]
Teamlions-Extended Kernel is a basic common kernel with some useful basic features based on FrancoKernel source for Xiaomi Redmi 4A by teamlions. Our kernel support both android oreo and pie Features:- * Added interactivex governor * Added dancedance governor * Added nightmare governor * Enabled 300HZ timer for better performance and battery backup * Added adreno idle support * optimized wakelock and deepsleep * Added state notifier support * optimized booting time * backported smb358-charger driver from ido ( 10% otg and charging speed improvement ) * optimized display driver * Builded with latest linaro 7.3.x Gcc . ( For better performance) . * Legendary battery life * Bypasses the verified boot flag for Android Pay compatibility. * Idle power consumption reduced to the absolute minimum (if you have wakelocks from 3rd party apps you're obviously on your own) * Added power EFFICIENT driver (Saves more battery life) * Added WIREGUARD driver (good internet connectivity) * Optimized Cpufreq * Added back Sound control driver(boost your speaker audio level) * Updated Wakelock blocker driver * Optimized performance * Improved Bluetooth connectivity * memory Management improvement * Optimized interactive gov * Optimized display & graphics * Optimized Zram * Enabled Xbox, logitech, analogue Joystick Support * Qnovo Quick charging Support * Ported land led driver (better led indicactor for all rolex variants) * Under clock cpu to 200mhz supported * No overlocked cpu . so safe to use our kernel as daily driver And much more check our kernel commits changes https://github.com/Teamlions/android_kernel_Teamlions-extended.git Downloads : sourceforge XDA:DevDB Information Teamlions-Extended, Kernel for the Xiaomi Redmi 4a Contributors muralivijay, franciscofranco Kernel Special Features: Version Information Status: Beta Current Beta Version: 0.1 Beta Release Date: 2019-02-27 Created 2019-02-28 Last Updated 2019-12-20

---

Title: [DISCONTINUED][KERNEL][RIVA][ROLEX] DireWolf Unified kernel - Redmi 5A and Redmi 4A | XDA Forums
URL: https://xdaforums.com/t/discontinued-kernel-riva-rolex-direwolf-unified-kernel-redmi-5a-and-redmi-4a.3824182/
Published: 2018-08-02T14:06:42.000Z
Author: N/A
Highlights:
About DireWolf Kernel DireWolf Kernel is a new kernel and it works on both Redmi 4A and 5A. It is developed to give the maximum in every aspect of the device. I added governors, i/o schedulers, various other things to get the maximum out of the device. It supports spectrum profiles and also has a lot of other stuffs that tweakers like.
[...]
- Linux version 3.18.116
- Unified for 4A and 5A
- Better battery life and performance
- Wireguard support
- Supports spectrum profiles
- Boeffla wakelock blocker
- Overclocking and underclocking
- Overclocked Audio processor
- Overclocked Slimbus
- Disabled CRC check for better io
- Snappy compression and decompression
- DTS eagle(New driver)
- Overall sound tweakings
[...]
- Governors: Electron, alucard, conservative, ondemand, userspace, interactive, powersave, lionheart, lionfish, performance
- I/O schedulers: Maple(default), zen, noop, deadline, cfq, bfq
- TCP congestion algorithm : cubic, reno, westwood(default), bic, htcp, highspeed, vegas, veno, scalable, lp, yeah, illinois
- Works on Unified ROMs based on Fabian's trees
- AutoSMP hotplug
[...]
- Must be on Oreo based ROM based on Fabian's Unified Tree
- A custom recovery (TWRP) should be installed
[...]
About DireWolf Kernel DireWolf Kernel is a new kernel and it works on both Redmi 4A and 5A. It is developed to give the maximum in every aspect of the device. I added governors, i/o schedulers, various other things to get the maximum out of the device. It supports spectrum profiles and also has a lot of other stuffs that tweakers like.
[...]
- Linux version 3.18.116
- Unified for 4A and 5A
- Better battery life and performance
- Wireguard support
- Supports spectrum profiles
- Boeffla wakelock blocker
- Overclocking and underclocking
- Overclocked Audio processor
- Overclocked Slimbus
- Disabled CRC check for better io
- Snappy compression and decompression
- DTS eagle(New driver)
- Overall sound tweakings
[...]
- Governors: Electron, alucard, conservative, ondemand, userspace, interactive, powersave, lionheart, lionfish, performance
[...]
- I/O schedulers: Maple(default), zen, noop, deadline, cfq, bfq
[...]
- TCP congestion algorithm : cubic, reno, westwood(default), bic, htcp, highspeed, vegas, veno, scalable, lp, yeah, illinois
[...]
- Works on Unified ROMs based on Fabian's trees
[...]
- AutoSMP hot
[...]
- Must be on Oreo based ROM based on Fabian's Unified Tree
- A custom recovery (TWRP) should be installed
[...]
DireWolf Version 7 update for Riva and Rolex Merged latest Linux Stable Linux 3.18.131 and CAF tag LA.UM. 7.6.r1-03700-89xx.0. ● Heavily debloated and removed unnecessary features. ● Added Input Boost. ● Added Built-in KCAL Screen profiles, accessible from Kernel Adiutor. ● Improved and adaptable Low Memory Killer. ● Improved architecture specific oriented usage. ● Tuned Low Memory Killer for slightly better battery without compromising performance. ● Improvement on LTE battery usage. ● GPU overclocked to 653MHz. ● GPU underclocked to 19MHz(only on idle). ● Added Simple GPU algorithm. Direwolf 7 Unified
[...]
. I'm not
[...]
though. The only significant
[...]
I've done is just set
[...]
200, deactivated CC
[...]
control), turned
[...]
LordShenron
[...]
) and now we have westwood (total
[...]
, I don'
[...]
, but when I
[...]
the read_wakeup_threshold to 80 (def
[...]
64) it
[...]
my 5A a lil. Haven't seen major difference in Dire though, maybe it's not needed, but still I'm holding
[...]
to 80
[...]
if this is right (havent
[...]
) but I
[...]
Yes AutoSMP is little bit harsh. I also found it makes device wakeup a difficult task. But since i found its quite efficient in battery saving so i kept it. Now the choppy sound will most likely be fixed if u add some speaker gain (as i tested). And for the death sleep i think autosmp after wakeup doesn't let the cpus come online, so if after wakeup all cpus come online at the higest frequency there will be no issues. I will test this soon.

---

Title: NgntdKernel, Kernel for the Xiaomi Redmi 4A and Xiaomi Redmi 5A | XDA Forums
URL: https://xdaforums.com/t/ngntdkernel-kernel-for-the-xiaomi-redmi-4a-and-xiaomi-redmi-5a.3882261/
Published: 2018-12-24T02:42:11.000Z
Author: N/A
Highlights:
About NgntdKernel NgntdKernel is a new kernel and it works on both Redmi 4A and 5A. It is developed to give the maximum in every aspect of the device. I added governors, i/o schedulers, various other things to get the maximum out of the device. It has a lot of other stuffs that tweakers like.
[...]
- Arch power and Arch
[...]
- Works on Unified ROMs based on Fabian's trees
[...]
- Tuned Interactive CPU Governor for better performance
[...]
- Audio processor Overclock to 12.228MHz!
[...]
- GPU Overclocking max 650MhZ!
[...]
- CPU Underclocking min 200MhZ!
- CPU Overclocking max 1.6GhZ!
- Better battery life and performance
[...]
- Unified for Redmi 4A and Redmi 5A
[...]
- A custom recovery (TWRP) should be installed
[...]
- Must be on Oreo or Pie Treble or Non-Treble based on Fabian's Unified Tree.
[...]
only work in custom rom oreo and pie unified tree
[...]
Good! One of the best kernel ever for Redmi 4A (Rolex) :good:
[...]
I tested Antutu using his Kernel and Simontek (okay, I'll ignore Xolos, horrible performance). Your Kernel made 40k versus 44k Simontek's in game mode via Spectrum. I remember that MIUI9 with custom Kernel made something around 37k. One thing that calls attention to even the Antutu is the Memory performance of Simontek, surpassing 6k in isolation and receiving warning of the program about abnormal performance. Your kernel outperforms the CPU rival by a considerable margin, loses in all other tests. Ps.: ROM AEX PIE. Redmi 4a with 2 GB RAM.
[...]
I tested Antutu using his Kernel and Simontek (okay, I'll ignore Xolos, horrible performance). Your Kernel made 40k versus 44k Simontek's in game mode via Spectrum. I remember that MIUI9 with custom Kernel made something around 37k. One thing that calls attention to even the Antutu is the Memory performance of Simontek, surpassing 6k in isolation and receiving warning of the program about abnormal performance. Your kernel outperforms the CPU rival by a considerable margin, loses in all other tests. Ps.: ROM AEX PIE. Redmi 4a with 2 GB RAM.
[...]
I tested Antutu using his Kernel and Simontek (okay, I'll ignore Xolos, horrible performance). Your Kernel made 40k versus 44k Simontek's in game mode via Spectrum. I remember that MIUI9 with custom Kernel made something around 37k. One thing that calls attention to even the Antutu is the Memory performance of Simontek, surpassing 6k in isolation and receiving warning of the program about abnormal performance. Your kernel outperforms the CPU rival by a considerable margin, loses in all other tests. Ps.: ROM AEX PIE. Redmi 4a with 2 GB RAM.
[...]
I tested Antutu using his Kernel and Simontek (okay, I'll ignore Xolos, horrible performance). Your Kernel made 40k versus 44k Simontek's in game mode via Spectrum. I remember that MIUI9 with custom Kernel made something around 37k. One thing that calls attention to even the Antutu is the Memory performance of Simontek, surpassing 6k in isolation and receiving warning of the program about abnormal performance. Your kernel outperforms the CPU rival by a considerable margin, loses in all other tests. Ps.: ROM AEX PIE. Redmi 4a with 2 GB RAM.
[...]
About NgntdKernel NgntdKernel is a new kernel and it works on both Redmi 4A and 5A. It is developed to give the maximum in every aspect of the device. I added governors, i/o schedulers, various other things to get the maximum out of the device. It has a lot of other stuffs that tweakers like.
[...]
- Works on Unified ROMs based on Fabian's trees
[...]
- Boeffla wakelock blocker
[...]
- Tuned Audio Codecs
[...]
Qnovo Interface
[...]
Westwood I/
[...]
as default I/O Scheduler
[...]
- Tuned Interactive CPU Governor for better performance
[...]
reno Idler
[...]
all TCP Congestion Algorithm
[...]
ed Slimbus
[...]
- Audio processor Overclock to 12.228MHz!
[...]
- GPU Overclocking max 650MhZ!
[...]
- CPU Underclocking min 200MhZ!
[...]
- CPU Overclocking max 1.6GhZ!
- Better battery life and performance
[...]
- Unified for Redmi 4A and Redmi 5A

---

Title: List of Redmi 4A (Rolex) Custom Roms | XDA Forums
URL: https://xdaforums.com/t/list-of-redmi-4a-rolex-custom-roms.3774162/
Published: 2018-04-06T13:31:33.000Z
Author: N/A
Highlights:
am just compiling a list of all the latest roms. Because the previous thread https
[...]
xdaforums.com
[...]
706
[...]
84 by sk
[...]
050 got discontinued. https
[...]
androidfilehost.com
[...]
w=developers&did
[...]
2684
[...]
the entire list
[...]
----------------------------------------------------------------------------------------------------------------
[...]
cam portrait working https
[...]
camera---------------------------------------------------------------------------------------------------------------- Project Treble XDA Thread----------------
[...]
OREO
[...]
: XDA Thread----------------
[...]
-------------------------------- CrDroid OREO
[...]
XDA Thread----------------
[...]
------------------------------------------------ AEX OREO
[...]
aospextended.com/rolex XDA Thread----------------
[...]
-------------------------------------------------------------------------------- Project Xtended OREO
[...]
XDA Thread
[...]
XDA Thread
[...]
Cardinal AOSP (OREO
[...]
XDA Thread
[...]
OREO
[...]
Nitrogen OS OREO
[...]
9.1
[...]
---------------------------------------------------------------- AOSCP
[...]
XDA Thread
[...]
r20
[...]
OFFICIAL] MoKee 81.0 for Redmi 4A
[...]
8.1.0
[...]
UNOFFICIAL] XDA Thread
[...]
1.0
[...]
] Sudamod 4.1
[...]
official XDA by Aryan
[...]
---------------- MiracleDROID 1.0
[...]
Bootleggers ROM
[...]
4.1
[...]
------------------------------------------------ Firehound OREO
[...]
UltraSuccROM ROM
[...]
----------------------------------------------------------------
[...]
UNOFFICIAL
[...]
AOSPA - Paranoid Android ROM Link---------------------------------------------------------------------------------------------------------------- [ROM][8.1][UNIFIED][OFFICIAL] ToxycOS for Redmi 4A/5A [1.0] XDA Thread ROM By Eric
[...]
------------------------------------------------------------------------------------------------ COSMIC OS OREO | UNOFFICIAL ROM Link Guide: Wipe, Flash Rom, flash Gapps, Flash Magisk, Reboot ---------------------------------------------------------------------------------------------------------------- CARBON CR 6.1 NOCT OREO [8.1.0_r26][CLANG] | UNOFFICIAL XDA By Carlos Guide: Wipe, Flash Rom, flash Gapps, Flash Magisk, Reboot ---------------------------------------------------------------------------------------------------------------- LineageOS 15.1 (Unofficial) by 33bca aka Offain XDA Thread---------------------------------------------------------------------------------------------------------------- AICP by Aryan OREO | UNOFFICIAL : XDA Thread---------------------------------------------------------------------------------------------------------------- DirtyUnicorns build by Murli | UNOFFICIAL ROM Link---------------------------------------------------------------------------------------------------------------- [ROM] [OREO] [UNOFFICIAL] Validus OS [STABLE] XDA Thread ROM Link---------------------------------------------------------------------------------------------------------------- Infinity Kernel for Oreo Roms: Flash Kernel https://xdaforums.com/redmi-4a/development/infinity-kernel
[...]
v3-2-redmi-4a-rolex-t3775549---------------------------------------------------------------------------------------------------------------- ---------------------------------------------------------------------------------------------------------------- Nougat ROMs: LineageOS Rom: https
[...]
androidfilehost
[...]
746010030569967699 CRDroid https
[...]
818
[...]
850
[...]
743 Viper OS https
[...]
Use AEX Extended, battery drain is amazing
[...]
Bootleggers proved best battery friendly and stable rom so far. Cheers
```

---

## Assistant (Plan · Big Pickle · 5.9s)

_Thinking:_

Let me search for more up-to-date information about the best recent ROMs for Redmi 4A, particularly Android 13/14/15 options, as there seem to be more recent crDroid builds available for this device.

**Tool: websearch**

**Input:**
```json
{
  "query": "Redmi 4A rolex best lightweight ROM Android 13 14 15 crDroid LineageOS 2025 2026",
  "numResults": 8
}
```

**Output:**
```
Title: [ROM][15.0][OFFICIAL][Non-RDP][Rolex/Riva] crDroid 11.x | XDA Forums
URL: https://xdaforums.com/t/rom-15-0-official-non-rdp-rolex-riva-crdroid-11-x.4718474/
Published: 2025-02-13T11:46:45.000Z
Author: N/A
Highlights:
[ROM][15.0][OFFICIAL][Non-RDP][Rolex/Riva] crDroid 11.x | XDA Forums
[...]
# [ROM][15.0][OFFICIAL][Non-RDP][Rolex/Riva] crDroid 11.x
[...]
crDroid is designed to increase performance and reliability over stock Android for your device also attempting to bringing many of the best features existent today. Features: https://github.com/crdroidandroid/crdroid_features/blob/15.0/README.mkdn Extra features (implemented by the maintainer): - Ability to disable touchscreen buttons - Audio amplification - WireGuard - KernelSU-NEXT (KSU-NEXT): A kernel-based root solution for Android (Get It here) - Clear Speaker - LED indicator on offline charging (0-10% = red+blink, 11-30% = red, 31-80% = blue, 81-99% = green, 100% = green+blink) - Mi Sound Enhancer - Properly calibrated sensor-based Doze mode - Advanced "Smart Charging" - Native support for "Ok Google" hotword feature - Native support for Google Phone call recording - FMRadio(with RDS support) - Reboot to Fastboot - Battery-friendly pocket mode- RAM+ feature - 7SIM app to control SIM cards based on your schedule Flashing Instructions: Install steps can be found on our device page https://crdroid.net/rova/11/install Sources: ROM: https://github.com/crdroidandroid Kernel: https://github.com/crdroidandroid/android_kernel_xiaomi_rova Download: ROM https://crdroid.net/rova/11 Changelog: https://crdroid.net/rova/11#changelog Known issues: You tell me Visit official website @ crDroid.net crDroid Device Group and Support Community Donate to help our team pay server costs
[...]
Just installed in my redmi 4A and gotta say, it's awesome. Tested it all, no bugs whatsoever, everything is working fine. Thank you guys.
[...]
(for 4A)
[...]
This is a unified ROM. rova is rolex (Redmi 4A) + riva (Redmi 5A).
[...]
Recently I intalled CRDroid 11.6 on my Redmi 4A and I have issue with display. After the phone is switched on everything is working fine
[...]
to unlock phone
[...]
Touch works because when sliding I hear unlocking sound.
[...]
I have issue with display too. The screen goes black after I lock the screen. I already try all Android 15 release from Feb 2025 and with no solution. Any workaround will be appreciated. The ROM is great IMHO. I will keep eye for an update. I will use Nusantara ROM (Android 13) for meanwhile.
[...]
[ROM][8.1.0_r52][OFFICIAL] AospExtended ROM V5.8 for Redmi 4A/5A [ROLEX/RIVA]
[...]
[ROM][OFFICIAL][OREO 8.1]crDroid v4.2[Redmi 4A][ROLEX][VOLTE]
[...]
[ROM][UNOFFICIAL] LineageOS 15.1 for Xiaomi Redmi 4A & 5A [UNIFIED][OTA]
[...]
crDroid is designed to increase performance and reliability over stock Android for your device also attempting to bringing many of the best features existent today. Features: https://github.com/crdroidandroid/crdroid_features/blob/15.0/README.mkdn Extra features (implemented by the maintainer): - Ability to disable touchscreen buttons - Audio amplification - WireGuard - KernelSU-NEXT (KSU-NEXT): A kernel-based root solution for Android (Get It here) - Clear Speaker - LED indicator on offline charging (0-10% = red+blink, 11-30% = red, 31-80% = blue, 81-99% = green, 100% = green+blink) - Mi Sound Enhancer - Properly calibrated sensor-based Doze mode - Advanced "Smart Charging" - Native support for "Ok Google" hotword feature - Native support for Google Phone call recording - FMRadio(with RDS support) - Reboot to Fastboot - Battery-friendly pocket mode- RAM+ feature - 7SIM app to control SIM cards based on your schedule Flashing Instructions: Install steps can be found on our device page https://crdroid.net/rova/11/install Sources: ROM: https://github.com/crdroidandroid Kernel: https://github.com/crdroidandroid/android_kernel_xiaomi_rova Download: ROM https://crdroid.net/rova/11 Changelog: https://crdroid.net/rova/11#changelog Known issues: You tell me Visit official website @ crDroid.net crDroid Device Group and Support Community Donate to help our team pay server costs
[...]
This is a unified ROM. rova is rolex (Redmi 4A) + riva (Redmi 5A).

---

Title: [ROM][14.0][OFFICIAL][Non-RDP][Rolex/Riva] crDroid 10.x | XDA Forums
URL: https://xdaforums.com/t/rom-14-0-official-non-rdp-rolex-riva-crdroid-10-x.4669734/
Published: 2024-05-01T10:07:17.000Z
Author: N/A
Highlights:
[ROM][14.0][OFFICIAL][Non-RDP][Rolex/Riva] crDroid 10.x | XDA Forums
[...]
# [ROM][14.0][OFFICIAL][Non-RDP][Rolex/Riva] crDroid 10.x
[...]
crDroid is designed to increase performance and reliability over stock Android for your device also attempting to bringing many of the best features existent today. Features: https://github.com/crdroidandroid/crdroid_features/blob/14.0/README.mkdn Extra features (implemented by the maintainer): - Ability to disable touchscreen buttons - Audio amplification - WireGuard - KernelSU (KSU): A kernel-based root solution for Android (Get It here) - Clear Speaker - LED indicator on offline charging (0-10% = red+blink, 11-30% = red, 31-80% = blue, 81-99% = green, 100% = green+blink) - Mi Sound Enhancer - Properly calibrated sensor-based Doze mode - Advanced "Smart Charging" - Native support for "Ok Google" hotword feature - Native support for Google Phone call recording - FMRadio(with RDS support) - Reboot to Fastboot - Battery-friendly pocket mode- RAM+ feature - 7SIM app to control SIM cards based on your schedule Flashing Instructions:
[...]
additional device-
[...]
for the ROM to work properly.
[...]
are some issues you may encounter
[...]
a unified rolex/riva ROM:
[...]
- Bluetooth dead (mainly on riva) - WiFi dead (the most frequent
[...]
The ROM is encrypted by default. This is a crDroid requirement! If you don't care about encryption, you can disable it within OrangeFox recovery: demonstration(you should see "Disable FBE" button instead)
[...]
Flash Android 7 (Nougat) based firmware
[...]
❗️The "Redmi 4A" users **SHALL** upgrade the firmware to the latest available. ❗️The "Redmi 5A" users **SHALL** absolutely avoid firmwares based on Android 8 (Oreo) and downgrade to the latest Android 7 (Nougat) based one.
[...]
Sources: ROM: https://github.com/crdroidandroid Kernel: https://github.com/crdroidandroid/android_kernel_xiaomi_rova Download: ROM https://crdroid.net/rova/10 Changelog: See here Known issues: You tell me Visit official website @ crDroid.net crDroid rova Telegram crDroid Community Telegram crDroid Updates Channel Donate to help our team pay server costs
[...]
crDroid is designed to increase performance and reliability over stock Android for your device also attempting to bringing many of the best features existent today. Features: https://github.com/crdroidandroid/crdroid_features/blob/14.0/README.mkdn Extra features (implemented by the maintainer): - Ability to disable touchscreen buttons - Audio amplification - WireGuard - KernelSU (KSU): A kernel-based root solution for Android (Get It here) - Clear Speaker - LED indicator on offline charging (0-10% = red+blink, 11-30% = red, 31-80% = blue, 81-99% = green, 100% = green+blink) - Mi Sound Enhancer - Properly calibrated sensor-based Doze mode - Advanced "Smart Charging" - Native support for "Ok Google" hotword feature - Native support for Google Phone call recording - FMRadio(with RDS support) - Reboot to Fastboot - Battery-friendly pocket mode- RAM+ feature - 7SIM app to control SIM cards based on your schedule Flashing Instructions:
[...]
- Bluetooth dead
[...]
Flash crDroid
[...]
The ROM is encrypted by default. This is a crDroid requirement! If you don't care about encryption, you can disable it within OrangeFox recovery: demonstration(you should see "Disable FBE" button instead)
[...]
Flash Android 7 (Nougat) based firmware
[...]
❗️The "Redmi 4A" users **SHALL** upgrade the firmware to the latest available. ❗️The "Redmi 5A" users **SHALL** absolutely avoid firmwares based on Android 8 (Oreo) and downgrade to the latest Android 7 (Nougat) based one.
[...]
Sources: ROM: https://github.com/crdroidandroid Kernel: https://github.com/crdroidandroid/android_kernel_xiaomi_rova Download: ROM https://crdroid.net/rova/10 Changelog: See here Known issues: You tell me Visit official website @ crDroid.net crDroid rova Telegram crDroid Community Telegram crDroid Updates Channel Donate to help our team pay server costs

---

Title: [ROM][16.0][OFFICIAL][Non-RDP][Rolex/Riva] crDroid 12.x | XDA Forums
URL: https://forum.xda-developers.com/t/rom-16-0-official-non-rdp-rolex-riva-crdroid-12-x.4762708/
Published: 2025-10-07T15:00:40.000Z
Author: N/A
Highlights:
[ROM][16.0][OFFICIAL][Non-RDP][Rolex/Riva] crDroid 12.x | XDA Forums
[...]
# [ROM][16.0][OFFICIAL][Non-RDP][Rolex/Riva] crDroid 12.x
[...]
- Thread starter iusmac
- Start date Oct 7, 2025
- Tags crdroid redmi 4a redmi 5a riva rolex rova
[...]
crDroid is designed to increase performance and reliability over stock Android for your device also attempting to bringing many of the best features existent today. Features: https://github.com/crdroidandroid/crdroid_features/blob/16.0/README.mkdn Extra features (implemented by the maintainer): - Ability to disable touchscreen buttons - Audio amplification - WireGuard - KernelSU-NEXT (KSU-NEXT): A kernel-based root solution for Android (Get It here) - SUSFS support: A KernelSU module for root hiding (Get v1.5.2+ here here) - Clear Speaker - LED indicator on offline charging (0-10% = red+blink, 11-30% = red, 31-80% = blue, 81-99% = green, 100% = green+blink) - Mi Sound Enhancer - Properly calibrated sensor-based Doze mode - Advanced "Smart Charging" - Native support for "Ok Google" hotword feature - Native support for Google Phone call recording - FMRadio(with RDS support) - Reboot to Fastboot - Battery-friendly pocket mode- RAM+ feature - 7SIM app to control SIM cards based on your schedule - Very low battery (<5%) notification Flashing Instructions: Install steps can be found on our device page https://crdroid.net/rova/12/install Sources: ROM: https://github.com/crdroidandroid Kernel: https://github.com/crdroidandroid/android_kernel_xiaomi_rova Download: ROM https://crdroid.net/rova/12 Changelog: https://crdroid.net/rova/12#changelog Known issues: You tell me Visit official website @ crDroid.net crDroid Device Group and Support Community Donate to help our team pay server costs
[...]
[ROM][8.1.0_r52][OFFICIAL] AospExtended ROM V5.8 for Redmi 4A/5A [ROLEX/RIVA]
[...]
[RECOVERY] [OFFICIAL] TWRP 3.2.1-0 for Xiaomi Redmi 4A [rolex] [20171210]
[...]
-[9.
[...]
[ROM][OFFICIAL][OREO 8.1]crDroid v4.2[Redmi 4A][ROLEX][VOLTE]
[...]
[ROM][UNOFFICIAL] LineageOS 15.1 for Xiaomi Redmi 4A & 5A [UNIFIED][OTA]
[...]
crDroid is designed to increase performance and reliability over stock Android for your device also attempting to bringing many of the best features existent today. Features: https://github.com/crdroidandroid/crdroid_features/blob/16.0/README.mkdn Extra features (implemented by the maintainer): - Ability to disable touchscreen buttons - Audio amplification - WireGuard - KernelSU-NEXT (KSU-NEXT): A kernel-based root solution for Android (Get It here) - SUSFS support: A KernelSU module for root hiding (Get v1.5.2+ here here) - Clear Speaker - LED indicator on offline charging (0-10% = red+blink, 11-30% = red, 31-80% = blue, 81-99% = green, 100% = green+blink) - Mi Sound Enhancer - Properly calibrated sensor-based Doze mode - Advanced "Smart Charging" - Native support for "Ok Google" hotword feature - Native support for Google Phone call recording - FMRadio(with RDS support) - Reboot to Fastboot - Battery-friendly pocket mode- RAM+ feature - 7SIM app to control SIM cards based on your schedule - Very low battery (<5%) notification Flashing Instructions: Install steps can be found on our device page https://crdroid.net/rova/12/install Sources: ROM: https://github.com/crdroidandroid Kernel: https://github.com/crdroidandroid/android_kernel_xiaomi_rova Download: ROM https://crdroid.net/rova/12 Changelog: https://crdroid.net/rova/12#changelog Known issues: You tell me Visit official website @ crDroid.net crDroid Device Group and Support Community Donate to help our team pay server costs

---

Title: [ROM][15.0][OFFICIAL][Non-RDP][Rolex/Riva] crDroid 11.x | XDA Forums
URL: http://forum.xda-developers.com/t/rom-15-0-official-non-rdp-rolex-riva-crdroid-11-x.4718474/
Published: 2025-02-13T11:46:45.000Z
Author: N/A
Highlights:
[ROM][15.0][OFFICIAL][Non-RDP][Rolex/Riva] crDroid 11.x | XDA Forums
[...]
# [ROM][15.0][OFFICIAL][Non-RDP][Rolex/Riva] crDroid 11.x
[...]
- Thread starter iusmac
- Start date Feb 13, 2025
- Tags crdroid redmi 4a redmi 5a riva rolex rova
[...]
crDroid is designed to increase performance and reliability over stock Android for your device also attempting to bringing many of the best features existent today. Features: https://github.com/crdroidandroid/crdroid_features/blob/15.0/README.mkdn Extra features (implemented by the maintainer): - Ability to disable touchscreen buttons - Audio amplification - WireGuard - KernelSU-NEXT (KSU-NEXT): A kernel-based root solution for Android (Get It here) - Clear Speaker - LED indicator on offline charging (0-10% = red+blink, 11-30% = red, 31-80% = blue, 81-99% = green, 100% = green+blink) - Mi Sound Enhancer - Properly calibrated sensor-based Doze mode - Advanced "Smart Charging" - Native support for "Ok Google" hotword feature - Native support for Google Phone call recording - FMRadio(with RDS support) - Reboot to Fastboot - Battery-friendly pocket mode- RAM+ feature - 7SIM app to control SIM cards based on your schedule Flashing Instructions: Install steps can be found on our device page https://crdroid.net/rova/11/install Sources: ROM: https://github.com/crdroidandroid Kernel: https://github.com/crdroidandroid/android_kernel_xiaomi_rova Download: ROM https://crdroid.net/rova/11 Changelog: https://crdroid.net/rova/11#changelog Known issues: You tell me Visit official website @ crDroid.net crDroid Device Group and Support Community Donate to help our team pay server costs
[...]
Just installed in my redmi 4A and gotta say, it's awesome. Tested it all, no bugs whatsoever, everything is working fine. Thank you guys.
[...]
riva' (for 5A) and
[...]
rolex' (for 4A) -
[...]
rova' is a
[...]
that we have to live with
[...]
This is a unified ROM. rova is rolex (Redmi 4A) + riva (Redmi 5A).
[...]
and I have issue with display
[...]
I have issue with display too. The screen goes black after I lock the screen. I already try all Android 15 release from Feb 2025 and with no solution. Any workaround will be appreciated. The ROM is great IMHO. I will keep eye for an update. I will use Nusantara ROM (Android 13) for meanwhile.
[...]
[ROM][8.1.0_r52][OFFICIAL] AospExtended ROM V5.8 for Redmi 4A/5A [ROLEX/RIVA]
[...]
[ROM][OFFICIAL][OREO 8.1]crDroid v4.2[Redmi 4A][ROLEX][VOLTE]
[...]
[ROM][UNOFFICIAL] LineageOS 15.1 for Xiaomi Redmi 4A & 5A [UNIFIED][OTA]
[...]
crDroid is designed to increase performance and reliability over stock Android for your device also attempting to bringing many of the best features existent today. Features: https://github.com/crdroidandroid/crdroid_features/blob/15.0/README.mkdn Extra features (implemented by the maintainer): - Ability to disable touchscreen buttons - Audio amplification - WireGuard - KernelSU-NEXT (KSU-NEXT): A kernel-based root solution for Android (Get It here) - Clear Speaker - LED indicator on offline charging (0-10% = red+blink, 11-30% = red, 31-80% = blue, 81-99% = green, 100% = green+blink) - Mi Sound Enhancer - Properly calibrated sensor-based Doze mode - Advanced "Smart Charging" - Native support for "Ok Google" hotword feature - Native support for Google Phone call recording - FMRadio(with RDS support) - Reboot to Fastboot - Battery-friendly pocket mode- RAM+ feature - 7SIM app to control SIM cards based on your schedule Flashing Instructions: Install steps can be found on our device page https://crdroid.net/rova/11/install Sources: ROM: https://github.com/crdroidandroid Kernel: https://github.com/crdroidandroid/android_kernel_xiaomi_rova Download: ROM https://crdroid.net/rova/11 Changelog: https://crdroid.net/rova/11#changelog Known issues: You tell me Visit official website @ crDroid.net crDroid Device Group and Support Community Donate to help our team pay server costs
[...]
This is a unified ROM. rova is rolex (Redmi 4A) + riva (Redmi 5A).

---

Title: crDroid.net - Download crDroid v9 for Redmi 4A/5A (rova)
URL: https://crdroid.net/rova/9
Published: N/A
Author: N/A
Highlights:
crDroid.net - Download crDroid v9 for Redmi 4A/5A (rova) 

 

## You are now ready to download and install crDroid 9 based on Android 13 for Redmi 4A/5A

Check below info to get started

Back to all devices download page
[...]
#### Aww snap!
[...]
This version of crDroid is outdated or no longer supported, so try to check for other versions.
[...]
If this version source is still updated and if you are interested to maintain it, read our F.A.Q page to get started
[...]
### crDroid for Redmi 4A/5A
[...]
| OEM | Redmi |
| --- | --- |
| Codename | rova |
| Version | 9.18 |
| Android | 13 |
| Build date | 2024-07-19 |
| ZIP size | 913.2 MB |
| Build type | Final |
[...]
###### crDroid downloads:
[...]
Download latest version Download older versions

---

Title: crDroid.net - Download crDroid v12 for Redmi 4A/5A (rova)
URL: https://crdroid.net/rova/12
Published: N/A
Author: N/A
Highlights:
crDroid.net - Download crDroid v12 for Redmi 4A/5A (rova) 

 

## You are now ready to download and install crDroid 12 based on Android 16 for Redmi 4A/5A

Check below info to get started

Back to all devices download page

 

### crDroid for Redmi 4A/5A
[...]
| OEM | Redmi |
| --- | --- |
| Codename | rova |
| Maintainer | Max |
| Nickname | iusmac |
| Version | 12.8 |
| Android | 16 |
| Build date | 2026-03-16 |
| ZIP size | 1.1 GB |
| Build type | Monthly |
[...]
###### crDroid downloads:
[...]
Download latest version Download older versions

---

Title: [ROM][14.0][OFFICIAL][Non-RDP][Rolex/Riva] crDroid 10.x | XDA Forums
URL: http://xdaforums.com/t/rom-14-0-official-non-rdp-rolex-riva-crdroid-10-x.4669720/
Published: 2024-05-01T09:29:06.000Z
Author: N/A
Highlights:
[ROM][14.0][OFFICIAL][Non-RDP][Rolex/Riva] crDroid 10.x | XDA Forums
[...]
# [ROM][14.0][OFFICIAL][Non-RDP][Rolex/Riva] crDroid 10.x
[...]
- Tags crdroid redmi 4a redmi 5a riva rolex rova
- Start date May 1, 2024
- Thread starter iusmac
[...]
crDroid is designed to increase performance and reliability over stock Android for your device also attempting to bringing many of the best features existent today. Features: https://github.com/crdroidandroid/crdroid_features/blob/14.0/README.mkdn Extra features (implemented by the maintainer): - Ability to disable touchscreen buttons - Audio amplification - WireGuard - KernelSU (KSU): A kernel-based root solution for Android (Get It here) - Clear Speaker - LED indicator on offline charging (0-10% = red+blink, 11-30% = red, 31-80% = blue, 81-99% = green, 100% = green+blink) - Mi Sound Enhancer - Properly calibrated sensor-based Doze mode - Advanced "Smart Charging" - Native support for "Ok Google" hotword feature - Native support for Google Phone call recording - FMRadio(with RDS support) - Reboot to Fastboot - Battery-friendly pocket mode- RAM+ feature - 7SIM app to control SIM cards based on your schedule Flashing Instructions:
[...]
The ROM is encrypted by default. This is a crDroid requirement! If you don't care about encryption, you can disable it within OrangeFox recovery: demonstration(you
[...]
Disable FBE
[...]
❗️The "Redmi 4A" users **SHALL** upgrade the firmware to the latest available. ❗️The "Redmi 5A" users **SHALL** absolutely avoid firmwares based on Android 8 (Oreo) and downgrade to the latest Android 7 (Nougat) based one.
[...]
Sources: ROM: https://github.com/crdroidandroid Kernel: https://github.com/crdroidandroid/android_kernel_xiaomi_rova Download: ROM https://crdroid.net/rova/10 Changelog: See here Known issues: You tell me Visit official website @ crDroid.net crDroid rova Telegram crDroid Community Telegram crDroid Updates Channel Donate to help our team pay server costs
[...]
[ROM][8.1.0_r52][OFFICIAL] AospExtended ROM V5.8 for Redmi 4A/5A [ROLEX/RIVA]
[...]
[ROM][UNOFFICIAL] LineageOS 15.1 for Xiaomi Redmi 4A &amp; 5A [UNIFIED][OTA]
[...]
crDroid is designed to increase performance and reliability over stock Android for your device also attempting to bringing many of the best features existent today. Features: https://github.com/crdroidandroid/crdroid_features/blob/14.0/README.mkdn Extra features (implemented by the maintainer): - Ability to disable touchscreen buttons - Audio amplification - WireGuard - KernelSU (KSU): A kernel-based root solution for Android (Get It here) - Clear Speaker - LED indicator on offline charging (0-10% = red+blink, 11-30% = red, 31-80% = blue, 81-99% = green, 100% = green+blink) - Mi Sound Enhancer - Properly calibrated sensor-based Doze mode - Advanced "Smart Charging" - Native support for "Ok Google" hotword feature - Native support for Google Phone call recording - FMRadio(with RDS support) - Reboot to Fastboot - Battery-friendly pocket mode- RAM+ feature - 7SIM app to control SIM cards based on your schedule Flashing Instructions:
[...]
kind of sensor issue - Bluetooth dead
[...]
The ROM is encrypted by default. This is a crDroid requirement! If you don't care about encryption, you can disable it within OrangeFox recovery: demonstration(you should see "Disable FBE" button instead)
[...]
Flash Android 7 (Nougat) based firmware
[...]
❗️The "Redmi 4A" users **SHALL** upgrade the firmware to the latest available. ❗️The "Redmi 5A" users **SHALL** absolutely avoid firmwares based on Android 8 (Oreo) and downgrade to the latest Android 7 (Nougat) based one.
[...]
Sources: ROM: https://github.com/crdroidandroid Kernel: https://github.com/crdroidandroid/android_kernel_xiaomi_rova Download: ROM https://crdroid.net/rova/10 Changelog: See here Known issues: You tell me Visit official website @ crDroid.net crDroid rova Telegram crDroid Community Telegram crDroid Updates Channel Donate to help our team pay server costs

---

Title: [ROM][13.0][OFFICIAL][Rolex/Riva] crDroid 9.x
URL: https://xdaforums.com/t/rom-13-0-official-rolex-riva-crdroid-9-x.4512831/
Published: 2022-10-31T20:38:18.000Z
Author: iusmac
Highlights:
[ROM][13.0][OFFICIAL][Rolex/Riva] crDroid 9.x | XDA Forums
[...]
XDA Forums
[...]
crDroid is designed to increase performance and reliability over stock Android for your device also attempting to bringing many of the best features existent today.
[...]
Features:
https://github.com/crdroidandroid/crdroid\_features/blob/13.0/README.mkdn
[...]
**Extra features (*implemented by the maintainer*):**
[...]
```
`\* Ability to disable touchscreen buttons
\* Audio amplification
\* Bluetooth aptX codec
\* Clear Speaker
\* Improved battery saver at kernel level
\* LED indicator on offline charging (red when 0-99%, off when 100%)
\* Mi Sound Enhancer
\* Properly calibrated sensor-based Doze mode
\* Smart Charging
\* Native support for ""Ok Google"" hotword feature
\* Native support for Google Phone call recording
\* FMRadio (width RDS support)
\* Ability to reboot to Fastboot
\* Battery-friendly pocket mode
[...]
⚠️Stock kernel replacement will break some of the above features (ex. Ability to disable touchscreen buttons)`
```
[...]
**Pre-installation:**
[...]
* OrangeFox recovery (Download from here)
* Gapps (Download from here)
* Magisk 20.0 or newer for root (after first boot) - (
[...]
from here)
[...]
**⚠ The ROM is encrypted by default. This is a crDroid requirement! ⚠**
[...]
**If you don't care about encryption, you can disable it within OrangeFox recovery:demonstration(you should see "Disable FBE" button instead)**
[...]
💡**Note: encrypting via ROM's settings is no longer supported in Android 13+, so you will not be able to enable encryption in any other way (except clean install or as shown in the demo above).**
[...]
Wipe Dalvik
[...]
**ROM:**https://github.com/crdroidandroid
**Kernel:**https://github.com/crdroidandroid/android\_kernel\_xiaomi\_rova
Download:
**ROM**https://crdroid.net/rova/9
[...]
**Changelog:**See here
[...]
crDroid 9 Update
[...]
Changelog
[...]
- Upgraded kernel to 4.9.331-3.1-iusmac
- Added more DNS providers
- Hotspot: added ability to hide SSID
- Updated translations
- Fixed Bluetooth calling
- XiaomiParts:
[...]
\* Added back Dirac tile to quick settings
[...]
\* Added Dirac logo to Dirac settings
\* Added Mi logo to all XiaomiParts features
[...]
- Removed debris and reduced ROM size
- Fixed PowerOffAlarm
[...]
- Synced with crDroid 9.0 sources (November security patches).
- Added FaceUnlock support
- Added option to disable clipboard overlay
- Launcher: switched to build-in iconpack for themed app icons
- Updated translations
- Upgraded kernel to 4.9.332-3.2-iusmac
- Optimized graphics render engine
- Added multiple vibration intensity levels
[...]
crDroid 9
[...]
333
[...]
crDroid 9
[...]
- Synced with crDroid 9.0 sources (December security patches).
- Upgraded kernel to 4.9.336-3.5-iusmac
- Added Google Settings Intelligence app prebuilt
[...]
- Upgraded kernel to 4.9.336-3.
[...]
-iusmac
[...]
- Fixed incorrect WiFi MAC address detection
- Fixed kernel panic,
[...]
stack on Mi logo for some Riva devices
[...]
- Fixed left corner extra space when centering clocks or setting logo
[...]
- Removed HEVC support for builtin screen recorder
[...]
- Launcher3: Fixed
[...]
Google search bar
[...]
- Launcher3
[...]
[ROM][UNOFFICIAL] LineageOS 15.1 for Xiaomi Redmi 4A &amp; 5A [UNIFIED][OTA]
* 33bca
* Apr 16, 2018131415
Replies285
[...]
Views91K
[...]
`\* Ability to disable touchscreen buttons
[...]
\* Audio amplification
[...]
\* Clear Speaker
[...]
\* LED indicator on offline charging (red when 0-
[...]
00%)
[...]
Properly calibrated sensor-based Doze mode
[...]
Native support for
[...]
**crDroid 9
[...]
- Upgraded kernel to 4.9.331-3.
[...]
-iusmac
- Added more DNS providers
- Hotspot: added ability to hide SSID
- Updated translations
- Fixed Bluetooth calling
- XiaomiParts:
[...]
\* Added back Dirac tile to quick settings
[...]
\* Added Dirac logo to Dirac settings
[...]
\* Added Mi logo to all XiaomiParts features
[...]
- Removed debris and reduced ROM size
[...]
- Fixed PowerOffAlarm
```

**Tool: websearch**

**Input:**
```json
{
  "query": "GoGreen kernel Redmi 4A rolex review battery",
  "numResults": 5
}
```

**Output:**
```
Title: Best Custom Roms & Kernels? [rolex] | XDA Forums
URL: https://xdaforums.com/t/best-custom-roms-kernels-rolex.4095877/
Published: 2020-05-07T15:54:00.000Z
Author: N/A
Highlights:
Whatbare the best custom roms and kernels for rolex??currently using crdroid 6.5 rom with Go green kernel any suggestions?
[...]
I am using superioros with flamegapps. The reason i use flamegapps because they are very lightweight. The rom is very smooth. The default kernel (Starlight) works well. I have also used crdroid 6.5 with gogreen and it is good too.
[...]
Sep 12, 2017 15 26 Jaipur Xiaomi Redmi 4a Xiaomi Redmi 8
[...]
All roms and kernel are best. u have to try them and choose according to your requirement.
[...]
Xioami Redmi 4A kernel source (rolex) stil not released. all users please support
[...]
Rolex and Android 11. Battery Issues.
[...]
I am using superioros with flamegapps. The reason i use flamegapps because they are very lightweight. The rom is very smooth. The default kernel (Starlight) works well. I have also used crdroid 6.5 with gogreen and it is good too.
[...]
All roms and kernel are best. u have to try them and choose according to your requirement.

---

Title: [KERNEL][P/9-Q/10] GoGreen Rolex[HM4A] | XDA Forums
URL: https://xdaforums.com/t/kernel-p-9-q-10-gogreen-rolex-hm4a.4038775/
Published: 2020-01-22T15:17:29.000Z
Author: N/A
Highlights:
Kernel For Android Q Only Changelog: Added OC Cpu Up to 1,65GHZ Added OC GPU up to 650Mhz Screen Refresh OC to 65Hz Added Kcal Control Added Msm Hotplug Driver Download Link: MOD EDIT: DOWNLOAD LINK REMOVED *Tested on Treble ROM(bliss ROM) Special Thanks: Nick@xda for kernel source Note: If flash fail 'busybox error' use batik recovery (recomended) or old recovery
[...]
Update GoGreen Q Pushed This for Android q only -Added sound control -Enable all core when boot -arm: boot: dts: msm8917: enable threadirqs boot -ARM: dts: msm8917: Set GPU idle timeout to 64 ms -dts: qce: Set QCE Hardware to 160 MHz on msm8917 platforms Other optimized Special thanks Nick for source @z4nyx for helping @am_Useless for suggested Channel : http://t.me/gogreenDarkness Link Download: https://sourceforge.net/projects/gogreenxiaomi/files/latest/download Sources: https://github.com/areyoudeveloper/android_kernel_msm8917 Note:if device slow down disabled msm thermal
[...]
[Update Pushed] - msm_adreno_tz: add adrenoboost parameter - drivers: thermal: disabled core control forcefully - msm8917.dtsi: disable vdd-restriction - msm8917-regulator.dtsi: undervolts -50mV - OC Cpu up to 1,8Ghz Bugs: -core control force enabled Sources: https://github.com/areyoudeveloper/android_kernel_msm8917 Download Links: https://sourceforge.net/projects/gogreenxiaomi/files/latest/download
[...]
$2&
[...]
Cpu -Optimization Regulator (Undervolts)(To keep device cold) -Optimization Something and I forget
[...]
://sourceforge.net/projects/gogreenxiaomi/files/latest/download Source: Http://GitHub.com/areyoudeveloper/android_kernel_xiaomi_msm8917 Thanks for: Z4nyx Nick for sources Based on S kernel Note: "Cause used anykernel
[...]
2 after flash kernel need to flash magisk again"
[...]
msm_ion.h m0v3 all definition to
[...]
staging/Android/ion/
[...]
_ion.h -Added qnovo Quick Charging -Added BioShock Governor -Added impulse governor -Added Lionheart Governor -Added maple iosched -Added anxiety
[...]
Special Adding:
[...]
sad_tea Governor XD Credit: @mh
[...]
d fas (I'm Kang
[...]
ched from her GitHub) @muralivijay(I'm Kang Governor and qnovo
[...]
Charging from her GitHub) Download Links
[...]
/projects/g
[...]
.18.14
[...]
20200217.zip/download Source (Not Up-to-date): https://GitHub.com/areyoudeveloper/android_kernel_xiaomi_msm8917 Get GoGreen Save world's (Warning Contain Ads XD)
[...]
ched from her GitHub) @
[...]
ay(I
[...]
m Kang Governor and qnovo
[...]
from her GitHub)
[...]
world's
[...]
[UPDATE PUSHED] [KERNEL] [GoGreen] [P/9&Q/10] Changes: ________ √Boot/qcom/ msm8917-bus.dtsi :ptimization camera bandwidth ________ √boot/qcom/msm8917-camera-*.dtsi :: trying to reduce gcam lag ________ ✓boot/qcom/msm8917-gpu.dtsi :: little optimization ________ ✓boot/qcom/msm8917-regulator.dtsi :: uv again to reduce global warming Xb ________ +?Some optimization By Tea :') Download Link
[...]
https://sourceforge.net/projects/go...F.Kernel-VER.3.18.140-Q-20200315.zip/download Sources: https://GitHub.com/areyoudeveloper/android_kernel_xiaomi_msm8917 Flash and enjoy ?
[...]
[Update Arrived] Note:Go green leaf edition (normal update) Changes: Reduce heat issue Improve performance Improve battery Spectrum(depends on tree support) Aircrack-ng patches Update wireguard snapshot Download: https://sourceforge.net/projects/go....Kernel-VER.3.18.140-Q-202004018.zip/download By Tea
[...]
Nick@xda
[...]
sources Note: If flash fail use batik recovery Note for user Which uses gogreen If found bug or other problem Can ask and provide
[...]
) Keep calm
[...]
Kernel For Android Q Only Changelog: Added OC Cpu Up to 1,65GHZ Added OC GPU up to 650Mhz Screen Refresh OC to 65Hz Added Kcal Control Added Msm Hotplug Driver Download Link: MOD EDIT: DOWNLOAD LINK REMOVED *Tested on Treble ROM(bliss ROM) Special Thanks: Nick@xda for kernel source Note: If flash fail 'busybox error' use batik recovery (recomended) or old recovery

---

Title: [KERNEL][ROLEX][Aosp-Miui][7.1.x-up] Night-Core kernel for Redmi 4a
URL: https://xdaforums.com/t/kernel-rolex-aosp-miui-7-1-x-up-night-core-kernel-for-redmi-4a.3832828/
Published: 2018-08-23T05:56:15.000Z
Author: Vony C
Highlights:
][Aosp-Miui][7.1.x-up] Night-Core kernel for Redmi 4a | XDA Forums
[...]
XDA Forums
[...]
eRZEBDN.jpg
**Night-Core kernel for Redmi 4A**
**Numpang ngeshare pak**​
**I am not responsible for bricked devices, dead sd cards, explosions, nuclear wars, alarm applications getting failed, pleaseread the first 3 posts (features, faq, settings) carefullybefore flashing this kernel to make sure everything goes well with your installation.
This kernel will focus onquality over quantity, I will add only those features which don't cause instability and really improve performance or battery life of our device. I like to test my changes properly before release and keepstability the topmost priority, I don't guarantee weekly or nightly builds, updates will be given whenever required.
**
**Some Kernel Features**
**Features**
* Compile Gcc 7.2.x
* Overclocked Cpu to3878Mhz
* Tune-up Bus : Cpu-Gpu-memory
* Cpu boost and input boost
* Better battery life and performance
* Wireguard support
* Supports spectrum profiles
* Boeffla wakelock blocker
* Overclocking and underclocking
* Overclocked Display
* Disabled CRC check for better io
* lz4 & lz0 compression support available
* DTS eagle(New driver)
* msm ultra sound and tweakings
* NTFS, exFAT, F2FS, EXT filesystems support
* Fixed wrong gpu frequency reflected in sysfs
* Adding Octa-core,dual-core driver
* Adding 9 TCP
* Works on Unified Rom based on Fabian's trees And Miui rom
* Msm hotplug
**Requirements**
[...]
* Must be on Pie-Oreo based ROM based on Fabian's Unified Tree
* Miui Global stable (miuipro,stock rom,miui eu etc)
**How to flash**
[...]
* Boot into recovery mode
* Select zip kernel
* Flash the zip
* Reboot
[...]
DOWNLOAD LINKS REMOVED BY MOD UNTIL KERNEL SOURCE IS AVAILABLE
[...]
**Credits and thanks**
[...]
68F
[...]
24,
[...]
239**23
[...]
23, 2018
[...]
* **
* #3
Thanks,will it work for miui 10 global ?
Gonna try now
Edit : Freezing after boot
Last edited:Aug 23, 2018
[...]
**Vony C**
[...]
eRZEBDN.jpg
**Night-Core kernel for Redmi 4A**
**Numpang ngeshare pak**​
**I am not responsible for bricked devices, dead sd cards, explosions, nuclear wars, alarm applications getting failed, pleaseread the first 3 posts (features, faq, settings) carefullybefore flashing this kernel to make sure everything goes well with your installation.
This kernel will focus onquality over quantity, I will add only those features which don't cause instability and really improve performance or battery life of our device. I like to test my changes properly before release and keepstability the topmost priority, I don't guarantee weekly or nightly builds, updates will be given whenever required.
**
**Some Kernel Features**
**Features**
* Compile Gcc 7.2.x
* Overclocked Cpu to3878Mhz
* Tune-up Bus : Cpu-Gpu-memory
* Cpu boost and input boost
* Better battery life and performance
* Wireguard support
* Supports spectrum profiles
* Boeffla wakelock blocker
* Overclocking and underclocking
* Overclocked Display
* Disabled CRC check for better io
* lz4 & lz0 compression support available
* DTS eagle(New driver)
* msm ultra sound and tweakings
* NTFS, exFAT, F2FS, EXT filesystems support
* Fixed wrong gpu frequency reflected in sysfs
* Adding Octa-core,dual-core driver
* Adding 9 TCP
* Works on Unified Rom based on Fabian's trees And Miui rom
* Msm hotplug
**Requirements**
[...]
* Must be on Pie-Oreo based ROM based on Fabian's Unified Tree
* Miui Global stable (miuipro,stock rom,miui eu etc)
[...]
**How to flash**
[...]
* Boot into recovery mode
* Select zip kernel
* Flash the zip
* Reboot

---

Title: [DISCONTINUED][KERNEL][RIVA][ROLEX] DireWolf Unified kernel - Redmi 5A and Redmi 4A | XDA Forums
URL: https://xdaforums.com/t/discontinued-kernel-riva-rolex-direwolf-unified-kernel-redmi-5a-and-redmi-4a.3824182/
Published: 2018-08-02T14:06:42.000Z
Author: N/A
Highlights:
About DireWolf Kernel DireWolf Kernel is a new kernel and it works on both Redmi 4A and 5A. It is developed to give the maximum in every aspect of the device. I added governors, i/o schedulers, various other things to get the maximum out of the device. It supports spectrum profiles and also has a lot of other stuffs that tweakers like.
[...]
- Linux version 3.18.116
- Unified for 4A and 5A
- Better battery life and performance
- Wireguard support
- Supports spectrum profiles
- Boeffla wakelock blocker
- Overclocking and underclocking
- Overclocked Audio processor
- Overclocked Slimbus
- Disabled CRC check for better io
- Snappy compression and decompression
- DTS eagle(New driver)
- Overall sound tweakings
[...]
- Governors: Electron, alucard, conservative, ondemand, userspace, interactive, powersave, lionheart, lionfish
[...]
- I/O
[...]
ulers: Maple(
[...]
), zen, noop, deadline, cfq, bfq
[...]
TCP congestion algorithm : cubic, reno, westwood(default), bic, htcp, highspeed, vegas, veno, scalable, lp, yeah, illinois
[...]
Unified ROMs based on Fabian's trees
[...]
- AutoSMP hotplug
[...]
. I will test
[...]
. I also found
[...]
. But since i found its quite efficient in battery saving so i kept it. Now the
[...]
will most likely be fixed if u add some speaker gain (
[...]
i tested). And
[...]
the death sleep i think
[...]
doesn't let
[...]
cpus come online, so
[...]
About DireWolf Kernel DireWolf Kernel is a new kernel and it works on both Redmi 4A and 5A. It is developed to give the maximum in every aspect of the device. I added governors, i/o schedulers, various other things to get the maximum out of the device. It supports spectrum profiles and also has a lot of other stuffs that tweakers like.
[...]
- Linux version 3.18.116
- Unified for 4A and 5A
- Better battery life and performance
- Wireguard support
- Supports spectrum profiles
- Boeffla wakelock blocker
- Overclocking and underclocking
- Overclocked Audio processor
- Overclocked Slimbus
- Disabled CRC check for better io
- Snappy compression and decompression
- DTS eagle(New driver)
- Overall sound tweakings
[...]
DireWolf Version 7 update for Riva and Rolex Merged latest Linux Stable Linux 3.18.131 and CAF tag LA.UM. 7.6.r1-03700-89xx.0. ● Heavily debloated and removed unnecessary features. ● Added Input Boost. ● Added Built-in KCAL Screen profiles, accessible from Kernel Adiutor. ● Improved and adaptable Low Memory Killer. ● Improved architecture specific oriented usage. ● Tuned Low Memory Killer for slightly better battery without compromising performance. ● Improvement on LTE battery usage. ● GPU overclocked to 653MHz. ● GPU underclocked to 19MHz(only on idle). ● Added Simple GPU algorithm. Direwolf 7 Unified
[...]
yet. Well Dire is
[...]
. I'm not
[...]
though. The only significant
[...]
I've done is just set the
[...]
1651 and
[...]
freq to 200, deactivated CC
[...]
control), turned
[...]
" to make sure it drops to 200Mhz
[...]
my phones idle.
[...]
was set on default (thank LordShenron for that) and now we have westwood (total bliss) as
[...]
. Oh I did change entropy settings, I don't know why in Infinity it had a big difference in snappiness, but when I changed the read_wakeup_threshold to 80 (def 64) it speed up my 5A a lil. Haven't seen major difference in Dire though, maybe it's not needed, but still I'm holding on to 80 I don't know if this is right (havent have the time to read the logs or dmse
[...]
) but I think with
[...]
Yes AutoSMP is little bit harsh. I also found it makes device wakeup a difficult task. But since i found its quite efficient in battery saving so i kept it. Now the choppy sound will most likely be fixed if u add some speaker gain (as i tested). And for the death sleep i think autosmp after wakeup doesn't let the cpus come online, so if after wakeup all cpus come online at the higest frequency there will be no issues. I will test this soon.

---

Title: Xiaomi Redmi 4A Unboxing Quick Review Gaming Battery And Benchmarks
URL: https://gadgetstouseag.pages.dev/posts/xiaomi-redmi-4a-unboxing-quick-review-gaming-battery-and-benchmarks
Published: 2023-04-14T00:00:00.000Z
Author: Kenneth Tipler
Highlights:
Xiaomi Redmi 4A Unboxing Quick Review Gaming Battery And Benchmarks | gadgetstouse
[...]
# Xiaomi Redmi 4A Unboxing Quick Review Gaming Battery And Benchmarks
[...]
## Gaming Performance#
[...]
We tested Dead trigger 2 as the light game and Asphalt 8 as the heavy one on the Redmi 4A. The phone performed really well in terms of graphics and sound management. I didn’t face any lag or frame drops while playing Dead Trigger 2. We expected to see lags and frame drops in the Asphalt 8 as its a heavy game, but yet again there were no major lags. Graphics are well handled by Adreno 308. All over it was a smooth experience.
[...]
Battery dropped by 4% after 15 minutes gaming session of Dead Trigger 2. On the other hand Asphalt 8 for 15 minutes dropped the battery by 6% in 15 minutes. Phone didn’t get too hot but got a little warm after both the sessions.
```

---

## Assistant (Plan · Big Pickle · 14.9s)

_Thinking:_

Based on my research, here's a consolidated recommendation for the Redmi 4A (rolex) for best performance and battery life:

**Most Recent/Official Options (2025-2026):**

The device is still being actively maintained by **iusmac** (Max) with **crDroid** builds. The latest is crDroid 12.x based on Android 16 (build date March 2026). However, newer Android versions may be heavier on this device with only 2GB RAM and Snapdragon 425.

**Best OS/ROM Recommendations:**

For **fastest performance + best battery life** on Redmi 4A, the optimal choice depends on the Android version trade-off:

1. **crDroid 9.x (Android 13)** - This is likely the sweet spot. Android 13 is modern enough for app compatibility but lighter than 14/15/16. The crDroid builds for rova are well-optimized by iusmac with kernel-level battery improvements. Version 9.18 was the final build (July 2024).

2. **crDroid 10.x (Android 14)** - Good balance but some users report Bluetooth/WiFi issues.

3. **crDroid 11.x (Android 15)** - Reports of display issues (screen goes black after locking).

4. **crDroid 12.x (Android 16)** - Very new, may have more overhead on 2GB RAM.

5. **AospExtended (AEX)** - Historically known for smooth performance and good battery (mentioned in multiple XDA threads as having "amazing battery drain").

6. **Pixel Experience / Pixel Experience Plus** - Very smooth, Pixel-like experience, good battery.

**Best Kernels:**

1. **GoGreen Kernel** - Specifically designed for battery life + performance. Has OC options, undervolt, thermal optimizations. Works with Android 9-10.

2. **Infinity Kernel** - "Maintain good battery life without sacrificing performance." Has alucard governor + hotplug for great battery. Supports overclock to 1.61GHz.

3. **Triton Kernel** - EAS (Energy-Aware Scheduling) kernel, good for battery on Android 10+.

4. **Stock crDroid kernel** (by iusmac) - If using crDroid, the stock kernel is well-tuned and includes battery-friendly features. The maintainer warns that replacing stock kernel breaks some features.

**My Recommendation for best balance:**

**crDroid 10.x (Android 14)** with the **stock crDroid kernel** - it's actively maintained, well-optimized, and has kernel-level battery improvements. If you want even better battery, pair it with GoGreen kernel (if compatible) or Triton kernel.

For **maximum performance with decent battery**: Use **AospExtended** (lighter than crDroid) with **Infinity Kernel** using alucard governor.

Let me present this concisely.

For Redmi 4A (rolex) with 2GB RAM and Snapdragon 425, here's the optimal combo:

**Best ROM: crDroid 9.x (Android 13)** — final build v9.18, well-optimized by maintainer iusmac with kernel-level battery improvements. Android 14+ gets heavier; users report display/Bluetooth bugs on 15/16.

**Alternative (lighter/faster): AospExtended** — historically praised for smoothness and minimal battery drain.

**Best Kernel: Stock crDroid kernel** (tuned by iusmac — don't replace it if using crDroid, it breaks XiaomiParts features). Or **Infinity Kernel** with `alucard` governor + `alucard` hotplug for best battery/performance balance.

**For max battery: GoGreen kernel** — undervolts, has thermal optimizations, underclocks to 200MHz idle. Pair with a lightweight ROM like AEX.

**Productivity tip:** Use *flamegapps* (pico/nano) instead of full GApps to save RAM. Install *Kernel Adiutor* to tune governor/interactive settings post-flash.

---

## User

what about arrowos

---

## Assistant (Plan · Big Pickle · 6.2s)

_Thinking:_

The user is asking about ArrowOS for Redmi 4A (rolex). Let me search for information about ArrowOS on this device.

**Tool: websearch**

**Input:**
```json
{
  "query": "ArrowOS Redmi 4A rolex custom ROM review battery performance",
  "numResults": 8
}
```

**Output:**
```
Title: [ROM][v11.0] Arrow-OS [UNOFFICIAL][ROLEX/RIVA] | XDA Forums
URL: https://xdaforums.com/t/rom-v11-0-arrow-os-unofficial-rolex-riva.4295147/
Published: 2021-06-22T04:41:35.000Z
Author: N/A
Highlights:
[ROM][v11.0] Arrow-OS [UNOFFICIAL][ROLEX/RIVA] | XDA Forums
[...]
# [ROM][v11.0] Arrow-OS [UNOFFICIAL][ROLEX/RIVA]
[...]
ABOUT ArrowOS is an AOSP/ CAF based project started with the aim of keeping things simple, clean and neat. Website: https://arrowos.net Telegram: Channel| TG Portal/Links Github: https://github.com/ArrowOS Code Review: review.arrowos.net E-mail: arrowos.contact PayPal: Donate to us Blog: blog.arrowos.net Checkout more documentation at (maintainership/contributing): Check this out WHAT WORKS?
[...]
Be sure to include a log : check how to DOWNLOADS Click here to Download Read our blog article/post about: * HOW-TO report a bug* GAPPS and VANILLA variants* Checking build integrity ROM Source: https://github.com/ArrowOS Kernel Source: https://github.com/rajsharma55/android_kernel_xiaomi_msm8917
[...]
Found actually NONE so far, it looks like a really stable build. I did some extensive testing but it's just SOLID. Probably battery life is a tad less than MIUI 10 but nothing extraordinary. Actually would be great to have this one OFFICIAL with updates etc Any chance on this @rajsharma55? Thank you for your efforts!
[...]
Works great! It seems to drain battery some when screen is on, but it is an old phone with the original battery.
[...]
ABOUT ArrowOS is an AOSP/ CAF based project started with the aim of keeping things simple, clean and neat. Website: https://arrowos.net Telegram: Channel| TG Portal/Links Github: https://github.com/ArrowOS Code Review: review.arrowos.net E-mail: arrowos.contact PayPal: Donate to us Blog: blog.arrowos.net Checkout more documentation at (maintainership/contributing): Check this out WHAT WORKS?
[...]
Be sure to include a log : check how to DOWNLOADS Click here to Download Read our blog article/post about: * HOW-TO report a bug* GAPPS and VANILLA variants* Checking build integrity ROM Source: https://github.com/ArrowOS Kernel Source: https://github.com/rajsharma55/android_kernel_xiaomi_msm8917

---

Title: List of Redmi 4A (Rolex) Custom Roms | XDA Forums
URL: https://xdaforums.com/t/list-of-redmi-4a-rolex-custom-roms.3774162/
Published: 2018-04-06T13:31:33.000Z
Author: N/A
Highlights:
Guys I am just compiling a list of all the latest roms. Because the previous thread https://xdaforums.com/redmi-4a/how-to/update-redmi-4a-users-t3706184 by skmaiti2050 got discontinued. https://androidfilehost.com/?w=developers&did=2684 Here is the entire list of devs who are building roms and mods
[...]
Redmi 4A aka rolex.\ Oreo
[...]
---------------------------------------------------------------- ---------------------------------------------------------------------------------------------------------------- ---------------------------------------------------------------------------------------------------------------- Gcam portrait working https://www.celsoazevedo.com/files/android/google-camera---------------------------------------------------------------------------------------------------------------- Project Treble XDA Thread---------------------------------------------------------------------------------------------------------------- Resurrection Remix OREO |: XDA Thread---------------------------------------------------------------------------------------------------------------- CrDroid OREO |: XDA Thread---------------------------------------------------------------------------------------------------------------- AEX OREO | Build by Erik Garcia (ECr34T1v3) https://downloads.aospextended.com/rolex XDA Thread---------------------------------------------------------------------------------------------------------------- Project Xtended OREO |: XDA Thread
[...]
Rom 13.5 OREO
[...]
XDA by Aryan
[...]
---------------- Pixel Experience
[...]
AOSP]
[...]
r1]
[...]
OREO |: XDA Thread
[...]
AtomicOS OREO
[...]
: XDA Thread
[...]
------------------------------------------------------------------------------------------------ Cardinal AOSP (OREO | UNOFFICIAL XDA Thread
[...]
-------------------------------------------------------------------------------- DOT OS OREO
[...]
UNOFFICIAL
[...]
---------------- Nitrogen OS OREO
[...]
9.1
[...]
official XDA Thread
[...]
---------------------------------------------------------------- AOSCP
[...]
Cypher Project
[...]
ee 81
[...]
----------------------------------------------------------------
[...]
8.1
[...]
OFFICIAL] ToxycOS for Redmi 4A/5A
[...]
----------------------------------------------------------------
[...]
OS OREO
[...]
UNOFFICIAL ROM Link Guide: Wipe, Flash Rom, flash Gapps
[...]
Flash Magisk
[...]
--------------------------------------------------------------------------------
[...]
---------------- CARBON CR 6.1 NOCT OREO [8.1
[...]
r26
[...]
CLANG] | UNOFFICIAL XDA By Carlos Guide: Wipe, Flash Rom
[...]
flash Gapps, Flash Magisk, Reboot
[...]
------------------------------------------------------------------------------------------------ LineageOS 15.1 (Unofficial) by 33bca aka Offain XDA Thread---------------------------------------------------------------------------------------------------------------- AICP by Aryan OREO | UNOFFICIAL : XDA Thread
[...]
DirtyUnicorns build by Murli
[...]
UNOFFICIAL ROM Link----------------------------------------------------------------------------------------------------------------
[...]
UNOFFICIAL] Validus OS
[...]
Oreo Roms
[...]
Flash Kernel https
[...]
xdaforums.com
[...]
775549
[...]
--------------------------------------------------------------------------------
[...]
----------------------------------------------------------------
[...]
Nice I used the Lineage OS 15.1 but I back to MiUI because I got battery drain..
[...]
Use AEX Extended, battery drain is amazing
[...]
Bootleggers proved best battery friendly and stable rom so far. Cheers

---

Title: List of Best Custom ROM for Xiaomi Redmi 4A [Updated]
URL: https://www.getdroidtips.com/custom-rom-xiaomi-redmi-4a/
Published: 2017-12-07T12:21:04.000Z
Author: Mohammed Huwais
Highlights:
### ArrowOS
[...]
ArrowOS is a new Custom ROM and it is AOSP inspired open-source project started with the aim of keeping things simple, clean, and neat. The ROM brings almost the same feature which is very useful for ROM customization and in the end aims to deliver smooth performance with better battery life.
[...]
Download ROM Here
[...]
ViperOS is a new Custom Firmware based on the AOSP code but has its own custom mods. This ROM is quite famous for its custom-made features from all CM, Lineage, Slim, Omni AOSPA, etc. The ROM was developed when Google released the code for Android 7.1 Nougat. Now it has become one of the most stable Custom firmware with many features and customization. It offers a great balance between battery and performance.
[...]
Download ROM Here

---

Title: [ROM][v11.0] Arrow-OS [UNOFFICIAL][ROLEX/RIVA] | XDA Forums
URL: http://forum.xda-developers.com/t/rom-v11-0-arrow-os-unofficial-rolex-riva.4295147/
Published: 2021-06-22T04:41:35.000Z
Author: N/A
Highlights:
[ROM][v11.0] Arrow-OS [UNOFFICIAL][ROLEX/RIVA] | XDA Forums
[...]
# [ROM][v11.0] Arrow-OS [UNOFFICIAL][ROLEX/RIVA]
[...]
- Thread starter rajsharma55
- Start date Jun 22, 2021
- Tags arrow os custom rom redmi 4a redmi 5a riva rolex rom xiaomi redmi 4a xiaomi redmi 5a
[...]
ABOUT ArrowOS is an AOSP/ CAF based project started with the aim of keeping things simple, clean and neat. Website: https://arrowos.net Telegram: Channel| TG Portal/Links Github: https://github.com/ArrowOS Code Review: review.arrowos.net E-mail: arrowos.contact PayPal: Donate to us Blog: blog.arrowos.net Checkout more documentation at (maintainership/contributing): Check this out WHAT WORKS?
[...]
Be sure to include a log : check how to DOWNLOADS Click here to Download Read our blog article/post about: * HOW-TO report a bug* GAPPS and VANILLA variants* Checking build integrity ROM Source: https://github.com/ArrowOS Kernel Source: https://github.com/rajsharma55/android_kernel_xiaomi_msm8917
[...]
4, 2017 44
[...]
Found actually NONE so far, it looks like a really stable build. I did some extensive testing but it's just SOLID. Probably battery life is a tad less than MIUI 10 but nothing extraordinary. Actually would be great to have this one OFFICIAL with updates etc Any chance on this @rajsharma55? Thank you for your efforts!
[...]
##### Member

Dec 29, 2017 5 0
[...]
Works great! It seems to drain battery some when screen is on, but it is an old phone with the original battery.
[...]
ABOUT ArrowOS is an AOSP/ CAF based project started with the aim of keeping things simple, clean and neat. Website: https://arrowos.net Telegram: Channel| TG Portal/Links Github: https://github.com/ArrowOS Code Review: review.arrowos.net E-mail: arrowos.contact PayPal: Donate to us Blog: blog.arrowos.net Checkout more documentation at (maintainership/contributing): Check this out WHAT WORKS?
[...]
Be sure to include a log : check how to DOWNLOADS Click here to Download Read our blog article/post about: * HOW-TO report a bug* GAPPS and VANILLA variants* Checking build integrity ROM Source: https://github.com/ArrowOS Kernel Source: https://github.com/rajsharma55/android_kernel_xiaomi_msm8917

---

Title: Xiaomi Redmi 4A (aka Rolex) | Jeff McNeill
URL: https://jeffmcneill.com/redmi4a/
Published: 2018-06-23T13:37:24.000Z
Author: by
Highlights:
The Xiaomi Redmi 4A (aka Rolex) is a cheap (~100 USD) and lightweight (131.5g) 5" phone. For price, weight, and size, there is not much competiton. The screen is a 720 x 1280 px 16x9 screen that is pretty decent. Its got a Snapdragon 425 and 2gb of RAM with 16 or 32 gb of storage, and supports dual sim or single sim + microsd card.
[...]
On the negative side, the camera is weak, it is slow to open, and of course stock MIUI is slow and bloated, along with an annoying reminder to register your sim aka spyware on the prowl.
[...]
Custom ROMs for Redmi 4A
[...]
## Custom ROMs for Redmi 4A
[...]
Thankfully this is a popular device for custom roms. Rolex is not as widely supported as some devices. However, the AOSP Extended ROM, a twice monthly updated vanilla Google + customizations does support this device. It turns out that LinneageOS 15.1 supports Redmi 4A as well. Turns out Pixel Experience rom is also available for rolex.
[...]
I still prefer this phone over the Xiaomi Redmi 5A and Xiaomi Redmi 6A. The 6A is a bit heavier, with a longer screen, but the home row buttons have been moved onto the display, so no real gain in screen real estate. The 5A is not as nice a feel in the hand, but some versions have 4gb of ram and 32gb of storage, so that is better than the 2gb generally available across all of these models. Overall, a good balance of lightweight, decent screen, moderate performance, and lower-end camera. Hard to beat for around $100 USD.

---

Title: [ROM][rolex][UNOFFICIAL] LineageOS 14.1 for Redmi 4A [06/04/2018] | Page 4 | XDA Forums
URL: https://forum.xda-developers.com/t/rom-rolex-unofficial-lineageos-14-1-for-redmi-4a-06-04-2018.3701237/page-4
Published: 2017-11-06T18:55:51.000Z
Author: N/A
Highlights:
[ROM][rolex][UNOFFICIAL] LineageOS 14.1 for Redmi 4A [06/04/2018] | Page 4 | XDA Forums
[...]
# [ROM][rolex][UNOFFICIAL] LineageOS 14.1 for Redmi 4A [06/04/2018]
[...]
No rom is bug free. That said, I've been using it over the last day and it seems stable for me. Best thing to do is back up all your data and try it out. Any issues let the developers know so they can fix it.
[...]
No rom is bug free. That said, I've been using it over the last day and it seems stable for me. Best thing to do is back up all your data and try it out. Any issues let the developers know so they can fix it.
[...]
Great ROM, I have one issue - LED does not light up when charging. It works for notifications or low battery, but not for charging. Is this fixable?
[...]
Great ROM, I have one issue - LED does not light up when charging. It works for notifications or low battery, but not for charging. Is this fixable?
[...]
Change the battery pulse colour in settings.
[...]
Change the battery pulse colour in settings.
[...]
Thank you - I tried it before but after picking a few values and none of them working I gave up. I tried it now and I can get it to be blue while charging by setting color to white (#ffffff). I'd prefer yellow though, but for now it works.
[...]
Is only one bug, with notifications led colors: work only red, green and blue. For me is enough, even the white color not working. This rom is more battery-friendly tthan MIUI. I love this rom! Thank you, Carlos! Sorry for my bad english.
[...]
I think so. A changelog by OP mentioned it here.
[...]
LineageOS is a free, community built, aftermarket firmware distribution of Android 7 (Nougat), which is designed to increase performance and reliability over stock Android for your device. LineageOS is based on the Android Open Source Project with extra contributions from many people within the Android community. It can be used without any need to have any Google application installed. Linked below is a package that has come from another Android project that restore the Google parts. LineageOS does still include various hardware-specific code, which is also slowly being open-sourced anyway. All the source code for LineageOS is available in the LineageOS Github repo. And if you would like to contribute to LineageOS, please visit out Gerrit Code Review. Disclaimer
[...]
What's Working :
[...]
1. Audio
2. BLUETOOTH
3. Camera
4. dt2w
5. EGL
6. FINGERPRINT
7. IR Blaster
8. RIL
9. Video Playback
10. VoLTE
11. WIFI
12. LED
[...]
Firmware Required for install: http://bigota.d.miui.com/V9.2.6.0.NCCMIEK/rolex_global_images_V9.2.6.0.NCCMIEK_20180206.0000.00_7.1_global_0847316da4.tgz Downloads: builds: https://sourceforge.net/projects/redmi-4a/files/LineageOS-14.1/ LineageOS addons: https://download.lineageos.org/extras Google Apps: http://opengapps.org Donations: https://www.paypal.me/CarlosArriagaCM [Mention device name & rom name while donating] DO NO POST BUGS WITHOUT LOGS AND PROPER STEPS TO REPRODUCE THE ISSUE Source: https://github.com/LineageOS-R4A Contributors
[...]
New build is up Fix battery drain
[...]
Changelog: * Update blobs to MIUI 9.2.6.0 * Import kernel source upstream 3.18.34 and update caf LA.UM.5.6.r1-06000-89xx.0 * Hostpotd fixed * Import Camera OSS BUGS: * Camera with flash on in pictures. (The camera all works video recording with flash on and camera works fine with flash off). * Baseband unknow (ONLY VISUAL BUG).
[...]
NEW BUILD IS UP! Changelog: * Fix Camera with flash * Fix Saving video recording * Sync sources los * Update blobs * and others... Bugs: * Only baseband unknow (visual bug) THREAD UPDATE! PLS READ

---

Title: Get Android 9.0 Pie on Xiaomi Redmi Note 4 with Arrow OS
URL: https://www.fonearena.com/blog/269448/xiaomi-redmi-note-4-android-pie-arrow-os.html
Published: 2018-11-27T04:08:19.000Z
Author: Arpit
Highlights:
Xiaomi recently announced the list of smartphones eligible for Android Oreo/Pie update, but Xiaomi’s best seller from 2017 is not included in the list and now we can assume that Redmi Note 4 will not receive any Android update. In case you wish to enjoy the latest version of Android on your Redmi Note 4, you can use custom ROM on your device. We tried Android Pie 9.0 based Arrow OS on our unit and here are our impressions,
[...]
Performance and Benchmarks:
[...]
Qualcomm Snapdragon 625 is a decent performer, we obtained AnTuTu score of 81212 on Arrow OS. We experienced a smooth and reliable day to day performance. The device exhibit RAM management issue and was unable to keep more than 3 apps in memory, most of apps reload incase you have more than 3 apps in background.
[...]
Arrow OS is close to stock Android with some nifty features, this ROM is based on latest Android Pie 9.0 and comes with October security patch (updated to November security patch now). There is almost no bloatware pre-installed with the ROM and there are only a few essential apps preinstalled which can be disabled. Out of 32 GB internal storage, 7.31 GB is occupied by the system and users get around 24 GB of free storage.
[...]
Users can also assign different LED colors to different battery charging levels and choose battery icon as per their preference. Apart from this, features like double tap to wake the device, double tap on status bar to lock the device, and ambient display are also available.
[...]
Battery Life:
[...]
The battery performance on this ROM is slightly better than stock MIUI ROM, it lasts for a whole day with heavy usage. On moderate usage, the device should last for more than a day easily. I was able to get 7 hours screen on time on a busy day with 29% charge left on my device and device lasted for 2 days on moderate usage.
[...]
It takes about 2 hours and 30 minutes to charge the device from 0 to 100%, 0-50% takes 1 hour and it charges to 90% in 2 hours 10 minutes with 5V/2A charger. The phone also shows charging information on the lock screen while charging.
[...]
If you’re using Redmi Note 4 (Mido) and want to stay updated with the latest Android, Arrow OS is worth consideration. The ROM is stable and offers good day to day performance along with good battery life, the only issue that we came across was RAM management.
[...]
- System-wide themes and accent colors
- Customizations
- Bloat-free
- Cam2API enabled by default
- Good battery life
[...]
- RAM management issue
- Slow Fingerprint response

---

Title: Xiaomi Redmi 4A Review
URL: http://www.fonearena.com/blog/216019/xiaomi-redmi-4a-review.html
Published: 2017-03-27T03:57:11.000Z
Author: Srivatsan Sridhar
Highlights:
Unlike the Redmi 3s series, this one has a polycarbonate body, even though it looks like metal, but the matte finish offers a nice feel and the phone is solid to hold. Polycarbonate body also makes the phone light at just 131.5 grams, even though is packs a huge 3120mAh battery. It measures 139.9 x 70.4 x 8.5mm, making it slightly taller and wider than the Redmi 3s, but the thickness is the same.
[...]
Coming to the performance, the phone is powered by a quad-core Snapdragon 425 processor with four ARM Cortex A53 cores clocked at 1.4GHz per core and has 2GB of RAM. The performance is good without any lags. It also has a 500MHz Adreno 308 GPU. Since this is not a powerful SoC the GPU is just average, so the gaming performance is not on par with the Redmi 3s that has an Octa-Core Snapdragon 430 SoC with Adreno 505 GPU. That said, check out some synthetic benchmark scores below.
[...]
853
[...]
in the Bas
[...]
II benchmark and topped the
[...]
Coming to the battery life the 3030mAh (minimum) / 3120mAh (typical) built-in battery offers good battery life. It lasts for a whole day with average use and lasts more than that with minimal use. Sadly, the phone doesn’t have fast charging so it takes more than 2 and half hours to charge the phone.
[...]
It achieved a One Charge Rating of 12 hours and 53 minutes. Check out the c omplete set of battery life test results here.
[...]
6,999 Redmi
[...]
a metal body
[...]
camera and a faster Snapdragon 430
[...]
a-Core processor, so
[...]
might not go for the Redmi 4A. If you are tight on the budget, go for the Redmi 4A, otherwise, the Redmi
[...]
the preferred choice. Xiaomi
```

**Tool: websearch**

**Input:**
```json
{
  "query": "ArrowOS rolex Redmi 4A XDA download",
  "numResults": 8
}
```

**Output:**
```
Title: [ROM][9.0.0_r46][OFFICIAL] AospExtended ROM V6.7 for Redmi 4A [ROLEX] | XDA Forums
URL: http://forum.xda-developers.com/t/rom-9-0-0_r46-official-aospextended-rom-v6-7-for-redmi-4a-rolex.3867054/
Published: 2018-11-14T13:54:25.000Z
Author: N/A
Highlights:
[ROM][9.0.0_r46][OFFICIAL] AospExtended ROM V6.7 for Redmi 4A [ROLEX] | XDA Forums
[...]
# [ROM][9.0.0_r46][OFFICIAL] AospExtended ROM V6.7 for Redmi 4A [ROLEX]
[...]
Download ROM, GApps here for your device! rolex Google Apps - GApps
[...]
XDA:DevDB Information AospExtended Pie Official (rolex), ROM for the Xiaomi Redmi 4a Contributors ECr34T1v3, muralivijay, ataberkozen Source Code: https://github.com/ECr34T1v3 ROM OS Version: 9.x Pie ROM Kernel: Linux 3.x ROM Firmware Required: MIUI 9.2.6.0 Global Based On: AOSP Version Information Status: Stable Current Stable Version: 1.5 Stable Release Date: 2018-12-17 Current Beta Version: 1.1 Beta Release Date: 2018-11-11 Created 2018-11-14 Last Updated 2019-09-02
[...]
Build 2019/08/23: -Merged: New version of AospExtended (v6.7) Changelog in https://blog.aospextended.com/AospExtended-v6.7-Changelog-Merged: August Security Patch (9.0.0_r46) It has been 2 years officially maintaining AEX, i am following new paths for my life. I will no longer compile officially, but I will always be available. Thanks for all, guys <3 Unofficial ROMs and projects: https://ecr34t1v3.github.io Build 2019/07/11: -Merged: July Security Patch (9.0.0_r44) -Merged: SELinux Enforcing -Reworked: Device Tree No-Commonized (Thanks to nick) -Reworked: Doze settings (Ambient display) -Readded: Dirac Settings (Increased Sound) -Fixed: Quickswitch support -Enabled: Incall music -Enabled: AGPS Recommended: Clean Flash (because is new device tree)
[...]
Q: Which TWRP do I use? A: Use latest TWRP for ROLEX from HERE Q: Which GApps do I use? A: Flash OpenGApps Pico (recommended version). Link HERE Q: Is there a bug in ROM?? A: No. It is stable. Maybe there is a problem (if you have it, let me know which one I will correct), but it is stable for daily use. Q: Do I have to wipe data if coming from another ROM? A: Yes, I will not be providing help/support to users that haven't wiped data when coming from another ROM. Q: How often will I be getting updates? A: The plan is for weeklies, if unavoidable circumstances come up, please don't spam the thread. I will release a build as soon as one is ready. Q: Does VoLTE/VoWiFi work? A: Yes, works. Q: Is the ROM official? A: Yes, Official, and updates OTA available. Q: I use Telegram, where can I find help on that platform? A: There is a common AEX Group Chat for all devices, the link is HERE Q: Does SafetyNet pass and is the SELinux Enforcing? A: Yes, SafetyNet does pass and SELinux is Enforcing.
[...]
Download ROM, GApps here for your device! rolex Google Apps - GApps
[...]
XDA:DevDB Information AospExtended Pie Official (rolex), ROM for the Xiaomi Redmi 4a Contributors ECr34T1v3, muralivijay, ataberkozen Source Code: https://github.com/ECr34T1v3 ROM OS Version: 9.x Pie ROM Kernel: Linux 3.x ROM Firmware Required: MIUI 9.2.6.0 Global Based On: AOSP Version Information Status: Stable Current Stable Version: 1.5 Stable Release Date: 2018-12-17 Current Beta Version: 1.1 Beta Release Date: 2018-11-1
[...]
Created 2018-11-14 Last Updated 2019-
[...]
9-02
[...]
Build 2019/08/23: -Merged: New version of AospExtended (v6.7) Changelog in https://
[...]
.aospe
[...]
ended.com/AospExtended-v6.7-Changelog-Merged: August Security Patch (9.0.0_r46) It has
[...]
2 years
[...]
maintaining AEX, i am following new paths for my life. I will no longer compile officially, but I will always be available. Thanks for all, guys <
[...]
Which TWRP do I use? A
[...]
Use latest TWRP for ROLEX from HERE Q: Which GApps do I use? A: Flash OpenGApps Pico (recommended version). Link HERE Q
[...]
Is there a bug in ROM?? A: No. It is stable. Maybe there is a problem (if you have it, let me know which one I will correct), but it is stable for daily use. Q: Do I have to wipe data if coming from another ROM? A
[...]
, I will not be providing help/support to users that haven't wiped data when coming from another ROM
[...]
How often will I be getting updates
[...]
, please don't spam

---

Title: List of Redmi 4A (Rolex) Custom Roms | XDA Forums
URL: https://xdaforums.com/t/list-of-redmi-4a-rolex-custom-roms.3774162/
Published: 2018-04-06T13:31:33.000Z
Author: N/A
Highlights:
Guys I am just compiling a list of all the latest roms
[...]
=files&flid=259083 AquariOs Nougat https://androidfilehost
[...]
=818070582850494235 ColtOS
[...]
https://androidfilehost.com/?w=files&flid=250711 VanirAOSP
[...]
https://androidfilehost.com/?w
[...]
latest roms. Because the previous thread https://xdaforums.com/redmi-4a/how-to/update-redmi-4a-users-t3706184 by skmaiti2050 got discontinued. https://androidfilehost.com/?w=developers&did=2684 Here is the entire list of devs who are building roms and mods for Redmi 4A aka rolex.\ Oreo Builds ---------------------------------------------------------------------------------------------------------------- ---------------------------------------------------------------------------------------------------------------- ---------------------------------------------------------------------------------------------------------------- Gcam portrait working https://www.celsoazevedo.com/files/android/google-camera---------------------------------------------------------------------------------------------------------------- Project Treble XDA Thread---------------------------------------------------------------------------------------------------------------- Resurrection Remix OREO |: XDA Thread---------------------------------------------------------------------------------------------------------------- CrDroid OREO |: XDA Thread---------------------------------------------------------------------------------------------------------------- AEX OREO | Build by Erik Garcia (ECr34T1v3) https://downloads.aospextended.com/rolex XDA Thread---------------------------------------------------------------------------------------------------------------- Project Xtended OREO |: XDA Thread---------------------------------------------------------------------------------------------------------------- FrankenRom 13.5 OREO |: XDA by Aryan---------------------------------------------------------------------------------------------------------------- Pixel Experience [AOSP] [r1] | OREO |: XDA Thread---------------------------------------------------------------------------------------------------------------- AtomicOS OREO |: XDA Thread Note: No Updates ---------------------------------------------------------------------------------------------------------------- Candy8.1 OREO | UNOFFICIAL XDA Thread by AryanPatidar XDA Thread by sharath3589---------------------------------------------------------------------------------------------------------------- Cardinal AOSP (
[...]
FFICIAL XDA Thread---------------------------------------------------------------------------------------------------------------- DOT
[...]
FFICIAL XDA Thread---------------------------------------------------------------------------------------------------------------- Xperience 12.1 Unofficial
[...]
9.1 Unofficial XDA Thread---------------------------------------------------------------------------------------------------------------- AOSCP - Cypher Project Unofficial ROM by Eric---------------------------------------------------------------------------------------------------------------- [ROM][8.1.0][UNOFFICIAL] COLT OS 2.1 [ROLEX] XDA Thread---------------------------------------------------------------------------------------------------------------- [Unified][RIVA][RO
[...]
][UNOFFICIAL][VOL
[...]
][OREO][8.1.0_r30]XenonHD X
[...]
.0] X
[...]
.com/
[...]
---------------- Nougat ROMs: LineageOS Rom: https://androidfilehost.com/?fid=746010030569967699 CRDroid https://androidfilehost.com/?fid=818070582850493743 Viper
[...]
https://www.androidfilehost.com/?fid=746010030569951104 Resurrection
[...]
https://androidfilehost.com/?fid=818070582850494211 Atomic
[...]
You might want to add these: 8.1 Oreo: • Ressurection Remix (Official)• crDroid (Official)• Project Xtended (Official)• AtomicOS (Official)• LineageOS 15.1 (Unofficial)• Candy8.1 (Unofficial)• Cardinal AOSP (Unofficial)• Firehound (Unofficial)

---

Title: [ROM][v11.0] Arrow-OS [UNOFFICIAL][ROLEX/RIVA] | XDA Forums
URL: https://xdaforums.com/t/rom-v11-0-arrow-os-unofficial-rolex-riva.4295147/
Published: 2021-06-22T04:41:35.000Z
Author: N/A
Highlights:
[ROM][v11.0] Arrow-OS [UNOFFICIAL][ROLEX/RIVA] | XDA Forums
[...]
# [ROM][v11.0] Arrow-OS [UNOFFICIAL][ROLEX/RIVA]
[...]
Sep 12, 2017 15 26 Jaipur Xiaomi Redmi 4a Xiaomi Redmi 8
[...]
ArrowOS​
[...]
ABOUT ArrowOS is an AOSP/ CAF based project started with the aim of keeping things simple, clean and neat. Website: https://arrowos.net Telegram: Channel| TG Portal/Links Github: https://github.com/ArrowOS Code Review: review.arrowos.net E-mail: arrowos.contact PayPal: Donate to us Blog: blog.arrowos.net Checkout more documentation at (maintainership/contributing): Check this out WHAT WORKS?
[...]
Be sure to include a log : check how to DOWNLOADS Click here to Download Read our blog article/post about: * HOW-TO report a bug* GAPPS and VANILLA variants* Checking build integrity ROM Source: https://github.com/ArrowOS Kernel Source: https://github.com/rajsharma55/android_kernel_xiaomi_msm8917
[...]
Found actually NONE so far, it looks like a really stable build. I did some extensive testing but it's just SOLID. Probably battery life is a tad less than MIUI 10 but nothing extraordinary. Actually would be great to have this one OFFICIAL with updates etc Any chance on this @rajsharma55? Thank you for your efforts!
[...]
Works great! It seems to drain battery some when screen is on, but it is an old phone with the original battery.
[...]
[RECOVERY] [OFFICIAL] TWRP 3.2.1-0 for Xiaomi Redmi 4A [rolex] [20171210]
[...]
[ROM][8.1.0_r52][OFFICIAL] AospExtended ROM V5.8 for Redmi 4A/5A [ROLEX/RIVA]
[...]
4A
[...]
ArrowOS​
[...]
ABOUT ArrowOS is an AOSP/ CAF based project started with the aim of keeping things simple, clean and neat. Website: https://arrowos.net Telegram: Channel| TG Portal/Links Github: https://github.com/ArrowOS Code Review: review.arrowos.net E-mail: arrowos.contact PayPal: Donate to us Blog: blog.arrowos.net Checkout more documentation at (maintainership/contributing): Check this out WHAT WORKS?
[...]
Be sure to include a log : check how to DOWNLOADS Click here to Download Read our blog article/post about: * HOW-TO report a bug* GAPPS and VANILLA variants* Checking build integrity ROM Source: https://github.com/ArrowOS Kernel Source: https://github.com/rajsharma55/android_kernel_xiaomi_msm8917

---

Title: [9.0] ArrowOS v9.0 [STABLE] | XDA Forums
URL: https://xdaforums.com/t/9-0-arrowos-v9-0-stable.3840382/
Published: 2018-09-09T14:01:55.000Z
Author: N/A
Highlights:
[9.0] ArrowOS v9.0 [STABLE] | XDA Forums
[...]
# [9.0] ArrowOS v9.0 [STABLE]
[...]
ABOUT ArrowOS is an AOSP based project started with the aim of keeping things simple, clean and neat. We added just the right and mostly used stuff that will be actually USEFUL at the end of the day. Website: https://arrowos.net Telegram: Channel| Group Github: https://github.com/ArrowOS Code Review: review.arrowos.net WHAT WORKS?
[...]
1. Download The ROM & GApps
2. Wipe: System, Data, Dalvik, Cache,vendor
3. Flash ROM + GApps
4. Reboot & Enjoy
[...]
DOWNLOADS ROM: Click Here for ROM Gapps: Click Here for GApps Note : Pico, Nano or Micro Gapps are recommended. We don't prefer STOCK/HEAVY Gapps Source Code Device Sources Special thanks to AOSP LineageOS Ezio Lacandia Bijelkic Maxwen Alex Cruz scoute-dich Tibor Kaputa And all other Open Source - Developers,Teams and Organisations DM if we missed someone - you can always look at GitHub to find more contributors! :highfive: XDA:DevDB Information Arrow OS, ROM for the Xiaomi Redmi 3S Contributors Jayant_Deshmukh Source Code: https://github.com/ArrowOS Kernel source : https://github.com/Jayant-Deshmukh/android_kernel_xiaomi_msm8937_pie ROM OS Version: 9.x Pie ROM Kernel: Linux 3.x ROM Firmware Required: Latest MIUI Global Based On: AOSP Version Information Status: Beta Created 2018-09-09 Last Updated 2018-09-09
[...]
First unofficial build https://drive.google.com/file/d/1PDL5Zza2K-R3WaqLSX1UKrvQ0003EArH/view?usp=sharing Thanks to @Ani96
[...]
ABOUT ArrowOS is an AOSP based project started with the aim of keeping things simple, clean and neat. We added just the right and mostly used stuff that will be actually USEFUL at the end of the day. Website: https://arrowos.net Telegram: Channel| Group Github: https://github.com/ArrowOS Code Review: review.arrowos.net WHAT WORKS?
[...]
1. Download The ROM & GApps
2. Wipe: System, Data, Dalvik, Cache,vendor
3. Flash ROM + GApps
[...]
4. Reboot & Enjoy
[...]
2. Wipe:
[...]
DOWNLOADS ROM: Click Here for ROM Gapps: Click Here for GApps Note : Pico, Nano or Micro Gapps are recommended. We don't prefer STOCK/HEAVY Gapps Source Code Device Sources Special thanks to AOSP LineageOS Ezio Lacandia Bijelkic Maxwen Alex Cruz scoute-dich Tibor Kaputa And all other Open Source - Developers,Teams and Organisations DM if we missed someone - you can always look at GitHub to find more contributors! :highfive: XDA:DevDB Information Arrow OS, ROM for the Xiaomi Redmi 3S Contributors Jayant_Deshmukh Source Code: https://github.com/ArrowOS Kernel source : https://github.com/Jayant-Deshmukh/android_kernel_xiaomi_msm8937_pie ROM OS Version: 9.x Pie ROM Kernel: Linux 3.x ROM Firmware Required: Latest MIUI Global Based On: AOSP Version Information Status: Beta Created 2018-09-09 Last Updated 2018-09-09
[...]
Device related: * Official build * Mic fixed * Fp working right (report if not) Featured changelog: *System themes: Black, Dark *OmniJaws : lockscreen, statusbar weather *network traffic *status bar clock & date customisations *double tap to sleep status bar *double tap to sleep lockscreen *QS quick pull down *MicroG / Signature spoofying support added *many more optimizations, fixes. *Phh device updates https://sourceforge.net/projects/arrow-os/files/arrow-9.x/land/
[...]
New build of arrow is up https://sourceforge.net/projects/arrow-os/files/arrow-9.x/land/ Note: - Fp issue isnt fixed yet FPC users flash the zip if needed and goodix users don't flash the zip - Changelogs will be updated soon!

---

Title: [ROM][OFFICIAL][Pie][9.0] Arrow OS [WEEKLY]
URL: https://xdaforums.com/t/rom-official-pie-9-0-arrow-os-weekly.3884321/
Published: 2018-12-29T17:36:00.000Z
Author: mdeejay
Highlights:
[ROM][OFFICIAL][Pie][9.0] Arrow OS [WEEKLY] | XDA Forums
[...]
XDA Forums
[...]
* New posts
* Manufacturers
* What's new
[...]
New postsLatest
[...]
* Members
[...]
# [ROM][OFFICIAL][Pie][9.0] Arrow OS [WEEKLY]
[...]
* **Thread startermdeejay
* **Start dateDec 29, 2018
* **Home
* Forums
* Xiaomi
* Xiaomi Mi A1
* Xiaomi Mi A1 ROMs, Kernels, Recoveries, &amp; Other De
•••
#### Breadcrumb
[...]
* **Home
* Forums
* Xiaomi
* Xiaomi Mi A1
* Xiaomi Mi A1 ROMs, Kernels, Recoveries, & Other De
Search This thread
This thread
**Search titles only
[...]
logo.png
**ArrowOS**
​
**ABOUT**
**ArrowOS**is an AOSP based project started with the aim of keeping things simple, clean and neat. We added just the right and mostly used stuff that will be actually USEFUL at the end of the day.
**Website**:https://arrowos.net
**Telegram**:Channel|Group
**Github**:https://github.com/ArrowOS
**Code Review**:review.arrowos.net
**E-mail**:arrowos.contact
To apply for maintainershipCheck this out
**WHAT WORKS?**
* Almost everything
[...]
**WHAT DOESN'T WORK?**
* You tell meBe sure to include a log :check how to
**INSTRUCTIONS**
**Clean Flash**
1. Download The ROM & GApps
2. Wipe: System, Data, Dalvik, Cache
3. Flash ROM + GApps
4. Reboot & Enjoy**Dirty Flash**
1. Download the ROM
2. Wipe: Dalvik and Cache
3. Flash ROM (+Magisk if rooted previously or if want root)
4. Reboot & Enjoy
**• Magisk makes OTA unbootable, so flash Magisk Uninstaller and then install an update
•So, when OTA comes, just download it, flash Magisk Uninstaller and you're good to go. After boot up, flash GApps and Magisk. And do the same when next OTA comes**
**DOWNLOADS**
**ROM:**Click Here for ROM
**Gapps:**Click Here for GApps
**Note :**Pico, Nano or Micro Gapps are recommended. We don't prefer STOCK/HEAVY Gapps
Source Code
[...]
Device Sources:
device tree|kernel|vendor
**Special thanks to**
AOSP
LineageOS
[...]
Ezio Lac
[...]
Bijelkic
[...]
Tibor Kaputa
[...]
And all other Open Source - Developers,Teams and Organisations
[...]
DM if we missed someone - you can always look at GitHub to find more contributors! :highfive:
[...]
**XDA:DevDB Information**
**Arrow OS, ROM for the Xiaomi Mi A1**
**Contributors**
mdeejay,flex1911
**ROM OS Version:**9.0 Pie
**Kernel Version:**4.9.x
**Version Information**
**Status:**Stable
**Created**2018-12-29
**Last Updated**2018-12-29
Last edited:Dec 30, 2018
* **Reactions:TurkeyPro,apexashwin,AG14795and 15 others
mdeejay
[...]
logo.png
[...]
**ArrowOS**
​
**ABOUT**
**ArrowOS**is an AOSP based project started with the aim of keeping things simple, clean and neat. We added just the right and mostly used stuff that will be actually USEFUL at the end of the day.
**Website**:https://arrowos.net
**Telegram**:Channel|Group
**Github**:https://github.com/ArrowOS
**Code Review**:review.arrowos.net
**E-mail**:arrowos.contact
[...]
To apply for maintainershipCheck this out
[...]
**WHAT WORKS?**
* Almost everything
[...]
**WHAT DOESN'T WORK?**
* You tell meBe sure to include a log :check how to
[...]
**INSTRUCTIONS**
**Clean Flash**
1. Download The ROM & GApps
2. Wipe: System, Data, Dalvik, Cache
3. Flash ROM + GApps
4. Reboot & Enjoy**Dirty Flash**
1. Download the ROM
2. Wipe: Dalvik and Cache
3. Flash ROM (+Magisk if rooted previously or if want root)
4. Reboot & Enjoy
**• Magisk makes OTA unbootable, so flash Magisk Uninstaller and then install an update
•So, when OTA comes, just download it, flash Magisk Uninstaller and you're good to go. After boot up, flash GApps and Magisk. And do the same when next OTA comes**
**DOWNLOADS**
**ROM:**Click Here for ROM
**Gapps:**Click Here for GApps
**Note :**Pico, Nano or Micro Gapps are recommended. We don't prefer STOCK/HEAVY Gapps
[...]
**XDA:DevDB Information**
[...]
**Arrow OS, ROM for the Xiaomi Mi A1**
[...]
**Contributors**
mdeejay,flex1911
**ROM OS Version:**9.0 Pie
**Kernel Version:**4.9.x
**Version Information**
**Status:**Stable
**Created**2018-12-29
**Last Updated**2018-12-29
Dec 29, 2018View

---

Title: Downloads for : Xiaomi Redmi 4A | AndroidFileHost.com
URL: https://androidfilehost.com/?flid=306778&w=files
Published: N/A
Author: N/A
Highlights:
Downloads for : Xiaomi Redmi 4A | AndroidFileHost.com | Download GApps, Roms, Kernels, Themes, Firmware and more. Free file hosting for all Android developers.

- Membership Plans
- About
- Gapps
- Home
- Register Login

1. Pedro Pereira
2. Redmi 4A
3. Xiaomi
4. home

# Downloads for : Xiaomi Redmi 4A

1. Custom Rom
2. root

### Corvus OS

### Corvus_v3.5-rolex-24032020-UNOFFICIAL-1845.zip

153Downloads

717.6MBSize

Mar 24, 2020 | 07:28PMUpload Date

Download

### Corvus_v4.0-rolex-12042020-UNOFFICIAL-0943.zip

631Downloads

707.4MBSize

Apr 12, 2020 | 10:40AMUpload Date

Download

### Popular files

HIOS-2.2.0-V160-MX.zip for Uhans MX(MX)

3,068

MM-MOD-V4.1_P6.zip for -Android- Generic Device/Other

1,955

Validus-z5-7.1.2.STABLE.15.1-UNOFFICIAL-20180313-1550.zip for Leagoo Leagoo(Z5)

1,288

lineage-14.1-20180307-UNOFFICIAL-z5.zip for Leagoo Leagoo(Z5)

1,013

MM-Mod-V5_Alcatel-4034.zip for -Android- Generic Device/Other

896

### Other devices

- Redmi Note 7 Xiaomi
- MX Uhans
- Redmi 4A Xiaomi
- Leagoo Leagoo
- Generic Device/Other -Android-

--

---

Title: Xiaomi Redmi 4a ROMs, Kernels, Recoveries, & Other - XDA Forums
URL: https://xdaforums.com/f/xiaomi-redmi-4a-roms-kernels-recoveries-other.7304/
Published: N/A
Author: N/A
Highlights:
Improve your Xiaomi Redmi 4a's battery life, performance, and look by rooting it and installing a custom ROM, kernel, and more.
[...]
[ROM][rolex][UNOFFICIAL] LineageOS 14.1 for Redmi 4A [06/04/2018]
[...]
[ROM][PORT][8.1.0] Samsung Experience 9.5 for Redmi 4A (ROLEX)
[...]
[RECOVERY] [OFFICIAL] TWRP 3.2.1-0 for Xiaomi Redmi 4A [rolex] [20171210]
[...]
[KERNEL][P/9-Q/10] GoGreen Rolex[HM4A]
[...]
15.0][
[...]
Rolex/Riva
[...]
[ROM][10.0][rolex] Pixel Experience [AOSP][2019/12/26][DISCONTINUED]
[...]
[ROM][11][ROLEX/RIVA] PixelExperience [AOSP] [UNOFFICIAL]
[...]
[ROM][8.1.0_r52][OFFICIAL] AospExtended ROM V5.8 for Redmi 4A/5A [ROLEX/RIVA]
[...]
[ROM][9.0][rolex] Pixel Experience [AOSP][2019/12/12][DISCONTINUED]
[...]
[ROM][14.0][OFFICIAL][Non-RDP][Rolex/Riva] crDroid 10.x
[...]
13.
[...]
][OFFICIAL][Role
[...]
/Riva] crDroid 9.
[...]
[UNIFIED][RIVA][ROLEX][ROM][OFFICIAL][STABLE] DotOS 2.3
[...]
Triton-kernel [EAS] [Treble] [android-10^][4.9] [Redmi4A | Redmi5A]

---

Title: [ROM][v11.0] Arrow-OS [UNOFFICIAL][ROLEX/RIVA] | XDA Forums
URL: http://forum.xda-developers.com/t/rom-v11-0-arrow-os-unofficial-rolex-riva.4295147/
Published: 2021-06-22T04:41:35.000Z
Author: N/A
Highlights:
[ROM][v11.0] Arrow-OS [UNOFFICIAL][ROLEX/RIVA] | XDA Forums 

New posts
[...]
- Terms and rules
- Privacy

 

You are using an out of date browser. It may not display this or other websites correctly.You should upgrade or use an alternative browser.

 

 

# [ROM][v11.0] Arrow-OS [UNOFFICIAL][ROLEX/RIVA]
[...]
- Thread starter rajsharma55
- Start date Jun 22, 2021
- Tags arrow os custom rom redmi 4a redmi 5a riva rolex rom xiaomi redmi 4a xiaomi redmi 5a
[...]
4a Xiaomi
[...]
ABOUT ArrowOS is an AOSP/ CAF based project started with the aim of keeping things simple, clean and neat. Website: https://arrowos.net Telegram: Channel| TG Portal/Links Github: https://github.com/ArrowOS Code Review: review.arrowos.net E-mail: arrowos.contact PayPal: Donate to us Blog: blog.arrowos.net Checkout more documentation at (maintainership/contributing): Check this out WHAT WORKS?
[...]
Be sure to include a log : check how to DOWNLOADS Click here to Download Read our blog article/post about: * HOW-TO report a bug* GAPPS and VANILLA variants* Checking build integrity ROM Source: https://github.com/ArrowOS Kernel Source: https://github.com/rajsharma55/android_kernel_xiaomi_msm8917
[...]
Found actually NONE so far, it looks like a really stable build. I did some extensive testing but it's just SOLID. Probably battery life is a tad less than MIUI 10 but nothing extraordinary. Actually would be great to have this one OFFICIAL with updates etc Any chance on this @rajsharma55? Thank you for your efforts!
[...]
Works great! It seems to drain battery some when screen is
[...]
, but it is an old
[...]
with the original battery.
[...]
[RECOVERY] [OFFICIAL] TWRP 3.2.1-0 for Xiaomi Redmi 4A [rolex] [20171210]
[...]
[ROM][8.1.0_r52][OFFICIAL] AospExtended ROM V5.8 for Redmi 4A/5A [ROLEX/RIVA]
[...]
[ROM]-[Official]-[23.09.18]-Havoc-OS-[9.0]-[Rolex]-[Riva]
[...]
ArrowOS​
[...]
ABOUT ArrowOS is an AOSP/ CAF based project started with the aim of keeping things simple, clean and neat. Website: https://arrowos.net Telegram: Channel| TG Portal/Links Github: https://github.com/ArrowOS Code Review: review.arrowos.net E-mail: arrowos.contact PayPal: Donate to us Blog: blog.arrowos.net Checkout more documentation at (maintainership/contributing): Check this out WHAT WORKS?
[...]
Be sure to include a log : check how to DOWNLOADS Click here to Download Read our blog article/post about: * HOW-TO report a bug* GAPPS and VANILLA variants* Checking build integrity ROM Source: https://github.com/ArrowOS Kernel Source: https://github.com/rajsharma55/android_kernel_xiaomi_msm8917
```

---

## Assistant (Plan · Big Pickle · 6.5s)

_Thinking:_

ArrowOS for Redmi 4A (rolex) is only available as an unofficial Android 11 build from mid-2021. It hasn't been updated since. Let me summarize the findings.

ArrowOS was available for Redmi 4A as an **unofficial Android 11 build** only (by rajsharma55, last updated June 2021). It's been **abandoned** — no updates, no Android 12/13/14/15 builds, and it was never official.

Based on XDA feedback: stable and bug-free, but reviewers noted "battery life is a tad less than MIUI" and "drains battery some when screen is on." Slightly worse battery than crDroid or AEX.

**Verdict:** Not worth it today. Dead project with no security patches since 2021. Stick with **crDroid 9.x (Android 13)** or **AEX** — both are lighter, better optimized, and have proper kernel-level battery tuning for this device.

---

## User

what about stock android?

---

## Assistant (Plan · Big Pickle · 10.6s)

_Thinking:_

The user is asking about "stock Android" for the Redmi 4A. This could mean:

1. AOSP (Android Open Source Project) - pure, unmodified Android
2. Stock MIUI that ships with the phone

Given the context of our conversation about custom ROMs for best performance and battery life, they're likely asking about pure AOSP-based ROMs vs the custom ROMs we've discussed. Let me think about what "stock Android" options exist for Redmi 4A.

For Redmi 4A, there isn't an official "stock Android" ROM from Xiaomi - it ships with MIUI. But there are AOSP-based ROMs that are very close to stock Android:

1. **Pixel Experience** - This is the closest to "stock Android" / Pixel Android. It was available for Redmi 4A but discontinued at Android 11.

2. **AOSP Extended (AEX)** - Also close to stock with minimal customizations.

3. **LineageOS** - Also close to AOSP

4. **ArrowOS** (which we just discussed) - positions itself as "simple, clean, and neat" AOSP-based

But there's actually a key distinction I should make. Some users who ask about "stock Android" might mean the actual stock MIUI ROM that comes with the phone. Given our conversation about custom ROMs, I think they're asking about pure AOSP/Google Android experience.

Let me search for information about pure stock Android options for Redmi 4A.

**Tool: websearch**

**Input:**
```json
{
  "query": "Pixel Experience Redmi 4A rolex AOSP stock Android ROM battery performance",
  "numResults": 5
}
```

**Output:**
```
Title: [ROM][9.0][rolex] Pixel Experience [AOSP][2019/12/12][DISCONTINUED] | XDA Forums
URL: https://xdaforums.com/t/rom-9-0-rolex-pixel-experience-aosp-2019-12-12-discontinued.3920102/
Published: 2019-04-10T14:16:57.000Z
Author: N/A
Highlights:
PixelExperience for Xiaomi Redmi 4A[rolex] What is this? Pixel Experience is an AOSP based ROM, with Google apps included and all Pixel goodies (launcher, wallpapers, icons, fonts, bootanimation) Our mission is to offer the maximum possible stability and security, along with essential and useful features for the proper functioning of the device Based on Android 9.0 Whats working? Wifi RIL Mobile data GPS Camera Flashlight Camcorder Bluetooth FMRadio Lights Sound / vibration Facelock Known issues Nothing DON'T FLASH GAPPS, ALREADY INCLUDED Download from my Google Drive Donate Liked my work? Give me a beer Translation Help with project translation Stay tuned Our Telegram channel Our blog​
[...]
- Android OS version: 9.0.0
[...]
- Security patch level: December 2019
[...]
- Build author/Device Maintainer: dandyfarid
[...]
- Device Source code: https
[...]
github.com/PixelExperience-Devices
[...]
- Source code: https://github.com/
[...]
ROM Developer: jhenrique09
[...]
XDA:DevDB Information Pixel Experience, ROM for the Xiaomi Redmi 4A Contributors dandyfarid, sunnyraj84348, muralivijay Source Code: https://github.com/PixelExperience ROM OS Version: 9.x. Pie ROM Kernel: Linux 3.18. ROM Firmware Required: V10.2.3.0.NCCMIXM TWRP Required: here Based On: AOSP Version Information Status: Stable Created: 10/04/2019 Last Updated: 12/12/2019
[...]
Changelog: 10/04/2019 - Enable bootanimation Half res - Add Custom Hotplug folder - Add Alucard Hotplug - Add Thunderplug Hotplug - Correct blobs entry - Set Zram 1 GB - arm64: Cortex-A53/ARMv8 optimizations for msm8917/20/37/40/52/53/sdm450 - prima: Merge tag 'LA.UM.7.6.r1-04300-89xx.0 - Merge tag 'LA.UM.7.6.r1-04300-89xx.0 - rolex_defconfig: update config - rolex_defconfig: disable VGA_ARB - staging: prima: Correct the ini value to enable default sap interface - msm: kgsl: Remove POPP - Enable Simple GPU Algorithm - Enable State Notifier - Enable Adreno Idler - Enable KCAL color control - Merge Tag v3.18.138 [EOL] from kernel.org - Enable Wireguard - Enable PowerSuspend driver - Add Nightmare Governor - Add DanceDance Governor - Add Intelliactive Governor
[...]
Changelog 13-04-2019 - Rebased new tree ( Thanks to sunnyraj84348 ) - power: Kill "Failed to acquire lock" log - Selinux Still permisive - Use Stock Kernel ( No features in kernel now ) - Merge tag 'LA.UM.7.5.r1-04500-8x96.0' in kernel - Merge tag 'LA.UM.7.5.r1-04500-8x96.0' in Media HAL - Merge tag 'LA.UM.7.5.r1-04500-8x96.0' in Display HAL Clean Flash Highly recomended !!!
[...]
PixelExperience for Xiaomi Redmi 4A[rolex] What is this? Pixel Experience is an AOSP based ROM, with Google apps included and all Pixel goodies (launcher, wallpapers, icons, fonts, bootanimation) Our mission is to offer the maximum possible stability and security, along with essential and useful features for the proper functioning of the device Based on Android 9.
[...]
Whats working?
[...]
Camera Flashlight Cam
[...]
Bluetooth FMRadio
[...]
Facelock Known issues Nothing DON'T FLASH
[...]
INCLUDED Download from my
[...]
.x. Pie ROM Kernel: Linux 3.18. ROM Firmware Required
[...]
V10.2.3.0.NCCMIXM TWRP Required: here Based On:
[...]
OSP Version Information Status
[...]
Stable Created:
[...]
10/04/2
[...]
Updated: 12/
[...]
2019
[...]
: Update to LA
[...]
.r1
[...]
4500-
[...]
xx.0
[...]
sepolicy: Add sepolicy
[...]
Revert "netfilter:Notify user
[...]
- Enable PowerSuspend driver
[...]
Enable Wireguard
[...]
Enable KCAL color control - Enable Adreno Idler - Enable State Notifier - Enable Simple GPU Algorithm - add Lionheart govover
[...]
add Bioshock governor - Added
[...]
Remove POPP - Added Alucard
[...]
drive.google.com/file/d
[...]
drivesdk
[...]
Changelog 23-04-2019 - Fix Launcher lags - Set LMK Parameter to very light - audio: Merge LA.UM.7.6.r1-04500-89xx.0 - overlay: Enable Swipe-up home gesture - Remove deprecated/useless flags PE Changelog: * Merged new CAF tag: LA.UM.7.3.r1-07400-sdm845.0 * Performance improvements * Others fixes

---

Title: List of Redmi 4A (Rolex) Custom Roms | XDA Forums
URL: http://forum.xda-developers.com/t/list-of-redmi-4a-rolex-custom-roms.3774162/
Published: 2018-04-06T13:31:33.000Z
Author: N/A
Highlights:
Add Bootleggers & Omni into the list too. Also Pixel Experience booted with no bugs. And if there is a dedicated thread of the ROM, post it's link. Not the direct download link.
[...]
Add Bootleggers & Omni into the list too. Also Pixel Experience booted with no bugs. And if there is a dedicated thread of the ROM, post it's link. Not the direct download link.
[...]
Use AEX Extended,
[...]
drain is amazing
[...]
Bootleggers proved best battery friendly and stable rom so far. Cheers
[...]
files&flid=262207 NucleaRom Nougat https://androidfilehost.com/?fid=746010030569968012
[...]
73956719
[...]
39820511 Infinity Kernel for
[...]
3775549 View attachment
[...]
latest roms. Because the previous thread https://xdaforums.com
[...]
-------------------------------- CrDroid
[...]
Thread--------------------------------------------------------------------------------
[...]
---------------- AEX OREO | Build by Erik Garcia (ECr
[...]
v3) https://downloads.
[...]
xtended.com
[...]
XDA Thread----------------
[...]
------------------------------------------------
[...]
REO |: XDA Thread---------------------------------------------------------------------------------------------------------------- FrankenRom 13.5 OREO |: XDA by
[...]
---------------------------------------------------------------------------------------------------------------- Pixel Experience [AOSP] [r1] | OREO |: XDA Thread---------------------------------------------------------------------------------------------------------------- AtomicOS OREO |: XDA Thread Note: No Updates ----------------------------------------------------------------------------------------------------------------
[...]
8.1
[...]
FFICIAL XDA Thread by
[...]
XDA Thread by shar
[...]
these: 8.1 Oreo: • Ressurection Remix (Official)• crDroid (Official)• Project Xtended (Official)• AtomicOS (Official)• LineageOS 15.1 (Unofficial)• Candy8
[...]
1 (Unofficial)• Cardinal AOSP (
[...]
Firehound (

---

Title: [ROM][11][ROLEX/RIVA] PixelExperience [AOSP] [UNOFFICIAL] | XDA Forums
URL: https://forum.xda-developers.com/t/rom-11-rolex-riva-pixelexperience-aosp-unofficial.4233351/
Published: 2021-02-13T19:30:28.000Z
Author: N/A
Highlights:
[ROM][11][ROLEX/RIVA] PixelExperience [AOSP] [UNOFFICIAL] | XDA Forums
[...]
# [ROM][11][ROLEX/RIVA] PixelExperience [AOSP] [UNOFFICIAL]
[...]
[ROM][11][ROLEX/RIVA] PixelExperience [AOSP] [UNOFFICIAL]
[...]
PixelExperience for Redmi4A/5A [rolex/riva] What is this? PixelExperience is an AOSP based ROM, with Google apps included and all Pixel goodies (launcher, wallpapers, icons, fonts, boot animation) Our mission is to offer the maximum possible stability and security, along with essential and useful features for the proper functioning of the device Based on Android 11 Whats working? Wi-Fi RIL Mobile data GPS Camera Flashlight Camcorder Bluetooth FM radio Fingerprint reader Face unlock NFC Lights Sound/vibration Known issues Nothing yet You tell me DON'T FLASH GAPPS, THEY'RE ALREADY INCLUDED Download PixelExperience Donate Liked my work? Give me a beer Translation Help with project translation Stay tuned Our Telegram channel Our blog​
[...]
- Android OS version: 11.0.0_r29
- Security patch level: February 2021
- Device Source code: https://github.com/Thagoo/android_device_xiaomi_rolex/tree/eleven
- Kernel Source code: https://github.com/Thagoo/platform_kernel_xiaomi_msm8917
- Source code: https://github.com/PixelExperience
- ROM Developer: jhenrique09
[...]
Can i install this ROM with dirty flash? Mine is PE+ based andro 10. And when dirty flash the files and apps still there not to be uninstalled? (just up android)
[...]
Can i install this ROM with dirty flash? Mine is PE+ based andro 10. And when dirty flash the files and apps still there not to be uninstalled? (just up android)
[...]
Backup your data (excluding internal storage) so you can restore if anything goes wrong
[...]
How much internal takes to backup? And i wanna know how to copy data and obb on android 11 (have been rooted device). Already try anything but still don't wanna copy paste file/folder
[...]
Use mixplorer file manager
[...]
Use mixplorer file manager
[...]
Still can't show folder and copy paste there. ZArchive same issue
[...]
need face unlock on next update and button to customizable style (like date and clock am-pm, etc)
[...]
Battery percentage 0 after installing and rebooting again
[...]
Battery percentage 0 after installing and rebooting again
[...]
Fixed by clean flashing
[...]
Couple bugs- No face unlock contrary to what is written Phone light keeps flashing even if no notifications cant charge above 75%
[...]
[ROM][11][ROLEX/RIVA] PixelExperience [AOSP] [UNOFFICIAL]
[...]
PixelExperience for Redmi4A/5A [rolex/riva] What is this? PixelExperience is an AOSP based ROM, with Google apps included and all Pixel goodies (launcher, wallpapers, icons, fonts, boot animation) Our mission is to offer the maximum possible stability and security, along with essential and useful features for the proper functioning of the device Based on Android 11 Whats working? Wi-Fi RIL Mobile data GPS Camera Flashlight Camcorder Bluetooth FM radio Fingerprint reader Face unlock NFC Lights Sound/vibration Known issues Nothing yet You tell me DON'T FLASH GAPPS, THEY'RE ALREADY INCLUDED Download PixelExperience Donate Liked my work? Give me a beer Translation Help with project translation Stay tuned Our Telegram channel Our blog​
[...]
- Android OS version: 11.0.0_r29
- Security patch level: February 2021
- Device Source code: https://github.com/Thagoo/android_device_xiaomi_rolex/tree/eleven
- Kernel Source code: https://github.com/Thagoo/platform_kernel_xiaomi_msm8917
- Source code: https://github.com/PixelExperience
- ROM Developer: jhenrique09

---

Title: Install Xiaomi Redmi 4A/Prime Pixel Experience Pie 9.0 Official ROM - Android Infotech (May 2026)
URL: https://www.androidinfotech.com/redmi-4a-prime-pixel-experience-pie/
Published: 2019-10-26T08:25:36.000Z
Author: Selva Ganesh
Highlights:
Most of the Xiami old phones are running great with Custom ROMs. By flashing these ROMs, you can experience the latest Android versions. In this list, Redmi 4A and Prime have the Official Marshmallow version. When we flash Pixel Experience ROM, we can use Pie 9.0 version on your mobile. You need Custom Recovery to do this. I also attached the link to do this. When you are a regular user, you may feel confused and thought about some Custom ROM issues. But, When we have Official versions, they are mostly bugs free and will receive regular patch updates like Stock ROM. After this, you can use this mobile as your secondary device, or If you are satisfied with the experience, you can use it as your Primary mobile for basic tasks and some heavy usage too. When we tested using PUBG, it gives Ok Experience. If you are a Developer or regular root apps user, you can follow the below guide to flash Pixel Experience ROM on your mobile.
[...]
We are thanks for the Hard Work of the Pixel Experience OS team and Maintainers Granrage and dandyfarid (Yuu_Koito). Without this team, this method is not possible. Your mobile has 2-3 GB of RAM. It is more than enough for normal usage. Your mobile will not receive regular patch updates officially from Xiaomi; Coming to CPU- Your mobile has a Mid-Range-level Qualcomm MSM8917 Snapdragon 425 (4A) and Qualcomm MSM8953 Snapdragon 625 (Prime) Processors. Coming to OS, It is MIUI OS With some added Custom Skin Xiaomi features. Some users prefer Pure Android. If you are a one, you can use this official Pixel Experience ROM. It is near the Stock Android with a lot of features. You can experience most of the Pixel phone features.
[...]
If we optimize correctly with correct OS after rooting, we can see some Improvements. So, after rooting, I can expect a Lag-free experience? Probably. Also, if we hibernate and eliminate a lot of unwanted apps and optimize some apps, your device is hardware limited. But, within these limits, we can enhance the performance by 30-40% compared with your old usage. If you use Pixel Experience Custom ROMs, you can expect a 50-80% improvement in performance.
[...]
. Verizon devices come with locked Bootloader.
[...]
rooted. Also
[...]
TWRP recovery or any
[...]
custom recovery file/app alike
[...]
With the help of TWRP Recovery, you can quickly flash the latest version of Pixel Experience ROM into your Redmi 4A/Prime. Before sharing the tutorial, you may want to know that, with the TWRP recovery present on your device, you can easily install any custom ROM or firmware. Does it seem complicated? Relax, everything will be explained succinctly in bullets. If you didn’t root your mobile, Refer- Root Xiaomi Redmi 4A/Prime.
[...]
Make sure your device battery is charged above 50%
[...]
- Android Pie 9.0 Stock Android ROM with System-Wide Color options available. Dark, Grey themes are also available.
[...]
- Digital Wellbeing- Optimize your time with Social Network interaction.

- Adaptive Battery- Better Battery optimization.

- Improved Gesture navigation compared with the Oreo version and most of the features available in Pixel devices.
[...]
Redmi 4A/Prime is a Mid-level Mobiles; We can expect Some Improvement After Rooting. But, If you use Pixel Experience Custom Roms, you can expect a considerable performance Improvement and Clear UI. So, If you have little knowledge in rooting, flash, you can flash Pixel Experience Custom ROM. If you flash other Custom ROM, check what is working and what is not working. It is wise to use Some Official Custom ROMs like Lineage or Pixel Experience. You will not get issues in HD streaming services like Netflix and Amazon Prime. Most of the Banking apps Will work without problems. Also, they have Improved Pie Gestures.

---

Title: Install Pixel Experience ROM on Xiaomi Redmi 4A (Android 8.1 Oreo)
URL: https://androidxda.net/install-pixel-experience-rom-xiaomi-redmi-4a-android-8-1-oreo/
Published: 2018-05-13T17:45:54.000Z
Author: Aamir Jamal
Highlights:
Install Pixel Experience ROM on Xiaomi Redmi 4A (Android 8.1 Oreo)
[...]
Here is a detailed guide on how to install Pixel Experience ROM on Xiaomi Redmi 4A (Android 8.1 Oreo). Being an advanced Xiaomi Redmi 4A user, you’ll be happy to know that the Pixel Experience ROM is now available for these devices. This custom ROM is based on the latest Android 8.1 Oreo and you can enjoy the unofficial Android Oreo by using this Custom ROM. Xiaomi Redmi 4A (rolex) is one of the best budget smartphones out there and launched on November 2016. This mid-range Android phone came out of the box with Android 6.0.1 Marshmallow. Now you can download and install Pixel Experience ROM on Xiaomi Redmi 4A (rolex).
[...]
Google Pixel Experience ROM on Xiaomi Redmi 4A brings the real ROM and it has all the features and applications which comes with Google Pixel smartphone out of the box. Go ahead and follow the given guide to install the new Custom ROM based on AOSP Android 8.1 Oreo for Xiaomi Redmi 4A known as Pixel Experience. Now you can download and install the AOSP Android 8.1 Oreo for Xiaomi Redmi 4A (rolex). After installing this ROM, you can enjoy:
[...]
Here you can download and install Google Pixel Experienced ROM for Xiaomi Redmi 4A based on Android 8.1 Oreo. The ROM is stable and can be used as a daily driver.
[...]
All you need to unlock bootloader and then Install TWRP Recovery on your Xiaomi Remi 4A to install this ROM.
[...]
- You must install TWRP or any Custom Recovery on your phone.
- You can also backup all your apps without Root
- Create a proper Backup of your phone before doing this step using TWRP or CWM or any Custom Recovery.
- Download Xiaomi USB Drivers on your PC.
- The battery level of your phone should be at least about 70 to 80% before proceeding to the installation.
- Keep in mind that the ROM given in this guide is working only with Xiaomi Redmi 4A (rolex). Do not try to flash this ROM on any other device or incorrect variants.
[...]
1. Now boot into TWRP Recovery, Here is the method to boot into Recovery.
2. Download the below Android 8.1 Oreo for Xiaomi Redmi 4A.
3. Unlock Bootloader on Xiaomi Redmi 4A
4. Download all the Zip files from below and transfer it to root folder of your phone’s internal memory.
[...]
- Download Android Oreo Gapps
- Pixel Experience ROM
[...]
Done! You have successfully installed Google Pixel Experience ROM on Xiaomi Redmi 4A. Let us know in the comments area below if you have any issues or queries.
```

**Tool: websearch**

**Input:**
```json
{
  "query": "Redmi 4A stock MIUI vs custom ROM battery performance comparison",
  "numResults": 5
}
```

**Output:**
```
Title: Why is the battery life so much worse on custom ROMs compared to ...
URL: https://xdaforums.com/t/why-is-the-battery-life-so-much-worse-on-custom-roms-compared-to-miui-13.4525633/
Published: 2022-12-02T06:49:46.000Z
Author: N/A
Highlights:
I've been trying a few custom ROMs (ArrowOS and Ricedroid) and a few custom kernels (Vantom and Sleepy) and I've noticed that the battery life is just worse. I went from an active drain of 10%/hr and an idle drain of 0.5%/hr (on debloated MIUI) to an active drain of around 12-15%/hr and an idle drain of 0.8-1.0%/hr (on Ricedroid+Sleepy, best one so far in my experience), which is an obvious increment in comparison. I've also seen a huge number of people complaining about terrible drain on basically every custom ROM I've seen on here. It's confusing because performance also seems to take a hit, so it's an overall worse experience, outside of the additional functionality which is often pretty great (both ArrowOS and Ricedroid look amazing). So why is the battery life so much better on MIUI compared to these almost (?)-AOSP custom ROMs? What can I do to further increase battery life AND performance?
[...]
Because MIUI has too aggressive battery management which result in apps not working as it should (i.e notification not coming). One of the reasons I use custom rom.
[...]
I've also seen a huge number of people complaining about terrible drain on basically every custom ROM I've seen on here. It's confusing because performance also seems to take a hit, so it's an overall worse experience, outside of
[...]
I´d suggest that you apply GMS Doze magisk module, Naptime app (from Francisco Franco, which also includes a magisk module) and also apply restrictions on battery usage of most Google stuff. That really makes a difference. I haven´t tried it yet on the RN10PRO (as my bootloader only unlocks this Sunday), but on Poco F2 Pro, while using Ricedroid and Immensity Kernel - these dozing/restriction tricks made active drain stay around 8%/hr (vs 12.5%/hr previously) and idle drain to go down to 0.4%/hr (vs 1.1%/hr previously). Good luck
[...]
Yeah, my stock MIUI was terrible both performance-wise and battery-wise, but after debloating it (by disabling basically every Xiaomi service / app) my phone was flying with amazing battery. I'm guessing that you've flashed the vanilla / degoogled ROM, right? This sounds like a good idea. I flashed the gapps version and my experience was not nice, and just restricting Google Services' battery usage made my phone go 0.1%/hr overnight which is insane. Though, active drain remains insanely high around 15%/hr... Can't find out why
[...]
I've been trying a few custom ROMs (ArrowOS and Ricedroid) and a few custom kernels (Vantom and Sleepy) and I've noticed that the battery life is just worse. I went from an active drain of 10%/hr and an idle drain of 0.5%/hr (on debloated MIUI) to an active drain of around 12-15%/hr and an idle drain of 0.8-1.0%/hr (on Ricedroid+Sleepy, best one so far in my experience), which is an obvious increment in comparison. I've also seen a huge number of people complaining about terrible drain on basically every custom ROM I've seen on here. It's confusing because performance also seems to take a hit, so it's an overall worse experience, outside of the additional functionality which is often pretty great (both ArrowOS and Ricedroid look amazing). So why is the battery life so much better on MIUI compared to these almost (?)-AOSP custom ROMs? What can I
[...]
I´d suggest that you apply GMS Doze magisk module, Naptime app (from Francisco Franco, which also includes a magisk module) and also apply restrictions on battery usage of most Google stuff. That really makes a difference. I haven´t tried it yet on the RN10PRO (as my bootloader only unlocks this Sunday), but on Poco F2 Pro, while using Ricedroid and Immensity Kernel - these dozing/restriction tricks made active drain stay around 8%/hr (vs 12.5%/hr previously) and idle drain to go down to 0.4%/hr (vs 1.1%/hr previously). Good luck
[...]
Because MIUI has too aggressive battery management which result in apps not working as it should (i.e notification not coming). One of the reasons I use custom rom.
[...]
12.1 vs

---

Title: Principal Custom ROMs to Redmi 4A | XDA Forums
URL: http://forum.xda-developers.com/t/principal-custom-roms-to-redmi-4a.3639372/
Published: 2017-07-20T03:07:25.000Z
Author: N/A
Highlights:
Hi Brothers,today i share principal roms avaliable to this device,i dont developed,only share 00 - Xperience11.2 (android 7.1.2) ROM Booting Now, Agoust Patch Download01---------------------------------------------------------------------------------------------------------------------------------- 01 - Lineage13 (july update/july patch) IR BUG - Thanks CarlosArriagaCM (dev) - Download Link Working Now---------------------------------------------------------------------------------------------------------------------------------- 02 - ResurrectionRemix-M-v5.7.4 (july update/january patch)IR BUG - Thanks CarlosArriagaCM (dev) - Download---------------------------------------------------------------------------------------------------------------------------------- 03 - Lineage14.1 (july update/july patch) (ATENTION,ROM DONT BOOT,ONLY SHARED TO OTHERS DEVS) - Thanks CarlosArriagaCM (dev) Download---------------------------------------------------------------------------------------------------------------------------------- 04 - Flyme6 (july update/january patch) Camera BUG (dont record videos in any time) install Cameringo to Fix - Thanks manucarcor (dev) Download- ---------------------------------------------------------------------------------------------------------------------------------- 05 - Mokee 6.0.1 (june update/april patch) - Camera BUG (dont record videos in any time) install Cameringo to Fix - Thanks manucarcor (dev) - Download---------------------------------------------------------------------------------------------------------------------------------- 06 - Mokee 7.1.1 (april update/january patch) - Camera BUG (dont record videos in any time) install Cameringo to Fix/much Fc´s - Thanks manucarcor (dev) Download---------------------------------------------------------------------------------------------------------------------------------- 07 - SM6.0.1 (april update/april patch) IR BUG - Thanks manucarcor (dev) Download---------------------------------------------------------------------------------------------------------------------------------- 08 - ResurrectionRemix-N-v5.8.0(april update/january patch) Camera BUG (dont record videos in any time) install Cameringo to Fix/much Fc´s - Thanks manucarcor Download---------------------------------------------------------------------------------------------------------------------------------- 09 - MIUI Pro (Thanks all miui pro team) https://www.androidfilehost.com/?fid=673368273298973720 Download(dev) -
[...]
The 01 - Lineage13 Rom,only have IR BUG,i use in daily driver and work smooth,one nice way to get performance
[...]
Lineage13, is stable enough for daily use.
[...]
how about the battery life?​
[...]
Unfortunately it is not of the level of the miui, but, acceptable 5/6hours of screen time
[...]
Just installed Line
[...]
13 and it didn't pass SafetyNet at the
[...]
, after installing Magisk
[...]
WoW, thank u so much for feedback, Lineage13 is really most stable of the list of roms
[...]
Hi Brothers,today i share principal roms avaliable to this device,i dont developed,only share 00 - Xperience11.2 (android 7.1.2) ROM Booting Now, Agoust Patch Download01---------------------------------------------------------------------------------------------------------------------------------- 01 - Lineage13 (july update/july patch) IR BUG - Thanks CarlosArriagaCM (dev) - Download Link Working Now---------------------------------------------------------------------------------------------------------------------------------- 02 - ResurrectionRemix-M-v5.7.4 (july update/
[...]
patch)IR BUG - Thanks CarlosAr
[...]
agaCM (dev) - Download---------------------------------------------------------------------------------------------------------------------------------- 03 - Lineage
[...]
uly update/
[...]
(ATENTION,ROM D
[...]
BOOT,
[...]
Thanks CarlosAr
[...]
The 01 - Lineage13 Rom,only have IR BUG,i use in daily driver and work smooth,one nice way to get performance

---

Title: List of Best Custom ROM for Xiaomi Redmi 4A [Updated]
URL: https://www.getdroidtips.com/custom-rom-xiaomi-redmi-4a/
Published: 2017-12-07T12:21:04.000Z
Author: Mohammed Huwais
Highlights:
When you buy a brand new Android device, it comes equipped with a “Stock ROM,” also known as the “Stock Firmware”. The stock ROM is the preinstalled operating system on your device. The stock ROM has limited functionalities that are defined by the phone’s manufacturer. If you wish to have extra features added to your device, then you will have to resort to custom ROM.
[...]
As you all know Android is an open-source platform where a developer can take all the source code from Google and build their own operating system images for Android phones and tablets from scratch. This Custom or Home built app is known as Custom ROM. Custom ROM replaces your Android Operating system (Stock ROM) which comes with your Phone or Tablet. It comes with a kernel which makes it a fully standalone OS. So some developers in Android Community will customize the Android OS by stripping all the Garbage and making it a pure Android experience with no carrier-installed app or OEM apps.
[...]
AOSP Extended ROM is based on the AOSP Source code which brings a lot of various cherry-picked commits from multiple other projects. Being based on AOSP, it provides a smooth and lag-free experience out of the box. The developer of AOSP Extended has promised to add many new features and make it even better for future updates.
[...]
ArrowOS is a new Custom ROM and it is AOSP inspired open-source project started with the aim of keeping things simple, clean, and neat. The ROM brings almost the same feature which is very useful for ROM customization and in the end aims to deliver smooth performance with better battery life.
[...]
ViperOS is a new Custom Firmware based on the AOSP code but has its own custom mods. This ROM is quite famous for its custom-made features from all CM, Lineage, Slim, Omni AOSPA, etc. The ROM was developed when Google released the code for Android 7.1 Nougat. Now it has become one of the most stable Custom firmware with many features and customization. It offers a great balance between battery and performance.
[...]
crDroid is designed to increase performance and reliability over stock Android for your device also attempting to bring many of the best features existent today. We’re mainly based on Lineage OS so use custom kernels compatible with them!
[...]
Resurrection Remix is a combination of the stability provided by CM and features from Slim, Omni, and original Remix builds providing an awesome combination of performance, customization, power, and the newest features brought directly to your device. This ROM is ultimately full-featured, stable, and combined with the best features of open source ROMs. The ROM is also providing a lot of awesome original Resurrection Remix ROM add-on s in the builds which include the best of performance, customization, power, and the newest features of your device!
[...]
### MIUI:
[...]
MIUI 13 is the latest iteration of MIUI ROM developed by Xiaomi company. It is also used in many devices as a custom ROM. It is developed based on the Android Operating system. The ROM comes with many features such as Theme support, Customization of the Status bar, Mi Launcher without an app drawer, and many other features.
[...]
Paranoid Android is one popular custom ROM built with many new innovative features, a slick user interface, improved performance, and battery backup.

---

Title: Xiaomi Redmi 4A Unboxing Quick Review Gaming Battery And Benchmarks
URL: https://gadgetstouseaj.pages.dev/posts/xiaomi-redmi-4a-unboxing-quick-review-gaming-battery-and-benchmarks
Published: 2023-04-14T00:00:00.000Z
Author: Kenneth Tipler
Highlights:
Featuring a 5 inch display and a quad-core processor, the Redmi 4A is a cheaper version of the Redmi 4. It comes with 2GB RAM and misses out on the fingerprint sensor.
[...]
## Gaming Performance#
[...]
We tested Dead trigger 2 as the light game and Asphalt 8 as the heavy one on the Redmi 4A. The phone performed really well in terms of graphics and sound management. I didn’t face any lag or frame drops while playing Dead Trigger 2. We expected to see lags and frame drops in the Asphalt 8 as its a heavy game, but yet again there were no major lags. Graphics are well handled by Adreno 308. All over it was a smooth experience.
[...]
Battery dropped by 4% after 15 minutes gaming session of Dead Trigger 2. On the other hand Asphalt 8 for 15 minutes dropped the battery by 6% in 15 minutes. Phone didn’t get too hot but got a little warm after both the sessions.
[...]
The entry level smartphone segment in India is fiercely competitive. While Xiaomi has been a very competitive player for a while now with its Redmi 3S, the Redmi 4A takes the fight to even lower price points. Offering a decent experience with its custom skin, the Redmi 4A seeks to build on the brand value of the Redmi series by targeting more people than ever with an even lower price.

---

Title: Xiaomi Redmi 4A Custom ROM Installation (Easiest Way)
URL: https://www.rootingsteps.com/xiaomi-redmi-4a-custom-rom/
Published: 2024-01-20T21:45:06.000Z
Author: Olivia Smith
Highlights:
Want to upgrade your Xiaomi Redmi 4A phone beyond the limitations of MIUI/ HyperOS by installing an enriched custom ROM? This guide details the easiest method to flash powerful third-party firmware options using TWRP recovery.
[...]
Custom ROMs based on Pixel Experience, AOSP or LineageOS open up features like GPU overclocking, themed interfaces, latest Android updates, widened app compatibility and more. You can unleash your Xiaomi Redmi 4A’s full potential with some care.
[...]
Our instructions are for the Xiaomi Redmi 4A, but they also apply to other Xiaomi models. Follow each step closely to safely transition away from a Stock OS to a
[...]
OS catered to your needs.
[...]
A custom ROM is an aftermarket firmware developed by independent developers and installable on Android devices to replace the stock OS.
[...]
These provide more options tailored to user needs that manufactured ROMs like MIUI/ HyperOS on Xiaomi phones often lack. Developers build custom ROMs for Android by extensively modifying open-source Android codebases like Pixel Experience, LineageOS or AOSP.
[...]
- There is a Privacy issue in Custom ROM as third-party developers develop it. But you can always trust XDA Developers for downloading Custom ROM.
- You cannot use Banking Apps like PayPal, Payoneer, etc.
- An Unstable ROM will impact the performance of the Xiaomi Redmi 4A device.
- If you install, Unstable ROM may affect device performance.
- There are chances of bricking your device.
- Installing, a Custom ROM will void your warranty.
[...]
- This method is only for the Xiaomi Redmi 4A smartphone. Please do not try this method on any other smartphone. Otherwise, it will brick your phone.
- Take a full backup of your Android, as installing Custom ROM will erase all your data.
- You need to Root your Xiaomi Redmi 4A smartphone.
- Moreover, fully charge your phone.
- You need to have TWRP Recovery on Xiaomi Redmi 4A. Without TWRP, you cannot flash Custom ROM to your Xiaomi Redmi 4A smartphone.
- Make sure to Unlock Bootloader on Xiaomi Redmi 4A.
[...]
The first Boot may take 5–10 minutes, so please don’t panic. Do not touch your phone until it boots up. Otherwise, it may brick your Xiaomi Redmi 4A device.
[...]
These steps will install a custom ROM on your Xiaomi Redmi 4A device, unlocking capabilities beyond stock OS limitations. If any issues emerge when flashing, please comment with details so we can provide troubleshooting assistance.
```

---

## Assistant (Plan · Big Pickle · 12.6s)

_Thinking:_

The user is asking about "stock Android" for the Redmi 4A. Let me think about what this means:

1. **Stock MIUI** - The original ROM that came with the phone. Redmi 4A shipped with Android 6.0.1 Marshmallow and MIUI. The latest official MIUI version would be MIUI 11 based on Android 7.1 (if I recall correctly). But this is MIUI, not stock Android.

2. **Pixel Experience / AOSP** - "Stock Android" in the custom ROM world usually means a ROM that is close to Google's AOSP / Pixel Android without manufacturer customizations like MIUI. The closest options would be:
   - Pixel Experience (discontinued for rolex after Android 11)
   - AOSP Extended (AEX) - discontinued after Android 9
   - LineageOS (closest to AOSP but with some enhancements)
   - crDroid (based on LineageOS, so close to AOSP)

3. **GSI (Generic System Image)** - There's also the option of flashing a Project Treble GSI, which is pure AOSP. Since Redmi 4A supports Treble, you can flash a pure AOSP GSI. This would be the closest to "stock Android" - you can flash a vanilla AOSP GSI from developers like phhusson.

The key point is: Redmi 4A **never had stock Android from the factory**. It came with MIUI. If you want pure AOSP/Google Android, you need a custom ROM.

For performance and battery life, the important consideration is:
- MIUI has very aggressive battery management (which can actually give better battery life numbers, but at the cost of delaying notifications and killing background apps)
- Custom AOSP ROMs generally have less aggressive battery management but feel smoother and more responsive
- With proper tweaks (GMS Doze, Naptime, etc.), AOSP ROMs can match or exceed MIUI battery life

Let me give a concise answer.

No Redmi 4A ever shipped with stock Android — it came with MIUI. If you mean **pure AOSP/Google Android**, your options are:

- **crDroid 9.x (Android 13)** — still the best. It's AOSP-based, actively maintained (iusmac), with kernel-level battery tuning. Closest to stock Android with just useful extras.

- **Pixel Experience** (Android 11, unofficial, discontinued 2021) — was the closest to "Pixel stock Android" but dead, no security patches.

- **LineageOS** (Android 14 unofficial exists, but no official build for rolex) — very close to AOSP but was never officially maintained for this device.

- **GSI (Generic System Image)** — you can flash pure AOSP via Project Treble (e.g., phhusson's GSI). This gives you actual unmodified stock Android. Works, but you lose device-specific optimizations (camera, sensors, battery tuning) that crDroid's maintainer has baked into the kernel.

**Bottom line:** crDroid 9.x is effectively your best "stock Android" experience — it's closer to AOSP than MIUI, actively patched, and optimized for this hardware. If you truly want unmodified AOSP, use a GSI, but expect worse battery life without the per-device kernel tuning.

---

## User

the most stripped down android for thid device

---

## Assistant (Plan · Big Pickle · 8.8s)

_Thinking:_

The user wants the most stripped-down/minimal Android for the Redmi 4A (rolex). They want maximum performance and battery life by eliminating everything unnecessary. Let me think about what options exist:

1. **Vanilla (no GApps) ROMs** - Custom ROMs without Google apps pre-installed
2. **LineageOS without GApps** - Minimal, close to AOSP
3. **AOSP GSI** - Pure AOSP via Project Treble
4. **Debloated MIUI** - Stripping down the stock ROM
5. **Special minimal ROMs** - There might be some specifically lite/minimal ROMs

Actually, I should search for what's available specifically for Redmi 4A that's minimal/lightweight.

**Tool: websearch**

**Input:**
```json
{
  "query": "lightweight minimal custom ROM Redmi 4A rolex no gapps debloated best battery 2024 2025",
  "numResults": 8
}
```

**Output:**
```
Title: Pixel Experience 11 for Redmi 4A – Android 11
URL: https://cyanogenmods.org/pixel-experience-11-redmi-4a/
Published: 2024-09-10T02:14:23.000Z
Author: Siba
Highlights:
Pixel Experience 11 for Redmi 4A – Android 11
[...]
Android 11 is released recently and the official update of the same for Redmi 4A is far away. But, Pixel Experience 11 for Redmi 4A which is based on Android 11, is now available to download.
[...]
This is a step-by-step guide that explains how to install Pixel Experience 11 on Redmi 4A. This build is brought to you by developer Foxtrot47.
[...]
Pixel Experience is based on AOSP that includes GApps and includes many features from the Google Pixel devices.
[...]
Like other custom ROMs the Pixel Experience focuses more on bringing Pixel features and the Pixel Experience Plus variant brings few extra features on top.
[...]
The Pixel Experience 11 is based on the recently released Android 11 update.
[...]
To be able to install any Android 11 ROM build on the phone, it must have an unlocked bootloader and a compatible custom recovery installed. So, to make it easier for you, we have included appropriate guides on how to unlock bootloader and install recovery in the below sections.
[...]
Pixel Experience 11 does not require GApps to be installed separately.
[...]
Installing Pixel Experience 11 requires an unlocked bootloader and a custom recovery installed on the phone. This is the reason the entire installation guide is divided into three parts as below:
[...]
- Unlocking bootloader on the phone
- Installing Custom Recovery on the phone
- Installing the Pixel Experience 11 ROM on the phone
[...]
[su_note note_color=”#FBF4DD”
[...]
_color=”#A38C68″ radius=”3″ class=”
[...]
=””]The bootloader must be unlocked on the phone before you can flash the Pixel Experience 11 custom ROM build![/su_note]
[...]
### Install custom recovery on
[...]
Custom recovery must be installed on Redmi 4A to install Pixel Experience 11.
[...]
Below is a list of guides that explains how to install custom recovery such as TWRP or OrangeFox recovery on Redmi 4A.
[...]
Download the Pixel Experience 11 ROM for Redmi 4A
[...]
it into the phone or
[...]
in the PC (
[...]
install using ADB
[...]
2. Enter into recovery mode and Wipe data, Cache, System and clean Dalvik cache. – Make sure you don’t wipe or format Internal memory here. Otherwise you will lose all your phone data![su_note note_color=”#D7E3F4″ text_color=”#728095″ radius=”3″ class=”” id=””]- Here is a step-by-step guide on how to wipe data using TWRP recovery[/su_note][su_note note_color=”#F9D9D9″ text_color=”#AA4343″ radius=”3″ class=”” id=””]- This step will erase the current firmware from the phone. You can choose to keep a backup of the relevant boot and system partition so that you can rollback if the new build doesn’t work properly.[/su_note]
[...]
3. Install Pixel Experience 11 using TWRP recovery or any custom recovery of your choice(OR) Use ADB Sideload to install the Pixel Experience 11 ROM zip file. [su_note note_color=”#D7E3F4″ text_color=”#728095″ radius=”3″ class=”” id=””]You can use any one of the above mentioned method to install the zip file on the phone.[/su_note]
[...]
Well, after installing the Pixel Experience 11 and GApps zip file you are done with the installation process. But, there are few add-on packages that you can install to unleash the real capabilities of your phone!
[...]
Currently, Magisk is the only thing that is actively developed and supports rooting of Android 11 ROM. You can either follow this Android 11 Rooting guide or the Magisk rooting guide to enable root.
[...]
## Other Custom ROMs for Redmi 4A
[...]
It is possible that the Pixel Experience 11 for Redmi 4A might not be stable as this is an initial build. In that case below are some of the custom ROMs that we have for the device, if you consider to switch.
[...]
That’s all on installing Pixel Experience 11 on Redmi 4A! If you face any issue, then you can comment below. Also, visit the Redmi 4A (rolex) page to get other Android 11 ROMs or other device specific topics.

---

Title: [ROM][10.0]REDMI 4A] Pixel Experience Plus Unofficial [AOSP][rolex] | XDA Forums
URL: https://xdaforums.com/t/rom-10-0-redmi-4a-pixel-experience-plus-unofficial-aosp-rolex.4079399/
Published: 2020-04-08T14:52:11.000Z
Author: N/A
Highlights:
PixelExperience Plus for Redmi 4a [rolex] What is this? Pixel Experience Plus is an AOSP based ROM with minimal customisation, with Google apps included and all Pixel goodies (launcher, wallpapers, icons, fonts, bootanimation) Our mission is to offer the maximum possible stability and security, along with essential and useful features for the proper functioning of the device Based on Android 10.0 Whats working? Wifi Face Unlock RIL Mobile data GPS Camera Flashlight Camcorder Bluetooth FMRadio Lights Sound / vibration Known issues Nothing yet You tell me DON'T FLASH GAPPS, THEY'RE ALREADY INCLUDED Download Donate Liked my work? Give me a beer Stay tuned Our Telegram channel Our blog​
[...]
- Android OS version: 10.0.0_r33
- Security patch level: April 2020
- Build author/Device Maintainer: Manohar Singh
- Device kernel code: https://github.com/Thagoo/Triton_kernel_xiaomi_msm8917
- Source code: https://github.com/PixelExperience
- ROM Developer: jhenrique09

​
[...]
As far as i know, this is a new feature. And bit by bit, it will be implemented into other roms soon. Also, it works very smooth. Takes 1-2 seconds.
[...]
@adi153 thanks for this build! But why gapps is so old? E.g. Chrome is 74 from mostly year ago. Please mention in first post that encryption of device causes boot loop. Also, I can't find an option to enable battery indication in %
[...]
[RECOVERY] [OFFICIAL] TWRP 3.2.1-0 for Xiaomi Redmi 4A [rolex] [20171210]
[...]
[ROM][8.1.0_r52][OFFICIAL] AospExtended ROM V5.8 for Redmi 4A/5A [ROLEX/RIVA]
[...]
- ECr34T1v3
[...]
- May 1, 2018
-
[...]
4 35 36
[...]
[ROM][9.0][rolex] Pixel Experience [AOSP][2019/12/12][DISCONTINUED]
[...]
10.0
[...]
rolex] Lineage OS 17.1
[...]
PixelExperience Plus for Redmi 4a [rolex] What is this? Pixel Experience Plus is an AOSP based ROM with minimal customisation, with Google apps included and all Pixel goodies (launcher, wallpapers, icons, fonts, bootanimation) Our mission is to offer the maximum possible stability and security, along with essential and useful features for the proper functioning of the device Based on Android 10.0 Whats working? Wifi Face Unlock RIL Mobile data GPS Camera Flashlight Camcorder Bluetooth FMRadio Lights Sound / vibration Known issues Nothing yet You tell me DON'T FLASH GAPPS, THEY'RE ALREADY INCLUDED Download Donate Liked my work? Give me a beer Stay tuned Our Telegram channel Our blog​
[...]
- Android OS version: 10.0.0_r33
- Security patch level: April 2020
- Build author/Device Maintainer: Manohar Singh
- Device kernel code: https://github.com/Thagoo/Triton_kernel_xiaomi_msm8917
- Source code: https://github.com/PixelExperience
- ROM Developer: jhenrique09

​
[...]
As far as i know, this is a new feature. And bit by bit, it will be implemented into other roms soon. Also, it works very smooth. Takes 1-2 seconds.

---

Title: [RR ROM] Resurrection Remix 8.5.8 Android 10 for Redmi 4A
URL: https://cyanogenmods.org/rr-rom-android-10-redmi-4a/
Published: 2024-10-03T17:46:30.000Z
Author: Siba
Highlights:
[RR ROM] Resurrection Remix 8.5.8 Android 10 for Redmi 4A
[...]
Android 10 based Resurrection Remix Ten ROM for Redmi 4A is now available to download. This build of RR Ten for Redmi 4A is brought to you by the official Resurrection Remix Team.
[...]
Following are some of the other custom ROMs based on Android 10 for Redmi 4A: – LineageOS 17.1 for supported devices – Bliss ROM Android 10 for supported devices – Android 10 download for all available devices
[...]
[su_note note_color=”#F9D9D9″ text_color=”#AA4343″ radius=”3″ class=”” id=””]This is a custom ROM for Redmi 4A which may have many bugs. This firmware has to be installed using a custom recovery such as TWRP, which requires an unlocked bootloader on the phone. Make sure you BACKUP all the data and all the partitions of your phone before installing this RR Ten ROM.
[...]
### About RR Ten v8.5.8 based on Android 10:
[...]
Resurrection Remix OS is an open source custom ROM based on LineageOS which provides gesture control, customization, better battery life, regular security merges, OTA updates etc. This project founded and run by Altan KRK (westcrip) and many others in the team.
[...]
The Resurrection Remix (RR) Ten ROM version v8.x is based on the recently released LineageOS 17.1 and Android 10, which is the latest Android to date.
[...]
WHAT’S WORKING: – Almost everything
[...]
How to Install Resurrection Remix (RR) Ten on Redmi 4A?
[...]
[su_note note_color=”#D8F1C6″
[...]
_color=”#769958″ radius=”3″ class=””
[...]
=””] Following are the two sub-sections of this Redmi 4A Android 10 update guide:
[...]
1. Android 10 GApps
2. First-time installation of RR Ten ROM
3. Upgrading RR Ten build from a previous build
[...]
1. Download and Copy the RR ROM 8.x Android 10 zip file for Redmi 4A and the Android 10 Gapps zip file to your phone.
[...]
2. Boot into the TWRP Recovery (with SAR support) to install RR ROM Android 10 on Redmi 4A. [su_note note_color=”#D7E3F4″ text_color=”#728095″ radius=”3″ class=”” id=””]- Make sure to have a Custom recovery like a TWRP recovery or any other custom recovery. – If not then download the TWRP recovery from Downloads link and follow the how to install TWRP recovery guide (it’s a generic guide which will work for TWRP as well as any other recovery)[/su_note]
[...]
4. Install the RR Ten zip file that you have copied into the phone.
[...]
5. Then flash the Android 10 Gapps zip file. [su_note note_color=”#D7E3F4″ text_color=”#728095″ radius=”3″ class=”” id=””]- Here is a post explaining how to install GApps using TWRP recovery.[/su_note]
[...]
6. Reboot and Enjoy Android 10 with Resurrection Remix Ten ROM, on your Redmi 4A.
[...]
### Upgrade RR Ten ROM Android 10 on Redmi 4A:
[...]
1. Copy the latest RR ROM Android 10 zip file for your device
2. Boot into TWRP recovery
3. Wipe the system partition from the custom recovery menu.
4. Install the latest RR ROM zip file.
5. Reboot and see you have the GApps and ROOT access or NOT (if you installed previously). [su_note note_color=”#D8F1C6″ text_color=”#769958″ radius=”3″ class=”” id=””]- Gapps is built in such a way that it will sustain across ROM updates.[/su_note]
[...]
6. If you don’t have GApps after upgrading the Android 10 on the phone, then flash the GApps again. [su_note note_color=”#D7E3F4″ text_color=”#728095″ radius=”3″ class=”” id=””]- Here is a post explaining how to flash GApps using TWRP recovery.[/su_note]
[...]
7. If you don’t have ROOT after upgrading the Resurrection Remix ROM Android 10 on your phone, then flash the Magisk Installer zip file.
[...]
8. Once everything is done, reboot and Enjoy the Android 10 RR ROM on Redmi 4A.
[...]
GCam 7.0 and later versions are compatible with RR Ten ROM v8 or any Android 10 ROM in general. You can always look into the big list of Google Camera APK download page to get a compatible GCam for your phone.

---

Title: AospExtended-v8.3-rolex-UNOFFICIAL-20210629-1128.zip | ROM by Raj sharma for Redmi 4A
URL: https://androidfilehost.com/?fid=14943124697586357767
Published: N/A
Author: N/A
Highlights:
AospExtended-v8.3-rolex-UNOFFICIAL-20210629-1128.zip | ROM by Raj sharma for Redmi 4A
[...]
### AospExtended-v8.3-rolex-UNOFFICIAL-20210629-1128.zip
[...]
for the Xiaomi Redmi 4A(Rolex), by Raj sharma
[...]
388Downloads
[...]
649.2MBSize
[...]
#### Description:
[...]
### Raj sharma

---

Title: [ROM][10]Evolution X 4.5 for Redmi 4A[rolex] | XDA Forums
URL: https://xdaforums.com/t/rom-10-evolution-x-4-5-for-redmi-4a-rolex.4130829/
Published: 2020-07-09T04:53:32.000Z
Author: N/A
Highlights:
# [ROM][10]Evolution X 4.5 for Redmi 4A[rolex]
[...]
Evolution X is a flashable custom ROM to bring a true Pixel feel to your Android Device at first glance, with many additional configurations at your disposal. We aim to provide frequent builds with monthly security patches from the latest aosp sources!​
[...]
- RGB Accent Picker - Dark Theme Styles (color Bucket) -
[...]
17 System Fonts - 6 System Icon Shapes - 4 Statusbar Icon Styles - 2019 Pixel Live Wallpapers - Custom QS Header Images - New Tint Style Toggle - QS Opacity & Color Configs - QS Backround Image Blur Statusbar - Clock Options - Battery Bar - Carrier Label Settings - Network Traffic Activity - Rounded Corners Config - System UI Tuner - 7 Battery Icon Style - Battery Percent Show/Hide Config - Old Mobile Style Network
[...]
- 4G/LTE
[...]
& Toggle Notifications
[...]
Heads Up - R
[...]
Notification Toggle - Notification light Config -
[...]
- Force Close Notifications - Force Expanded Notification - Kill App Button - Notification Vibration Toggle - Blink Flashlight On
[...]
Settings Icon Toggle -
[...]
- User Switcher Icon Toggle - QS Edit Icon Toggle Power Menu - Restart - Advanced Restart - Screenshot - Flashlight - Airplane - Settings - Lock Down - Users - Logout - Visibility On Lockscreen Configs Gestures - AOSP Gestures - Swipe To Screenshot - Status Bar Brightness Control - Screen Off Power Button Torch - Double Tap To Sleep Status Bar - Double Tap to Sleep Lockscreen - Toggle To Hide Navbar Pill - Back Gesture Height Config - Back Gesture Vibration Toggle - Screen Off Gestures Lockscreen - Pocket Detection - Fingerprint Authentication Vibration Toggle - Charging Info - Lock
[...]
- Status bar
[...]
Toggle - Lock
[...]
- Custom Clock & Date Fonts/
[...]
Disable/Enable
[...]
Flip/Rotate
[...]
Duration & Interpolator configs
[...]
System Animation Configs Miscellaneous
[...]
Gaming Mode - Launch Music App On Headset Connection - Wake On Charge - Charging Animation - Screenshot Type (Full/Drag) - Dashboard Condition/Suggestion Toggle - Doze Brightness Configs - Default USB Config - Disable Device Identifier Restrictions - Accidental Wake Up Prevention - Sensor Block Per Package - Signature Spoofing Support - Time In State Monitor - Doze Settings - Legacy App Scalling - Alarm Blocker - Wakelock Blocker
[...]
You tell me DO NOT FLASH GAPPS, ALREADY INCLUDED
[...]
First Time Install / Clean Flash - Make sure you're running the latest TWRP - Boot into recovery - Flash BUILD.zip - Flash TWRP.zip - Wipe Cache - Format data - Reboot to recovery (optional) - Flash Magisk.zip (optional) - Reboot to system & #KeepEvolving[/SIZE] Update / Dirty Flash - Boot into recovery - Flash BUILD.zip - Flash TWRP.zip - Reboot to recovery (optional) - Flash Magisk.zip (optional) - Wipe Cache - Reboot to system & #KeepEvolving Download Donate me!/ Official Chat/ Device Support​
[...]
- ROM Developer: Gaurav
- Kernel Source: [url]https://github.com/Nick89786/android_kernel_xiaomi_msm8917 [/url]
- ROM Source: [url]https://github.com/Evolution-X [/url]
- Build Author: Gaurav
- [*]Android version: 10 [*]Evolution version: 4.5 [*]Security patch level: July, 2020

​
[...]
Evolution X is a flashable custom ROM to bring a true Pixel feel to your Android Device at first glance, with many additional configurations at your disposal. We aim to provide frequent builds with monthly security patches from the latest aosp sources!​
[...]
the latest TWRP
[...]
] Update /
[...]
(optional) - Flash Magisk
[...]
(optional) - Wipe Cache - Reboot to system & #KeepEvolving Download
[...]
me!/ Official Chat/ Device Support​
[...]
- ROM Developer: Gaurav
- Kernel Source: [url]https://github.com/Nick89786/android_kernel_xiaomi_msm8917 [/url]
- ROM Source: [url]https://github.com/Evolution-X [/url]
- Build Author: Gaurav
- [*]Android version: 10 [*]Evolution version: 4.5 [*]Security patch level: July, 2020

​

---

Title: Xiaomi Redmi 4A (aka Rolex) | Jeff McNeill
URL: https://jeffmcneill.com/redmi4a/
Published: 2018-06-23T13:37:24.000Z
Author: by
Highlights:
The Xiaomi Redmi 4A (aka Rolex) is a cheap (~100 USD) and lightweight (131.5g) 5" phone. For price, weight, and size, there is not much competiton. The screen is a 720 x 1280 px 16x9 screen that is pretty decent. Its got a Snapdragon 425 and 2gb of RAM with 16 or 32 gb of storage, and supports dual sim or single sim + microsd card.
[...]
side, the camera is weak, it is slow to open, and of course stock
[...]
is slow and bloated, along with an annoying reminder to register your sim aka spyware on the prowl.
[...]
That said, there is nothing in a 5" screen that is as light and as cheap, and that means very strong value.
[...]
Custom ROMs for Redmi 4A
[...]
## Custom ROMs for Redmi 4A
[...]
Thankfully this is a popular device for custom roms. Rolex is not as widely supported as some devices. However, the AOSP Extended ROM, a twice monthly updated vanilla Google + customizations does support this device. It turns out that LinneageOS 15.1 supports Redmi 4A as well. Turns out Pixel Experience rom is also available for rolex.
[...]
Install Apps from the Play Store Without Gapps or Google Services.
[...]
I still prefer this phone over the Xiaomi Redmi 5A and Xiaomi Redmi 6A. The 6A is a bit heavier, with a longer screen, but the home row buttons have been moved onto the display, so no real gain in screen real estate. The 5A is not as nice a feel in the hand, but some versions have 4gb of ram and 32gb of storage, so that is better than the 2gb generally available across all of these models. Overall, a good balance of lightweight, decent screen, moderate performance, and lower-end camera. Hard to beat for around $100 USD.

---

Title: Nusantara Project Android 11 R untuk Redmi 4A (Rolex) - Andronine
URL: https://www.andronine.com/2020/12/nusantara-project-redmi-4a.html
Published: 2020-12-22T09:00:00.000Z
Author: https://www.blogger.com/profile/09528996332479265319
Highlights:
Apakah anda sedang mencari Custom ROM android 11 terbaik untuk Redmi 4A (Rolex)?Kalau begitu Andronine adalah tempat yang tepat. Pada artikel ini Andronine akan memberikan salah satu cusrom terbaik untuk Redmi 4A (Rolex) yang berbasis Android 11.Saya pastikan anda telah memiliki perangkat Xiaomi Redmi 4A, dan pastinya perangkat tersebut berjalan pada sistem operasi Android.Salah satu kelebihan android dibanding sistem operasi lainnya adalah open-source, yang artinya android memberikan kebebasan untuk komunitas atau developer dalam mengembangkan dan menciptakan ROM untuk perangkat tertentu.Sekedar informasi, Redmi 4A atau sering disebut Rolex dirilis pada Mei 2017 lalu dengan Android versi 6.0.1 (Marshmallow) pada sistem operasi bawaannya.Dalam artikel ini, Andronine akan memberikan salah satu Custom ROM dengan versi android terbaru yaitu Android 11 (R) yang telah tersedia dan dapat di instal pada perangkat Redmi 4A anda.
[...]
Nusantara Project adalah salah satu Custom ROM terbaik yang telah merilis android terbaru yaitu Android 11 R.
[...]
Pada artikel ini, anda dapat melakukan download dan instal Custom ROM Nusantara Project terbaru yang berbasis Android 11 untuk Xiaomi Redmi 4A anda.
[...]
Kalau anda sedang mencari custom ROM terbaik untuk Redmi 4A, maka ROM yang memiliki basis AOSP adalah pilihan yang tepat.
[...]
Karena ROM yang memiliki basis AOSP tidak memiliki bloatware, sehingga performanya menjadi lebih smooth dan ringan.
[...]
Android version : 11 (BETA5)ROM version: 2.5
[...]
Date build : Desember 20, 2020Maintainers : @dodyirawan85File size : 674 MB (Not include GApps)
[...]
Custom ROM, sebaiknya anda baca dulu hal
[...]
saja yang harus dipersiapkan sebelum melakukan instal custom ROM. Untuk cara flash cusrom di Redmi 4A, kalian harus melakukan clean flash. Clean flash adalah menginstal ROM dengan cara format partisi dalvik, cache, data, system, dan vendor, sehingga semua aplikasi anda akan hilang.Oleh karena itu lakukan backup aplikasi dengan Titanium Backup sebelum melakukan
[...]
Costum ROM.Sebelum mulai ke
[...]
custom rom yang pertama, biasakan selalu melakukan backup ROM terlebih dahulu.
[...]
- Lakukan
[...]
sebelum menginstal
[...]
Project
- Perangkat anda harus sudah terpasang TWRP (TW
[...]
Official, PB
[...]
, OrangeFox, dll)
[...]
Itulah Custom ROM Nusantara Project untuk perangkat Xiaomi Redmi 4A atau yang memiliki codename "Rolex".

---

Title: Redmi 4A – rolex
URL: https://cyanogenmods.org/forums/forum/xiaomi/redmi-4a-rolex/
Published: 2024-05-25T15:08:11.000Z
Author: N/A
Highlights:
Download LineageOS 16 for Redmi 4A
[...]
LineageOS 14.1 for Redmi 4A (rolex) Nougat 7.1 ROM
[...]
LineageOS 15.1 for Xiaomi Redmi 4A- rolex- Oreo 8.1 ROM Download
[...]
Download crDroid Android 10 ROM for Redmi 4a (Rolex)
[...]
Download Havoc OS 3 Android 10 ROM for Redmi 4a [Rolex]
[...]
Carbon ROM Android Pie for Redmi 4A – Android 9
[...]
Pixel Experience Android 9 Pie for Xiaomi Redmi 4A
[...]
How to Install AOSP Oreo for Redmi 4A – Android 8.1
[...]
How to Install Resurrection Remix OREO for Redmi 4A – Android 8.1
[...]
LineageOS 13 for Redmi 4A – Download and Installation Guide
```

**Tool: websearch**

**Input:**
```json
{
  "query": "AOSP GSI Redmi 4A rolex treble vanilla minimal performance",
  "numResults": 5
}
```

**Output:**
```
Title: Xiaomi Redmi 4A · TrebleDroid/treble_experimentations Wiki · GitHub
URL: https://github.com/TrebleDroid/treble_experimentations/wiki/Xiaomi-Redmi-4A
Published: N/A
Author: TrebleDroid
Highlights:
# Xiaomi Redmi 4A & Xiaomi Redmi 5A
[...]
Full Treble enabled by 33bca
[...]
REMEMBER : Redmi 4A and Redmi 5A are arm64 and System A-ONLY, however, if you're using custom ROM based on Android 10 or later, use A/B GSI since your partition is system-as-root, not all A/B GSI will boot, so choose carefully
[...]
We don't have Treble out of the box, it has been enabled by 33bca. We are using /cust partition which is around 537mb in our devices as our /vendor partition.

---

Title: AOSP 12.0 v400.a
URL: https://github.com/phhusson/treble_experimentations/releases/tag/v400.a
Published: 2021-10-29T19:03:47.000Z
Author: phhusson
Highlights:
- Repository: phhusson/treble_experimentations | Notes about tinkering with Android Project Treble | 4K stars | Smali
- Name: AOSP 12.0 v400.a
- Author: @phhusson
- Created: 2021-10-29T13:14:48Z
- Published: 2021-10-29T19:03:47Z
- Prerelease: true
- Reactions: 👍 20 😄 6 🎉 13 ❤️ 12 🚀 6 👀 7
[...]
This is a pre-release. This is not considered daily-drivable, though your mileage may vary.
[...]
Gapps variant will come later. As you'll notice, there is no A-only variant at the moment. It is still undecided whether A-only variants will later appear.
[...]
When you report issues in the bug tracker, don't forget to mention which GSI version you're using.
[...]
If you want unshared_blocks/read-write system, use vndklite variants. Non-vndklite devices are capable of running vndklite variants.
[...]
| File | Size | Downloads |
| --- | --- | --- |
| manifest.xml | 242 KB | 225 downloads |
| patches.zip | 107 KB | 378 downloads |
| system-squeak-arm32_binder64-ab-vanilla.img.xz | 457658 KB | 729 downloads |
| system-squeak-arm32_binder64-ab-vndklite-vanilla.img.xz | 494963 KB | 1244 downloads |
| system-squeak-arm64-ab-floss.img.xz | 877534 KB | 493 downloads |
| system-squeak-arm64-ab-vanilla.img.xz | 581018 KB | 1030 downloads |
| system-squeak-arm64-ab-vndklite-floss.img.xz | 937748 KB | 626 downloads |
| system-squeak-arm64-ab-vndklite-vanilla.img.xz | 652507 KB | 1020 downloads |

---

Title: Xiaomi Redmi 4A · erfanoabdi/P_semiGSI Wiki · GitHub
URL: https://github.com/erfanoabdi/P_semiGSI/wiki/Xiaomi-Redmi-4A
Published: N/A
Author: erfanoabdi
Highlights:
# Xiaomi Redmi 4
[...]
# Xioami Redmi 4A - rolex
[...]
# Booted using Crdroid Official treble .
[...]
## Hardware Support
[...]
2G - 4G+ working with no issues, in-call audio also working after flash the fix incall2.zip by erfan . Need create a APN for fix data connection .
[...]
- 3.5mm audio jack
[...]
## Working Tested Vendors
[...]
Crdroid ROM
[...]
## Additional Installation Notes
[...]
[If performace laggy.] flash this fix (https://androidfilehost.com/?fid=5862345805528049478) [If display UI glitches] set in Developer options: Profile GPU rendering - In adb shell dumpsys gfxinfo
[...]
## Known Bugs
[...]
Display UI gliches some sec. (fix up)

---

Title: [AOSP 9.0] [Experimental] Android 9.0 GSI | XDA Forums
URL: https://xdaforums.com/t/aosp-9-0-experimental-android-9-0-gsi.3826357/
Published: 2018-08-07T14:47:22.000Z
Author: N/A
Highlights:
WARNING: You'll most probably loose ALL your data, and might break your phone. Please use with extreme caution! The goal of this ROM is to provide full Treble-compatible hardware support, and nothing else. This means that hardware which DON'T have Treble API won't be supported, like Essential's external camera. No feature will be added. This will ease forward porting to new Android versions, which is the very goal of Project Treble My hope is that other ROM developers will use this ROM as a basis to construct more advanced ROM. For a list of treble supported devices, consult and fill https://github.com/phhusson/treble_experimentations/wiki How to flash: 1- Flash a treble rom (GSI only has 8.1 vndk. 8.0 probably won't work.) 2- Extract p-gsi-built.zip and flash system.img 3- Flash p-boot-other-fixes.zip, wifi fix, POST-sGSI_boot-patch.zip (thanks to erfanoabdi bootpatcher from p semi-gsi) 4- Reboot Bugs: - Camera - Flashlight -VoLTE (Tested on Redmi Note 4 and Redmi 4A, bugs can change according to device.) Download: 9.0.0_r3 (2018-08-07): system.img for A ARM64 devices vanilla Telegram Account: MacTavishAO Thanks to: @erfanoabdi @phhusson and thanks to ChristianEM for wifi fix. "Bayram Kılıç and Burak Mete Erdoğan the guys who says pixel stock and aosp is totally same. These 2 guys said to me 'Idiot released same rom. Unnecessary'. LOL. From their mouths; 'Pixel stock is started being AOSP. Pixel Team will release AOSP stock rom for pixel devices. It is pretty smooth. And said Pixel Team would give P immediately if AOSP wasn't problematic they fixed it.' Pixel's UI isn't AOSP UI lol "
[...]
WARNING: You'll most probably loose ALL your data, and might break your phone. Please use with extreme caution! The goal of this ROM is to provide full Treble-compatible hardware support, and nothing else. This means that hardware which DON'T have Treble API won't be supported, like Essential's external camera. No feature will be added. This will ease forward porting to new Android versions, which is the very goal of Project Treble My hope is that other ROM developers will use this ROM as a basis to construct more advanced ROM. For a list of treble supported devices, consult and fill https://github.com/phhusson/treble_experimentations/wiki How to flash: 1- Flash a treble rom (GSI only has 8.1 vndk. 8.0 probably won't work.) 2- Extract p-gsi-built.zip and flash system.img 3- Flash p-boot-other-fixes.zip, wifi fix, POST-sGSI_boot-patch.zip (thanks to erfanoabdi bootpatcher from p semi-gsi) 4- Reboot Bugs: - Camera - Flashlight -VoLTE (Tested on Redmi Note 4 and Redmi 4A, bugs can change according to device.) Download: 9.0.0_r3 (2018-08-07): system.img for A ARM64 devices vanilla Telegram Account: MacTavishAO Thanks to: @erfanoabdi @phhusson and thanks to ChristianEM for wifi fix. "Bayram Kılıç and Burak Mete Erdoğan the guys who says pixel stock and aosp is totally same. These 2 guys said to me 'Idiot released same rom. Unnecessary'. LOL. From their mouths; 'Pixel stock is started being AOSP. Pixel Team will release AOSP stock rom for pixel devices. It is pretty smooth. And said Pixel Team would give P immediately if AOSP wasn't problematic they fixed it.' Pixel's UI isn't AOSP UI lol "
[...]
If anyone wants
[...]
test, I just built
[...]
aosp treble
[...]
devices w/ 8.1 vendor. So, people with a whyred, modified mido/tissot, or similar a/
[...]
device that can run P treble roms such as this one should in theory be able to run this. Theory. System image is provided. Modifications to your bootimg and vendor should be the same as on this rom. Line
[...]
contains a whole bunch of nothing,
[...]
default apps we know and love. For
[...]
because Trebu
[...]
API and Android sometimes
[...]
having no launcher. Or the SEpolicies are completely broken. Not that it should matter with a permissive bootimg. Anyhow, here it is
[...]
arm64
[...]
. Samsung galaxy s9+ Exynos has official
[...]
roms but it only has
[...]
vendor file.

---

Title: [GSI][ROM][10.0][AOSP+GAPPS][04/08/20] | XDA Forums
URL: https://xdaforums.com/t/gsi-rom-10-0-aosp-gapps-04-08-20.3997819/
Published: 2019-11-05T13:22:02.000Z
Author: N/A
Highlights:
What is this? An AOSP based ROM, with gapps included and gesture support (pocket, hand wave, pickup). Based on Android 10.0 Bugs: voLTE - currently broken, working with Phh to get it up and running, absolutely no ETA, if you need voLTE, use any of the other roms Steps: 1. Use latest CosmicDan treble TWRP 2. Re-partition to treble layout if you haven't done so yet 3. Flash vendor.img, system.img and a treble supported kernel (you can use mine or any of the other treble kernels on tissot xda) 4. Wipe data if coming from any other rom(!) 5. Flash Rom (No need for gapps, do not flash them, they are included!) 6. Reboot and wait for setup wizard to come up (may take 2-3 minutes) 7. Reboot to twrp and flash magisk (optional) 8. Reboot Downloads: Link Thanks to @Ranjan for IMS.apk @phhusson for his work on GSI (donate to this man, he works on dozens of devices) @flex1911 for his help bringing 9.0 kernel source for tissot Oreo team (you all know who you are,@cosmicdan for twrp, @ghpranav for treble vendor source) Enjoy! P.S. I am not going to add any custom features from other roms so please don't comment about that, feel free to flash any other GSI with this vendor/kernel if you want other features. Source: https://github.com/aosp-tissot kernel source: https://github.com/aosp-tissot/android_kernel_xiaomi_msm8953-1 Credit to @flex1911 for the original work on the kernel XDA:DevDB Information [GSI][ROM][10.0][AOSP+GAPPS][04/08/20], ROM for the Xiaomi Mi A1 Contributors sooti, phhusson, flex1911, Ranjan Source Code: https://github.com/aosp-tissot ROM OS Version: Android 10 ROM Kernel: Linux 4.x ROM Firmware Required: Treble Based On: AOSP Version Information Status: Stable Stable Release Date: 2020-05-07 Created 2019-11-05 Last Updated 2020-08-04​
[...]
What is this? An AOSP based ROM, with gapps included and gesture support (pocket, hand wave, pickup). Based on Android 10.0 Bugs: voLTE - currently broken, working with Phh to get it up and running, absolutely no ETA, if you need voLTE, use any of the other roms Steps: 1. Use latest CosmicDan treble TWRP 2. Re-partition to treble layout if you haven't done so yet 3. Flash vendor.img, system.img and a treble supported kernel (you can use mine or any of the other treble kernels on tissot xda) 4. Wipe data if coming from any other rom(!) 5. Flash Rom (No need for gapps, do not flash them, they are included!) 6. Reboot and wait for setup wizard to come up (may take 2-3 minutes) 7. Reboot to twrp and flash magisk (optional) 8. Reboot Downloads: Link Thanks to @Ranjan for IMS.apk @phhusson for his work on GSI (donate to this man, he works on dozens of devices) @flex1911 for his help bringing 9.0 kernel source for tissot Oreo team (you all know who you are,@cosmicdan for twrp, @ghpranav for treble vendor source) Enjoy! P.S. I am not going to add any custom features from other roms so please don't comment about that, feel free to flash any other GSI with this vendor/kernel if you want other features. Source: https://github.com/aosp-tissot kernel source: https://github.com/aosp-tissot/android_kernel_xiaomi_msm8953-1 Credit to @flex1911 for
[...]
original work on the kernel XDA:DevDB Information [GSI][ROM][10.0][AOSP+GAPPS][04
[...]
20], ROM for the
[...]
phhusson, flex1911, Ranjan Source Code: https://github.com/aosp-tissot ROM OS Version: Android 10 ROM Kernel: Linux 4.x ROM Firmware Required: Treble Based On: AOSP Version Information Status: Stable Stable Release Date:
[...]
2020-
[...]
5-07 Created 2
```

---

## Assistant (Plan · Big Pickle · 20.6s)

_Thinking:_

The user is asking for the most stripped-down Android for the Redmi 4A. This is a plan mode question - I need to research and present options, but NOT make any edits or changes.

Let me think about what "most stripped down" means:

1. **No GApps** - No Google Play Services, no Google apps. This is the single biggest battery and performance improvement.
2. **Minimal ROM** - A ROM with few to no extra features, close to pure AOSP.
3. **Lightweight Android version** - Older Android versions (like Android 8/9/10) are lighter than newer ones (13/14/15/16).
4. **Debloated** - Minimal pre-installed apps.

Options for the most stripped-down Android on Redmi 4A:

1. **crDroid 9.x (Android 13) vanilla** - Flash the "vanilla" (no GApps) variant. This is actively maintained and well-optimized, but Android 13 is heavier than older versions.

2. **LineageOS 16 (Android 9) without GApps** - Android 9 is very lightweight for this hardware. LineageOS is close to AOSP with minimal additions. But this is outdated with no security patches.

3. **AOSP Extended (AEX) Android 9 or 10 without GApps** - Very close to stock AOSP. Android 10 AEX v8.3 was last updated in 2021.

4. **Pure AOSP GSI** - Using Project Treble, flash phhusson's AOSP GSI (vanilla variant). This is the absolute closest to unmodified stock Android. You'd flash it over a treble-compatible vendor (like crDroid's). However, GSIs often have hardware compatibility issues (camera, sensors, etc.) since they lack device-specific tuning.

5. **crDroid 10.x (Android 14) or crDroid 11.x (Android 15) vanilla** - These still have the stock crDroid kernel with battery optimizations, but Android 14/15 are heavier.

For "most stripped down" considering both minimal OS weight AND battery/performance:

The **crDroid vanilla (no GApps)** builds are probably the best balance. They use the well-tuned iusmac kernel with battery optimizations, and without GApps the device flies and has excellent battery life. But crDroid does add some features on top of AOSP.

If the user truly wants the MOST stripped down (bare minimum), a **pure AOSP GSI** (phhusson's AOSP vanilla) would be the leanest, but may have bugs.

Actually, let me reconsider. The user said "most stripped down." The absolute most stripped down would be:

1. **AOSP GSI vanilla** - pure AOSP, no Google services, no extra features. But potentially buggy on this device.
2. **LineageOS 16 (Android 9) vanilla** - lightweight, close to AOSP, but old and unpatched.
3. **crDroid 9.x (Android 13) vanilla** - modern, well-maintained, kernel-optimized, but Android 13 is heavier than 9.

I think the best answer is a plan that involves:
- Using **crDroid** as the base (for the excellent kernel tuning by iusmac)
- Flashing the **vanilla (no GApps)** variant
- Using **microG** or no Google services at all
- Optionally using a lightweight launcher (like Lawnchair Lite or even Trebuchet)

Or alternatively, for truly maximum stripped-down:
- Flash a **crDroid vendor** (for hardware support) 
- Flash a **phhusson AOSP GSI vanilla** on top
- This gives you pure AOSP with proper device support

Let me present this as a plan since we're in plan mode.

For the most stripped-down Android on Redmi 4A, here's the plan ranked by how barebones it gets:

## Option 1: Pure AOSP GSI (Maximum stripped down)

Flash **phhusson's AOSP GSI vanilla** (no GApps) over a crDroid vendor. This is unmodified AOSP — zero bloat, zero extra features, no Google services. But expect bugs (camera, sensors, VoLTE may need fixes).

**How:** Flash crDroid first (to get the treble vendor + iusmac kernel), then flash phhusson AOSP GSI vanilla on top.

## Option 2: crDroid vanilla (Best balance)

**crDroid 9.x (Android 13) vanilla** — the maintainer's kernel tuning is the best battery/performance work done for this device. By choosing the **vanilla** variant (no GApps), you keep all the kernel optimizations while stripping Google services. This is the most practical daily-drivable stripped-down setup.

## Option 3: LineageOS 16 (Android 9) vanilla

If you want the *lightest Android version* (9 is significantly lighter than 13), LineageOS 16 without GApps. But it's ancient — no security patches since 2020.

---

**Key rule regardless of ROM:** Skip GApps entirely. Google Play Services is the #1 battery and RAM hog on 2GB devices. Use F-Droid + Aurora Store instead.

**My recommendation:** **crDroid 9.x Android 13 vanilla** + **Triton kernel** or stock iusmac kernel. You get the kernel-level power management, zero Google services, and a modern Android base that still runs well on SD425/2GB.

Want me to search for the exact download links and install steps for this combo?

---

## User

based on pie

---

## Assistant (Plan · Big Pickle · 6.4s)

_Thinking:_

The user wants a stripped-down Android based on Pie (Android 9) for the Redmi 4A. Let me search for the best Android 9 Pie options for this device that are minimal/lightweight.

**Tool: websearch**

**Input:**
```json
{
  "query": "AOSP Extended 6.7 Pie Redmi 4A rolex vanilla no gapps lightweight 2019 final",
  "numResults": 5
}
```

**Output:**
```
Title: [ROM][9.0.0_r46][OFFICIAL] AospExtended ROM V6.7 for Redmi 4A [ROLEX] | XDA Forums
URL: https://xdaforums.com/t/rom-9-0-0_r46-official-aospextended-rom-v6-7-for-redmi-4a-rolex.3867054/
Published: 2018-11-14T13:54:25.000Z
Author: N/A
Highlights:
ROM][9
[...]
0_r
[...]
][OFFICIAL] AospExtended ROM V
[...]
XDA Forums
[...]
AOSP Extended is an AOSP based ROM which provides stock UI/UX with various customizations
[...]
along with the Substratum theme engine. The project has been made by cherry-picking various commits from various other projects. Being based on AOSP it provides a smooth and lag-free experience out of the box. We will constantly try to add more features and make it even better in future updates
[...]
A ROM by a user, for a user. #StayAOSP #
[...]
Device #BeExtended
[...]
XDA:DevDB Information AospExtended Pie Official (rolex), ROM for the Xiaomi Redmi 4a Contributors ECr34T1v3, muralivijay, ataberkozen Source Code: https://github.com/ECr34T1v3 ROM OS Version: 9.x Pie ROM Kernel: Linux 3.x ROM Firmware Required: MIUI 9.2.6.0 Global Based On: AOSP Version Information Status: Stable Current Stable Version: 1.5 Stable Release Date: 2018-12-17 Current Beta Version: 1.1 Beta Release Date: 2018-11-11 Created 2018-11-14 Last Updated 2019-09-02
[...]
Build 2019/08/23: -Merged: New version of AospExtended (v6.7) Changelog in https://blog.aospextended.com/AospExtended-v6.7-Changelog-Merged: August Security Patch (9.0.0_r46) It has been 2 years officially maintaining AEX, i am following new paths for my life. I will no longer compile officially, but I will always be available. Thanks for all, guys <3 Unofficial ROMs and projects: https://ecr34t1v3.github.io Build 2019/07/11: -Merged: July Security Patch (9.0.0_r44) -Merged: SELinux Enforcing -Reworked: Device Tree No-Commonized (Thanks to nick) -Reworked: Doze settings (Ambient display) -Readded: Dirac Settings (Increased Sound) -Fixed: Quickswitch support -Enabled: Incall music -Enabled: AGPS Recommended: Clean Flash (because is new device tree)
[...]
Q: Which TWRP do I use? A: Use latest TWRP for ROLEX from HERE Q: Which GApps do I use? A: Flash OpenGApps Pico (recommended version). Link HERE Q: Is there a bug in ROM?? A: No. It is stable. Maybe there is a problem (if you have it, let me know which one I will correct), but it is stable for daily use. Q: Do I have to wipe data if coming from another ROM? A: Yes, I will not be providing help/support to users that haven't wiped data when coming from another ROM. Q: How often will I be getting updates? A: The plan is for weeklies, if unavoidable circumstances come up, please don't spam the thread. I will release a build as soon as one is ready. Q: Does VoLTE/VoWiFi work? A: Yes, works. Q: Is the ROM official? A: Yes, Official, and updates OTA available. Q: I use Telegram, where can I find help on that platform? A: There is a common AEX Group Chat for all devices, the link is HERE Q: Does SafetyNet pass and is the SELinux Enforcing? A: Yes, SafetyNet does pass and SELinux is Enforcing.
[...]
Build 2019/08/23: -Merged: New version of AospExtended (v6.7) Changelog in https://blog.aospextended.com/AospExtended-v6.7-Changelog-Merged: August Security Patch (9.0.0_r46) It has been 2 years officially maintaining AEX, i am following new paths for my life. I will no longer compile officially, but I will always be available. Thanks for all, guys <3 Unofficial ROMs and projects: https://ecr34t1v3.github.io Build 2019/07/11: -Merged: July Security Patch (9.0.0_r44) -Merged: SELinux Enforcing -Reworked: Device Tree No-Commonized (Thanks to nick) -Reworked: Doze settings (Ambient display) -Readded: Dirac Settings (Increased Sound) -Fixed: Quickswitch support -Enabled: Incall music -Enabled: AGPS Recommended: Clean Flash (because is new device tree)
[...]
Which TWRP
[...]
Which GApps do I use? A: Flash OpenGApps Pico (recommended version). Link HERE Q
[...]
a bug in ROM?? A: No. It is stable. Maybe there is a problem (if you have it, let me know which one I will correct), but it is stable for daily use
[...]
another ROM? A
[...]
Yes, I
[...]
providing help/support to users that haven'
[...]
, please don'
[...]
on that platform? A
[...]
There is a common
[...]
Net pass and

---

Title: AospExtended ROM - Browse /rolex/pie at SourceForge.net
URL: https://sourceforge.net/projects/aospextended-rom/files/rolex/pie/
Published: N/A
Author: N/A
Highlights:
AospExtended ROM - Browse /rolex/pie at SourceForge.net
* * Join/Login
* Business Software
* Open Source Software
* For Vendors
* Blog
* About
* More
* * Articles
* Create
* SourceForge Podcast
* Site Documentation
* Subscribe to our Newsletter
* Support Request
SourceForge logo
SourceForge logo
AospExtended ROM
# AospExtended ROM Files
## An android custom ROM based on AOSP,which provides a stock experience
Status:Beta
Brought to you by:allstargaurav,amolamrit,ishubhamsingh
* Summary
* Files
* Reviews
* Support
* Wiki
Download Latest VersionAospExtended-v9.0-avicii-UNOFFICIAL-20220320-0821.zip (1.8 GB)
Email in envelope#### Get an email when there's a new version of AospExtended ROM
Next

Home/rolex/pie
|Name|Modified|Size|InfoDownloads / Week|
Parent folder|
AospExtended-v6.7-rolex-20190823-0458-OFFICIAL.zip|2019-08-23|566.9 MB|
99 weekly downloads
|
AospExtended-v6.6-rolex-20190711-0115-OFFICIAL.zip|2019-07-11|574.3 MB|
0
|
AospExtended-v6.6-rolex-20190611-1507-OFFICIAL.zip|2019-06-12|568.9 MB|
0
|
AospExtended-v6.4-rolex-20190324-1435-OFFICIAL.zip|2019-03-24|628.1 MB|
0
|
AospExtended-v6.3-rolex-20190224-2150-OFFICIAL.zip|2019-02-24|625.0 MB|
0
|
AospExtended-v6.3-rolex-20190215-2236-OFFICIAL.zip|2019-02-15|625.1 MB|
0
|
AospExtended-v6.2-rolex-20190125-1522-OFFICIAL.zip|2019-01-25|634.6 MB|
0
|
AospExtended-v6.1-rolex-20181219-1608-OFFICIAL.zip|2018-12-19|633.2 MB|
0
|
AospExtended-v6.1-rolex-20181218-1640-OFFICIAL.zip|2018-12-18|633.2 MB|
0
|
AospExtended-v6.0-rolex-20181121-1459-OFFICIAL.zip|2018-11-21|591.7 MB|
0
|
AospExtended-v6.0-rolex-20181116-1401-OFFICIAL.zip|2018-11-16|591.9 MB|
0
|
AospExtended-v6.0-rolex-20181115-1508-OFFICIAL.zip|2018-11-15|591.4 MB|
0
|
AospExtended-v6.0-rolex-20181113-2127-OFFICIAL.zip|2018-11-14|591.7 MB|
0
|
Totals:13 Items||7.9 GB|9|
Other Useful Business Software
Comprehensive Cybersecurity to Safeguard Your Organization | SOCRadar Icon
Comprehensive Cybersecurity to Safeguard Your Organization | SOCRadar
See what hackers already know about your organization –and stop them from getting in.
Protect your organization from cyber threats with SOCRadar’s cutting-edge threat intelligence. Gain 360° visibility into your digital assets, monitor the dark web, and stay ahead of hackers with real-time insights. Start for free and transform your cybersecurity today.
Free Trial
Our Free Plans just got better! | Auth0 Icon
Our Free Plans just got better! | Auth0
With up to 25k MAUs and unlimited Okta connections, our Free Plan lets you focus on what you do best—building great apps.
You asked, we delivered! Auth0 is excited to expand our Free and Paid plans to include more options so you can focus on building, deploying, and scaling applications without having to worry about your security. Auth0 now, thank yourself later.
Try free now
Recommended Projects
* 
Bazel

Bazel
Fast, scalable, multi-language and extensible build system
* 
DeSmuME: Nintendo DS emulator

DeSmuME: Nintendo DS emulator
DeSmuME is a Nintendo DS emulator
* 
KeePass

KeePass
A lightweight and easy-to-use password manager
* 
Apache OpenOffice

Apache OpenOffice
The free and Open Source productivity suite
* 
Clonezilla

Clonezilla
A partition and disk imaging/cloning program
×
Want the latest updates on software, tech news, and AI?

Get latest updates about software, tech news, and AI from SourceForge directly in your inbox once a month.
Submit
Thanks for helping keep SourceForge clean.
X
You seem to have CSS turned off.
Please don't fill out this field.
You seem to have CSS turned off.
Please don't fill out this field.
Briefly describe the problem (required):
Upload screenshot of ad (required):
Select a file, or drag & drop file here.
✔✘Screenshot instructions:Mac
Click URL instructions:
Right-click on the ad, choose "Copy Link", then paste here &rarr;
(This may not be possible with some types of ads)
More information about our ad policies
Ad destination/click URL:

---

Title: [ROM][9.0][rolex] Pixel Experience [AOSP][2019/12/12][DISCONTINUED] | XDA Forums
URL: https://xdaforums.com/t/rom-9-0-rolex-pixel-experience-aosp-2019-12-12-discontinued.3920102/
Published: 2019-04-10T14:16:57.000Z
Author: N/A
Highlights:
PixelExperience for Xiaomi Redmi 4A[rolex] What is this? Pixel Experience is an AOSP based ROM, with Google apps included and all Pixel goodies (launcher, wallpapers, icons, fonts, bootanimation) Our mission is to offer the maximum possible stability and security, along with essential and useful features for the proper functioning of the device Based on Android 9.0 Whats working? Wifi RIL Mobile data GPS Camera Flashlight Camcorder Bluetooth FMRadio Lights Sound / vibration Facelock Known issues Nothing DON'T FLASH GAPPS, ALREADY INCLUDED Download from my Google Drive Donate Liked my work? Give me a beer Translation Help with project translation Stay tuned Our Telegram channel Our blog​
[...]
XDA:DevDB Information Pixel Experience, ROM for the Xiaomi Redmi 4A Contributors dandyfarid, sunnyraj84348, muralivijay Source Code: https://github.com/PixelExperience ROM OS Version: 9.x. Pie ROM Kernel: Linux 3.18. ROM Firmware Required: V10.2.3.0.NCCMIXM TWRP Required: here Based On: AOSP Version Information Status: Stable Created: 10/04/2019 Last Updated: 12/12/2019
[...]
Changelog: 10/04/2019 - Enable bootanimation Half res - Add Custom Hotplug folder - Add Alucard Hotplug - Add Thunderplug Hotplug - Correct blobs entry - Set Zram 1 GB - arm64: Cortex-A53/ARMv8 optimizations for msm8917/20/37/40/52/53/sdm450 - prima: Merge tag 'LA.UM.7.6.r1-04300-89xx.0 - Merge tag 'LA.UM.7.6.r1-04300-89xx.0 - rolex_defconfig: update config - rolex_defconfig: disable VGA_ARB - staging: prima: Correct the ini value to enable default sap interface - msm: kgsl: Remove POPP - Enable Simple GPU Algorithm - Enable State Notifier - Enable Adreno Idler - Enable KCAL color control - Merge Tag v3.18.138 [EOL] from kernel.org - Enable Wireguard - Enable PowerSuspend driver - Add Nightmare Governor - Add DanceDance Governor - Add Intelliactive Governor
[...]
PixelExperience for Xiaomi Redmi 4A[rolex] What is this? Pixel Experience is an AOSP based ROM, with Google apps included and all Pixel goodies (launcher, wallpapers, icons, fonts, bootanimation) Our mission is to offer the maximum possible stability and security, along with essential and useful features for the proper functioning of the device Based on Android 9.0 Whats working? Wifi RIL Mobile data GPS Camera Flashlight Camcorder Bluetooth FMRadio Lights Sound / vibration Facelock Known issues Nothing DON'T FLASH GAPPS, ALREADY INCLUDED Download from my Google Drive Donate Liked my work? Give me a beer Translation Help with project translation Stay tuned Our Telegram channel Our blog​
[...]
Build author/
[...]
dandyfar
[...]
Device Source code
[...]
XDA:DevDB Information Pixel Experience, ROM for the Xiaomi Redmi 4A Contributors dandyfarid, sunnyraj84348, muralivijay Source Code: https://github.com/PixelExperience ROM OS Version: 9.x. Pie ROM Kernel: Linux 3.18. ROM Firmware Required: V10.2.3.0.NCCMIXM TWRP Required: here Based On: AOSP Version Information Status: Stable Created: 10/04/2019 Last Updated: 12/12/2019
[...]
Changelog: 10/04/201
[...]
- Enable bootanimation Half res - Add Custom Hotplug folder
[...]
Add Alucard Hotplug
[...]
Add Thunderplug Hotplug
[...]
Correct blobs entry
[...]
Set Zram 1 GB
[...]
arm64: Cortex-A53/ARMv8 optimizations for msm8917/20/37/40/52/53/sdm450
[...]
prima: Merge tag 'LA.UM.7.
[...]
.r1-04300-89xx.0
[...]
Merge tag 'LA.UM.7.6.r1-04300-89xx.0
[...]
rolex_defconfig: update config - rolex_defconfig: disable VGA_ARB
[...]
staging: prima: Correct the ini value to enable default sap interface
[...]
msm: kgsl: Remove POPP
[...]
Enable Simple GPU Algorithm - Enable State Notifier - Enable Adreno Idler
[...]
Enable KCAL color control
[...]
Merge Tag v3
[...]
18.138 [EOL] from kernel.org
[...]
Enable Wireguard
[...]
Enable PowerSuspend driver
[...]
Intelliactive
[...]
Enable Simple GPU Algorithm
[...]
very light - audio: Merge LA.UM.7.6.r1-04500-89xx.0 - overlay: Enable
[...]
- Remove deprecated/useless
[...]
og: * Merged new CAF tag: LA
[...]
.3.r

---

Title: [ROM][Onclite][9.0.0_r46] AospExtended ROM V6.7 [UNOFFICIAL] | XDA Forums
URL: https://forum.xda-developers.com/posts/80171972/
Published: 2019-09-02T12:37:03.000Z
Author: N/A
Highlights:
is an AOSP based ROM which provides stock UI/
[...]
with useful customizations. Being based on AOSP it provides a smooth experience. We have added useful customizations from various other open source projects and have tried to keep our things simple. A ROM by a user, for a user. #BeExtended
[...]
Download ROM, GApps here for your device! AEX 6.7 for Onclite Google Apps - GApps
[...]
```
[b]-Download the ROM and GApps of your choice
-Backup each and every partition from TWRP Recovery
-Make a full wipe (system,vendor, data, cache, dalvik)
-Format data
-Flash AEX Package
-Install GAPPS package
-Wipe cache!
-And at last Reboot!
 [First boot will take a few minutes! Have patience]
 Clean Flash is always recommended![/b]
[...]
-Base Of the ROM & Version? ->Rom is based on AOSP. Verison is updated monthly. -Why no "Incremental/Delta updates" Support? ->Actually the updates we provide monthly are heavily changed and modified than the previous builds. New stuff is merged and added. So we don't provide incremental updates and recommend a clean flash. -Does this ROM Support Substratum? ->Google killed Substratum support in Pie. You can use it, however, you need to be rooted. We don't support rootless Substratum. -Which Gapps are recommended? ->OpenGapps -How do I root this ROM? ->We recommend Magisk-Will this ROM relock the bootloader? ->No. -What about XPOSED? ->XPOSED is still in beta stage. We like Xposed but it messes up with the system so before giving any bug reports make sure you have Xposed uninstalled. -When Will Be the Next Update? ->No ETAs, please. ROM Will be updated whenever the new build is ready by your maintainer. We generally provide monthly updates with latest security patches and new features. -I am facing FCs, Bugs, Some feature is broken? ->Provide full info about your problem with logcat and the procedure to reproduce it. ->How to take Logcats? -> https://goo.gl/UcTM9 and https://goo.gl/J4CSEP-Adaway is not working ->Download it from here Adaway-SElinux Linux mode changer app is not working nor Busy Box installer app is working. ->Everything is good with the sources. You should try other things first and then contact your maintainer. -I want to contribute to the development of this ROM. ->Join our Github->Join our Gerrit-I want to contribute to the translation of this ROM. ->Visit our Crowdin
[...]
Donation: Buy me something, Paypal https://paypal.me/dhinathayalan If you like my work,Please hit thanks button Special Thanks to : - Abhishek Agarwal for his work on msm8953-common tree - Flex for his work on 4.9 based trees - @mylove90 for his unbeatable work on kernel - @revanthtolety for his contribution and help - @invcble for his tireless testing Device Source: https://github.com/Dhina17/android_kernel_xiaomi_onclite XDA:DevDB Information AOSP-Extended, ROM for the Xiaomi Redmi 7 Contributors Dhina_17, mylove90 Source Code: https://github.com/AospExtended ROM OS Version: 9.x Pie ROM Kernel: Linux 4.x ROM Firmware Required: Stock Pie Firmware with unlocked bootloader Based On: AOSP Version Information Status: Stable Stable Release Date: 2019-11-20 Beta Release Date: 2019-09-02 Created 2019-09-02 Last Updated 2019-12-29
[...]
Apps here for your
[...]
! AEX
[...]
Google Apps -
[...]
for the Xiaomi
[...]
.com/
[...]
9.
[...]
Built using new stable
[...]
Full treble support
[...]
New build updated - 08-09-2019 Changelogs: - Eng ----> Userdebug - Rounded corners fixed - Adaptive brightness fixed - Status bar height fixed - Video playback fixed No need to flash the fix For freshly installation : Wipe all (data,cache,dalvik,system) Flash Rom,stock vendor,genom magic kernel,magic,gapps(your wish) For Update AEX previous build to new build: Wipe cache,dalvik,system(no need to wipe data ) Flash rom ,gapps,stock vendor,genome kernel ,magisk Reboot... Edit -- video playback still persist.. sorry for that

---

Title: Downloads for : Xiaomi Redmi 4A | AndroidFileHost.com
URL: https://androidfilehost.com/?flid=267974&w=files
Published: N/A
Author: N/A
Highlights:
Downloads for : Xiaomi Redmi 4A | AndroidFileHost.com | Download GApps, Roms, Kernels, Themes, Firmware and more. Free file hosting for all Android developers.

- Membership Plans
- About
- Gapps
- Home
- Register Login

# Downloads for : Xiaomi Redmi 4A

### AospExtended

### AospExtended-v5.4-rolex-20180501-1847-OFFICIAL.zip

339Downloads

539.2MBSize

May 01, 2018 | 09:24PMUpload Date

Download

### AospExtended-v5.4-rolex-20180503-2224-OFFICIAL.zip

4,438Downloads

539.2MBSize

May 04, 2018 | 02:32AMUpload Date

Download

### AospExtended-v5.4-rolex-20180506-1922-OFFICIAL.zip

236Downloads

539.2MBSize

May 07, 2018 | 12:27AMUpload Date

Download

### AospExtended-v5.5-rolex-20180517-1632-OFFICIAL.zip

124Downloads

552.5MBSize

May 17, 2018 | 07:33PMUpload Date

Download

### AospExtended-v5.6-rolex-20180617-1801-OFFICIAL.zip

218Downloads

507.9MBSize

Jun 17, 2018 | 08:56PMUpload Date

Download

### AospExtended-v5.7-rolex-20180710-0058-OFFICIAL.zip

370Downloads

515.3MBSize

Jul 10, 2018 | 01:35AMUpload Date

Download

### AospExtended-v5.8-rolex-20180812-2226-OFFICIAL.zip

668Downloads

525.5MBSize

Aug 13, 2018 | 01:24AMUpload Date

Download

### AospExtended-v5.8-rolex-20180823-1708-OFFICIAL.zip

283Downloads

526.4MBSize

Aug 23, 2018 | 05:56PMUpload Date

Download

### AospExtended-v5.8-rolex-20180913-1933-OFFICIAL.zip

486Downloads

526.3MBSize

Sep 13, 2018 | 11:22PMUpload Date

Download

### AospExtended-v5.8-rolex-20181017-1735-OFFICIAL.zip

2,166Downloads

526.3MBSize

Oct 17, 2018 | 06:44PMUpload Date

Download

### Popular files

AospExtended-v4.6-rolex-20180406-1555-OFFICIAL.zip for Xiaomi Redmi 4A(Rolex)

5,478

AospExtended-v5.4-rolex-20180503-2224-OFFICIAL.zip for Xiaomi Redmi 4A(Rolex)

4,438

AospExtended-v4.6-rolex-20180917-1825-OFFICIAL.zip for Xiaomi Redmi 4A(Rolex)

2,571

AospExtended-v5.8-rolex-20181017-1735-OFFICIAL.zip for Xiaomi Redmi 4A(Rolex)

2,166

AospExtended-v4.6-rolex-20180619-0333-OFFICIAL.zip for Xiaomi Redmi 4A(Rolex)

1,300

### Other devices

- Galaxy S10e Samsung
- Xperia Z3 Compact Sony
- Redmi 5 Plus Xiaomi
- Redmi 4A Xiaomi
- Generic Device/Other -Android-
- Samsung Galaxy Core Prime VE Samsung

--
```

**Tool: websearch**

**Input:**
```json
{
  "query": "LineageOS 16 Pie Redmi 4A rolex final build vanilla download",
  "numResults": 5
}
```

**Output:**
```
Title: Downloads for : Xiaomi Redmi 4A | AndroidFileHost.com |  Download GApps, Roms, Kernels, Themes, Firmware and more. Free file hosting for all Android developers.
URL: https://androidfilehost.com/?flid=283520&w=files
Published: N/A
Author: N/A
Highlights:
### LineageOS 16.0
[...]
### lineage-16.0-20181020-UNOFFICIAL-rolex.zip
[...]
### lineage-16.0-20181028-UNOFFICIAL-rolex.zip
[...]
### lineage-16.0-20181111-UNOFFICIAL-rolex.zip
[...]
### lineage-16.0-20181116-UNOFFICIAL-rolex.zip
[...]
lineage-15.1-20180801-UNOFFICIAL-rolex.zip for Xiaomi Redmi 4A(Rolex)

---

Title: Download LineageOS 16 for Redmi 4A
URL: https://cyanogenmods.org/forums/topic/download-lineage-os-16-for-redmi-4a/
Published: 2024-09-03T12:56:16.000Z
Author: N/A
Highlights:
Download LineageOS 16 for Redmi 4A
[...]
Download LineageOS 16 for Redmi 4A
[...]
You can now download and install LineageOS 16 for Redmi 4A. Here is how to install LineageOS 16 on Redmi 4A, with a step-by-step guide. This LineageOS 16 build is brought to you by developer JSPiRiT.
[...]
Follow the links to get other LineageOS 16 and Android Pie ROM builds.
[...]
color=”#F
[...]
_color=”#AA
[...]
DISCLAIMER
[...]
## REQUIRED GUIDES AND DOWNLOADS TO INSTALL LineageOS 16 ON Redmi 4A:
[...]
- TWRP for Redmi 4A(rolex) for this Redmi 4A LineageOS 16 ROM
- How to install TWRP recovery
- Redmi 4A unlock bootloader guide– required to install TWRP recovery
- ROM download link for for Redmi 4A LineageOS 16
- MindTheGApps for LineageOS 16 or Open GApps for LineageOS 16
- How to ROOT LineageOS 16
[...]
## HOW TO DOWNLOAD AND INSTALL LineageOS 16 ON Redmi 4A – Android 9 Pie CUSTOM ROM:
[...]
1. First time installation of LineageOS 16 on Redmi 4A
2. Upgrading LineageOS 16 on Redmi 4A from a previous build of LineageOS 16 ROM
[...]
1. Download and Copy the Redmi 4A LineageOS 16 ROM and Android Pie GApps ZIP file to your phone.
[...]
2. Boot into the TWRP custom Recovery to install this LineageOS 16 on Redmi 4A. [su_note note_color=”#D7E3F4″ text_color=”#728095″ radius=”3″ class=”” id=””]- Make sure to have a Custom recovery like a TWRP recovery or any other custom recovery. – If not then download the TWRP recovery from Downloads link and follow the Custom Recovery Installation Guide(it’s a generic guide which will work for TWRP as well as any other recovery) – Installing TWRP recovery requires an unlocked bootloader on Redmi 4A[/su_note]
[...]
4. First flash the LineageOS 16 for Redmi 4A [su_note note_color=”#D7E3F4″ text_color=”#728095″ radius=”3″ class=”” id=””]- Here is a post explaining how to install recovery flashable zip file [/su_note]
[...]
5. Then install the Android Pie MindTheGapps for LineageOS 16 package. [su_note note_color=”#D7E3F4″ text_color=”#728095″ radius=”3″ class=”” id=””]- Here is a post explaining how to install GApps using TWRP recovery.[/su_note]
[...]
### Upgrading from earlier version of LineageOS 16 on Redmi 4A (rolex):
[...]
1. Copy the latest ROM zip file of LineageOS 16 for Redmi 4A, LineageOS 16 GApps and/or Magisk ROOT package to the phone
2. Boot into Recovery.- Make sure you have a latest custom Recovery that should be able to flash the LineageOS 16 ROM update.
3. Format or wipe the system partition from the custom recovery menu.
4. Install the LineageOS 16 for Redmi 4A. [su_note note_color=”#D7E3F4″ text_color=”#728095″ radius=”3″ class=”” id=””]- Here is a post explaining how to install LineageOS [/su_note]
[...]
5. Reboot and see you have the GApps and ROOT access or NOT. [su_note note_color=”#D8F1C6″ text_color=”#769958″ radius=”3″ class=”” id=””]- Gapps is built in such a way that it will sustain across ROM updates.[/su_note]
[...]
6. If you don’t have GApps after upgrading the LineageOS 16 on Redmi 4A, then flash the GApps. [su_note note_color=”#D7E3F4″ text_color=”#728095″ radius=”3″ class=”” id=””]- Here is a post explaining how to flash GApps using TWRP recovery.[/su_note]
[...]
7. If you don’t have ROOT after upgrading the LineageOS 16 on Redmi 4A, then flash the SuperSU or Magisk or the Lineage SU binary. [su_note note_color=”#D7E3F4″ text_color=”#728095″ radius=”3″ class=”” id=””]- Here is a post explaining How to Enable ROOT on LineageOS 16 ROM [/su_note]
[...]
8. Once everything is done, reboot and Enjoy the LineageOS 16 on Redmi 4A.
[...]
After installing LineageOS 16 on Redmi 4A you may want to install Google Camera (GCam) or enable ROOT access on your phone and here is how you can do that: – How to ROOT LineageOS 16– GCam for Android Pie(this page contains a huge list of GCam for all available devices)

---

Title: LineageOS Downloads
URL: https://download.lineageos.org/
Published: N/A
Author: N/A
Highlights:
LineageOS Downloads

ASUS

Banana Pi

Dynalink

TV Box 4K (2021)wade

Essential

F(x)tec

Fairphone

Fairphone 3 / 3+FP3

Google

Chromecast with Google TV (4K)sabrina

Pixel 9 Pro Foldcomet

Pixel 9 Pro XLkomodo

HardKernel

Lenovo

LG

G7 ThinQ (G710AWM/EM/EMW) / G7+ ThinQjudyln

V30 (Unlocked / T-Mobile / Other)joan

Motorola

edge 30 fusion / moto S30 Protundra

edge 40 pro / moto X40 / edge+ (2023)rtwo

edge s / moto g100nio

moto e7 plus / Lenovo K12guam

moto g 5G - 2024fogo

moto g 5G plusnairo

moto g power 2021borneo

moto g stylus 5Gdenver

moto g stylus 5G (2022)milanf

moto g10 / moto g10 power / Lenovo K13 Notecapri

moto g200 5G / Edge S30xpeng

moto g30 / Lenovo K13 Procaprip

moto g34 5G / moto g45 5Gfogos

moto g9 / g9 play / Lenovo K12 Noteguamp

moto g9 power / Lenovo K12 Procebu

moto z2 force / moto z (2018)nash

one vision / p50kane

Nintendo

Switch v1 / v2 / Lite / OLED [Android TV]nx

Switch v1 / v2 / Lite / OLED [Tablet]nx_tab

Nokia

Nothing

Nubia

Red Magic 5G / 5Snx659j

Nvidia

Jetson (Nano / Nano 2GB) [Android TV]porg

Jetson (Nano / Nano 2GB) [Tablet]porg_tab

Jetson (TX2 / TX2 NX) [Android TV]quill

Jetson (TX2 / TX2 NX) [Tablet]quill_tab

NVIDIA Shield TV (2019) [Android TV]sif

Shield TV (2015 / 2015 Pro / 2017 / 2019 Pro) / Jetson TX1 [Android TV]foster

Shield TV (2015 / 2015 Pro / 2017 / 2019 Pro) / Jetson TX1 [Tablet]foster_tab

OnePlus

Nord CE 2 Lite 5Goscaro

Nord CE 3 Lite 5G / Nord N30 5Glarry

Pad 2 Pro / Pad 3erhai

Pad Pro / Pad 2caihong

OSOM

Radxa

Zero 2 (Android TV)radxa02

Razer

Edge WiFi / 5Gnicole

Realme

9 Pro 5G / 9 5G / Q5oscar

Samsung

Galaxy S20 FE (Exynos)r8s

Galaxy S20 FE (Snapdragon)r8q

Galaxy S20 Ultra (5G)z3s

Galaxy Tab A 8.0 2019 (Wi-Fi)gtowifi

Galaxy Tab A7 10.4 2020 (LTE)gta4l

Galaxy Tab A7 10.4 2020 (Wi-Fi)gta4lwifi

Galaxy Tab S5e (LTE)gts4lv

Galaxy Tab S5e (Wi-Fi)gts4lvwifi

Galaxy Tab S6 Lite (LTE)gta4xl

Galaxy Tab S6 Lite (Wi-Fi)gta4xlwifi

Galaxy Tab S6 Lite 2024 (Wi-Fi)gta4xlswifi

Galaxy Tab S7 (LTE)gts7l

Galaxy Tab S7 (Wi-Fi)gts7lwifi

SHIFT

Smartisan

Solana

Sony

Vsmart

Joy 3 / Joy 3+casuarina

Walmart

onn. TV Box 4K (2021)dopinder

Xiaomi

11 Lite 5G NE / 11 Lite NE 5G / Mi 11 LElisa

12T Pro / Redmi K50 Ultraditing

Mi 10T / Mi 10T Pro / Redmi K30S Ultraapollon

Mi 10T Lite 5G / Mi 10i 5G / Redmi Note 9 Pro 5Ggauguin

Mi 11 Lite 5Grenoir

Mi 11i / Redmi K40 Pro / Redmi K40 Pro+ / Mi 11X Prohaydn

Mi 8 Explorer Editionursa

Mi CC9 / Mi 9 Litepyxis

Mi CC9 Meitu Editionvela

Mi Note 10 / Note 10 Pro / CC9 Protucana

POCO F2 Pro / Redmi K30 Prolmi

POCO F3 / Redmi K40 / Mi 11Xalioth

POCO F4 / Redmi K40Smunch

POCO F5 / Redmi Note 12 Turbomarble

POCO F5 Pro / Redmi K60mondrian

POCO F6 Pro / Redmi K70vermeer

POCO M2 Pro / Redmi Note 9S / Redmi Note 9 Pro / Redmi Note 9 Pro Max / Redmi Note 10 Litemiatoll

Redmi 12C / Redmi 12C NFC / POCO C55earth

Redmi 3S / 3X / 4(X) / [Note 5A / Y1 - Prime]Mi8937

Redmi 4A / 5A / [Note 5A / Y1 - Lite]Mi8917

Redmi 7A / 8 / 8A / 8A DualMi439

Redmi K20 / Mi 9Tdavinci

Redmi Note 10 Pro / Redmi Note 10 Pro Maxsweet

Redmi Note 10S / Redmi Note 10S NFC / Redmi Note 10S Latin America / POCO M5srosemary

Redmi Note 13 Pro 5G / POCO X6 5Ggarnet

Redmi Note 7 Proviolet

Redmi Note 8 / 8Tginkgo

Redmi Turbo 3/POCO F6peridot

ZTE

This device does not exist

---

Title: Xiaomi Redmi 4A / 5A / [Note 5A / Y1 - Lite] - Mi8917 - LineageOS 16.0 Changelog
URL: https://www.lineageoslog.com/16.0/Mi8917
Published: N/A
Author: N/A
Highlights:
Xiaomi Redmi 4A / 5A / [Note 5A / Y1 - Lite] - Mi8917 - LineageOS 16.0 Changelog
[...]
This page is listing the official LineageOS 16.0 (Android Pie 9.0) changes and downloads for Xiaomi Redmi 4A / 5A / [Note 5A / Y1 - Lite] (Mi8917).
[...]
LineageOS Download Page for this device
[...]
# Xiaomi Redmi 4A / 5A / [Note 5A / Y1 - Lite] Mi8917
[...]
### The selected device is not currently supported in LineageOS 16.0.
[...]
Select other version of LineageOS for this device:
[...]
20.0
[...]
or Select a device from the device menu.
[...]
##### Latest changes on the build roster (this device)
[...]
hudson: Promote Mi8917 & Mi8937 & Mi439 to lineage-20
[...]
* Mi8917 & Mi8937: Android 6.0/7.1 ~ Android 13, 2016/2017 ~ 2023 * Mi439: Android 9 ~ Android 13, 2019 ~ 2023 * We got k4.19 booting on both, hope they'll survive on Android 14 too :D * GPU issue on msm8937 k4.19 is fixed! and there're just few issues left on Mi439 k4.19
[...]
Xiaomi Redmi 7A / 8 / 8A / 8A Dual - Mi439 (20.0) Xiaomi Redmi 4A / 5A / [Note 5A / Y1 - Lite] - Mi8917 (20.0) Xiaomi Redmi 3S / 3X / 4(X) / [Note 5A / Y1 - Prime] - Mi8937 (20.0) Xiaomi Redmi 7A / 8 / 8A / 8A Dual - Mi439 (19.1) Xiaomi Redmi 4A / 5A / [Note 5A / Y1 - Lite] - Mi8917 (19.1) Xiaomi Redmi 3S / 3X / 4(X) / [Note 5A / Y1 - Prime] - Mi8937 (19.1)

---

Title: Lineage OS 16 unofficial for redmi 4a. | XDA Forums
URL: https://xdaforums.com/t/lineage-os-16-unofficial-for-redmi-4a.3922427/
Published: 2019-04-18T06:40:46.000Z
Author: N/A
Highlights:
DISCLAIMER: THIS IS AN INITIAL BUILD OF LineageOS 16 FOR Redmi 4A, WHICH MAY HAVE BUGS. MAKE SURE TO BACKUP ALL DATA OF YOUR PHONE. FLASH AT YOUR OWN RISK. Installing a custom ROM may require an unlock bootloader on Redmi 4A, which may VOID your warranty and may delete all your data. Before proceeding further you may consider backup all data on the phone. You are the only person doing changes to your phone; neither the developer nor I can be held responsible for the mistakes done by you. Status of the Redmi 4A LineageOS 16 ROM: WHAT’S WORKING: – Almost everything KNOWN ISSUES: – SEPolicy is permissive REQUIRED GUIDES AND DOWNLOADS TO INSTALL LineageOS 16 ON Redmi 4A: Flashing LineageOS 16 on Redmi 4A for the first time: Points to NOTE: Try to avoid restoring apps backup using Titanium Backup. It may break things up. Don’t restore system data using Titanium Backup! It will definitely break the current installation. It is also discouraged to Restoring Apps + Data using Titanium Backup. Download and Copy the Redmi 4A LineageOS 16 ROM and Android Pie GApps ZIP file to your phone. Boot into the TWRP custom Recovery to install this LineageOS 16 on Redmi 4A. – Make sure to have a Custom recovery like a TWRP recovery or any other custom recovery. – Installing TWRP recovery requires an unlocked bootloader on Redmi 4A Wipe the data partition (or do a factory reset), Cache partition, Dalvik Cache or ART cache and Format the System partition. This will delete all your data on your phone. You may consider complete backup of your phone data or take a NANDROID backup of the current ROM First flash the LineageOS 16 for Redmi 4A Then install the Android Pie MindTheGapps for LineageOS 16 package. Reboot and Enjoy the Android 9 Pie LineageOS 16 on Redmi 4A. Upgrading from earlier version of LineageOS 16 on Redmi 4A (rolex): Copy the latest ROM zip file of LineageOS 16 for Redmi 4A, LineageOS 16 GApps and/or Magisk ROOT package to the phone Boot into Recovery.- Make sure you have a latest custom Recovery that should be able to flash the LineageOS 16 ROM update. Format or wipe the system partition from the custom recovery menu. Install the LineageOS 16 for Redmi 4A – Gapps is built in such a way that it will sustain across ROM updates. If you don’t have GApps after upgrading the LineageOS 16 on Redmi 4A, then flash the GApps. – Here is a post explaining how to flash GApps using TWRP recovery. If you don’t have ROOT after upgrading the LineageOS 16 on Redmi 4A, then flash the SuperSU or Magisk or the Lineage SU binary. Once everything is done, reboot and Enjoy the LineageOS 16 on Redmi 4A. Complete the initial setup and enjoy Android 9 Pie with LineageOS 16 on Redmi 4A. Download Link -Lineage OS 16 https://sourceforge.net/projects/roms-for-xiaomi/files/
```

---

## Assistant (Plan · Big Pickle · 16.7s)

_Thinking:_

The user wants the most stripped-down Android based on Pie (Android 9) for the Redmi 4A. Let me look at what I found:

1. **AospExtended (AEX) v6.7** - Official, last build 2019-08-23, Android 9 Pie, 566.9 MB. Based on AOSP, close to stock. This is the most well-maintained Pie ROM for rolex. XDA users praised its battery life ("battery drain is amazing"). It's minimal and close to stock AOSP.

2. **Pixel Experience Pie** - Android 9, discontinued 2019-12-12. Includes GApps (can't remove them). Not stripped-down since GApps are baked in.

3. **LineageOS 16 (Android 9)** - Unofficial builds only for rolex (by JSPiRiT, last build Oct-Nov 2018). LineageOS 16 was never officially supported for Mi8917. There's unofficial builds but they're very old and likely have bugs.

So for Android 9 Pie on Redmi 4A, the best options for "most stripped down" are:

1. **AospExtended v6.7** (Official) - Final build August 2019. Very close to AOSP with minimal additions. Can flash without GApps. 567 MB. This is the best choice.

2. **LineageOS 16 unofficial** - Old (2018), SEPolicy permissive, likely more bugs. Not worth it.

3. **Pixel Experience Pie** - GApps baked in, can't strip them out.

So **AEX v6.7** is clearly the best Pie option for a stripped-down build. Combine with:

- **Don't flash GApps** (vanilla setup)
- Flash **Infinity Kernel** or **GoGreen kernel** (Pie-compatible versions) for better battery/performance
- Use F-Droid + Aurora Store instead of Play Store

Actually wait - AEX includes some customizations on top of AOSP. If the user wants truly "most stripped down" meaning as close to bare AOSP as possible, then:

1. The AEX ROM itself includes customizations (status bar tweaks, theme engine, etc.)
2. A pure AOSP GSI would be more stripped down

But for Pie on rolex, AEX v6.7 is probably the best and most stable option. Let me give a concise plan.

Actually, I should note that finding these old Pie builds is getting hard since many download links are dead. Let me check if the AEX v6.7 download is still available.

From the search results, the AEX v6.7 file is at SourceForge:
https://sourceforge.net/projects/aospextended-rom/files/rolex/pie/AospExtended-v6.7-rolex-20190823-0458-OFFICIAL.zip

This should still be downloadable.

Let me present a clean plan to the user.

Based on Pie (Android 9), the best stripped-down option for Redmi 4A is:

**AospExtended (AEX) v6.7** — Official, final build 2019-08-23. At 567 MB it's the lightest official Pie ROM for rolex. Very close to AOSP with minimal customizations. Known for excellent battery life ("battery drain is amazing" per XDA).

**Download:** https://sourceforge.net/projects/aospextended-rom/files/rolex/pie/AospExtended-v6.7-rolex-20190823-0458-OFFICIAL.zip

**Setup plan for maximum stripped-down:**

| Step | What | Why |
|------|------|-----|
| 1 | Flash AEX v6.7 **without GApps** | Biggest performance/battery gain — Play Services is the #1 hog on 2GB RAM |
| 2 | Flash **Infinity Kernel** Pie variant | Better battery tuning (alucard governor + hotplug) |
| 3 | Use **F-Droid** + **Aurora Store** | Replace Play Store without Google services |
| 4 | Optional: **MicroG** | Only if you need Push notifications, still lighter than full GApps |

**Other Pie options (worse):**
- **LineageOS 16** — unofficial only, SEPolicy permissive, last build 2018. Buggy.
- **Pixel Experience Pie** — GApps baked in, can't strip them out. Dead project.

**Tradeoff to know:** AEX v6.7 last security patch is **August 2019**. It won't get updates. If you need modern security, crDroid 9.x (Android 13) vanilla is more secure but heavier. Your call.

---

