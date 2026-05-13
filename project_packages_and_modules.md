# Redmi 4A (rolex) Optimization Project — Packages & Modules Reference

**Project:** AospExtended v6.7 / ArrowOS 11 optimization for Xiaomi Redmi 4A (rolex)
**Period:** March 6, 2026 onward
**Host OS:** Ubuntu 24.04 (Noble)

---

## 1. Android Platform Tools (adb / fastboot)

| Tool | Source | Link |
|------|--------|------|
| ADB + Fastboot (Linux) | Google SDK Platform-Tools | https://dl.google.com/android/repository/platform-tools-latest-linux.zip |
| Release Notes | Android Developers | https://developer.android.com/tools/releases/platform-tools |

---

## 2. System Packages (apt)

| Package | Purpose | Install Command |
|---------|---------|----------------|
| `brotli` | Decompress `.new.dat.br` ROM files | `sudo apt install brotli` |
| `android-sdk-libsparse-utils` | `simg2img` / `img2simg` sparse image tools | `sudo apt install android-sdk-libsparse-utils` |
| `mkbootimg` | Create Android boot images | `sudo apt install mkbootimg` |
| `abootimg` | Read/write/update Android boot images | `sudo apt install abootimg` |
| `python3` + `python3-pip` | Runtime for sdat2img & helper scripts | `sudo apt install python3 python3-pip python3-venv` |
| `curl` | Downloading files | `sudo apt install curl` |
| `wget` | Downloading files | `sudo apt install wget` |
| `aria2` | Download accelerator | `sudo apt install aria2` |
| `zip` / `unzip` | ZIP compression | `sudo apt install zip unzip` |
| `pigz` | Parallel gzip | `sudo apt install pigz` |
| `bzip2` | BZ2 compression | `sudo apt install bzip2` |
| `7zip` | 7z/p7zip archiver | `sudo apt install 7zip p7zip-full` |
| `pv` | Pipe progress viewer | `sudo apt install pv` |

**Ubuntu package info pages:**
- brotli: https://packages.ubuntu.com/noble/brotli
- android-sdk-libsparse-utils: https://packages.ubuntu.com/noble/android-sdk-libsparse-utils
- mkbootimg: https://packages.ubuntu.com/noble/mkbootimg
- abootimg: https://packages.ubuntu.com/noble/abootimg

---

## 3. Python Scripts

| Script | Purpose | Source |
|--------|---------|--------|
| `sdat2img.py` | Convert `.dat` sparse images to ext4 `.img` | https://raw.githubusercontent.com/xpirt/sdat2img/master/sdat2img.py |
| sdat2img repo | GitHub project page | https://github.com/xpirt/sdat2img |

---

## 4. Custom Recovery (TWRP)

| File | Version | Download |
|------|---------|----------|
| TWRP for rolex | 3.3.1-0 (latest) | https://eu.dl.twrp.me/rolex/twrp-3.3.1-0-rolex.img |
| TWRP mirror page | — | https://twrp.me/xiaomi/xiaomiredmi4a.html |

---

## 5. Custom Kernels

### 5.1 GoGreenCAF Kernel
| Detail | Value |
|--------|-------|
| Version | 3.18.140-Q (Android 9/10) |
| Download | https://sourceforge.net/projects/gogreenxiaomi/files/Rolex%28Redmi4a%29/AndroidQ/rolex-GoGreenCAF.Kernel-VER.3.18.140-Q-20200124.zip/download |
| XDA Thread | https://xdaforums.com/t/kernel-p-9-q-10-gogreen-rolex-hm4a.4038775/ |
| Source Code | https://github.com/areyoudeveloper/android_kernel_msm8917 |

### 5.2 NgntdKernel
| Detail | Value |
|--------|-------|
| Version | LSK-v1 (Android 9 Pie) |
| Download | https://androidfilehost.com/?fid=11410963190603860146 |
| XDA Thread | https://xdaforums.com/t/ngntdkernel-kernel-for-the-xiaomi-redmi-4a-and-xiaomi-redmi-5a.3882261/ |
| Source Code | https://github.com/najahiiii/NgntdKernel_F |

---

## 6. Custom ROMs

### 6.1 AospExtended v6.7 (Android 9 Pie)
| Detail | Value |
|--------|-------|
| Build | AospExtended-v6.7-rolex-20190823-0458-OFFICIAL.zip |
| Download | https://sourceforge.net/projects/aospextended-rom/files/rolex/pie/AospExtended-v6.7-rolex-20190823-0458-OFFICIAL.zip/download |
| XDA Thread | https://xdaforums.com/t/rom-9-0-0_r46-official-aospextended-rom-v6-7-for-redmi-4a-rolex.3867054/ |
| SourceForge | https://sourceforge.net/projects/aospextended-rom/files/rolex/pie/ |

### 6.2 ArrowOS 11 (Android 11)
| Detail | Value |
|--------|-------|
| Build | Arrow-v11.0-rolex-UNOFFICIAL-20210613-VANILLA.zip |
| XDA Thread | https://xdaforums.com/t/rom-v11-0-arrow-os-unofficial-rolex-riva.4295147/ |
| Status | Download link no longer publicly available (unofficial build from 2021) |
| Alternative | Check XDA thread for mirrors or build from source: https://github.com/ArrowOS |

---

## 7. Google Apps

| Package | Platform | Android | Link |
|---------|----------|---------|------|
| Open GApps Pico | ARM64 | 9.0 | https://opengapps.org/?api=9.0&arch=arm64&variant=pico |
| Open GApps (direct SF) | ARM64 | 9.0 | https://sourceforge.net/projects/opengapps/files/arm64/20220503/open_gapps-arm64-9.0-pico-20220503.zip/download |

---

## 8. App Stores / APKs

| App | Source | Link |
|-----|--------|------|
| Aurora Store | F-Droid | https://f-droid.org/packages/com.aurora.store |
| Aurora Store (direct) | Official site | https://auroraoss.com/files |
| F-Droid client | F-Droid | https://f-droid.org/F-Droid.apk |

---

## 9. Kernel Source Trees (for reference)

| Kernel | Source |
|--------|--------|
| Stock AEX kernel (TeamRedMi) | https://github.com/ECr34T1v3 |
| CAF kernel source (muralivijay) | https://github.com/muralivijay/android_kernel_xiaomi_msm8917 |
| ArrowOS 11 kernel (rajsharma55) | https://github.com/rajsharma55/android_kernel_xiaomi_msm8917 |
| GoGreenCAF source | https://github.com/areyoudeveloper/android_kernel_msm8917 |
| NgntdKernel source | https://github.com/najahiiii/NgntdKernel_F |
| Triton kernel | https://github.com/Thagoo/Triton_kernel_xiaomi_msm8917 |

---

## 10. Quick Install (Ubuntu 24.04)

```bash
# Core Android tools
sudo apt install brotli android-sdk-libsparse-utils mkbootimg abootimg

# Python and downloading
sudo apt install python3 python3-pip python3-venv curl wget aria2

# Compression
sudo apt install zip unzip gzip pigz bzip2 7zip p7zip-full xz-utils

# Utilities
sudo apt install pv openssl

# Platform-tools (manual download)
wget https://dl.google.com/android/repository/platform-tools-latest-linux.zip
unzip platform-tools-latest-linux.zip
# Add to PATH: export PATH=$PATH:$(pwd)/platform-tools

# sdat2img
sudo wget -O /usr/local/bin/sdat2img \
  https://raw.githubusercontent.com/xpirt/sdat2img/master/sdat2img.py
sudo chmod +x /usr/local/bin/sdat2img
```
