# RUACH

> **Direct, high-speed, offline file sharing across Android, Windows, and Linux.**  
> No cloud. No accounts. No tracking. Pure local peer-to-peer transfer.

[![Latest Release](https://img.shields.io/badge/Release-v1.0-00E5FF?style=flat-square&logo=github)](https://github.com/pbits1/Ruach/releases/latest)
[![License: MIT](https://img.shields.io/badge/License-MIT-00E676?style=flat-square)](LICENSE)
[![Platforms](https://img.shields.io/badge/Platforms-Android%20%7C%20Windows%20%7C%20Linux-7C4DFF?style=flat-square)](#downloads)

---

## Downloads

Download the latest version of RUACH for your platform:

| Platform | Format | Direct Download | Requirements |
|:---|:---:|:---:|:---|
| **Android** | `.apk` | [**Download Ruach.apk**](https://github.com/pbits1/Ruach/releases/latest/download/Ruach.apk) | Android 11+ (API 30–34) |
| **Windows** (Installer) | `.msi` | [**Download Ruach.msi**](https://github.com/pbits1/Ruach/releases/latest/download/Ruach.msi) | Windows 10 & 11 (64-bit) |
| **Windows** (Portable) | `.exe` | [**Download Ruach.exe**](https://github.com/pbits1/Ruach/releases/latest/download/Ruach.exe) | Standalone executable |
| **Linux** | `.deb` | [**Download Ruach.deb**](https://github.com/pbits1/Ruach/releases/latest/download/Ruach.deb) | Debian, Ubuntu, Pop!_OS, Mint |

---

## Features

### ⚡ High-Throughput Performance
- **Hardware Line-Rate Streaming**: Streams data directly across physical network interfaces at raw hardware speed, saturating local Wi-Fi or Ethernet bandwidth with minimal system overhead.
- **No File Size Limits**: Move massive 4K video files, disk images, and multi-gigabyte project directories smoothly.
- **Reliable Background Execution**: Built-in service handling ensures long-running transfers complete without disruption from operating system battery optimizers.

### 🌐 Dual Sharing Modes (Native Mesh & Zero-Install WebLink)
- **Direct Mesh (App-to-App)**: Instant, zero-configuration local peer discovery over Wi-Fi or mobile hotspots between Android, Windows, and Linux devices.
- **WebLink Mode (No App Required)**: Share files with recipients on any device with a browser (iPhone, iPad, Mac, or guest computers) via a local QR code or link.

### 🔒 100% Offline & Private by Design
- **Strictly Local Network**: Transfers operate entirely within your local Wi-Fi, Ethernet, or mobile hotspot. Zero bytes are transmitted to external servers.
- **Zero Accounts & Zero Tracking**: No registration, no email address, no phone number, and zero analytics telemetry.
- **Host Session Control**: Host approval allows you to approve or decline incoming connections, preventing unauthorized access.

### 📂 Complete Folder & Media Preservation
- **Nested Folder Hierarchies**: Send complete directory trees with relative folder paths preserved—no manual compression or archiving required.
- **Categorized Media Hub**: Instant filters for Photos, Videos, Documents, Audio, and App packages.
- **End-to-End Verification**: Cryptographic SHA-256 checks validate payload integrity on the fly to eliminate silent file corruption.

---

## Installation

### Android
1. Download [`Ruach.apk`](https://github.com/pbits1/Ruach/releases/latest/download/Ruach.apk) on your device.
2. Tap the downloaded file to install (allow *"Install unknown apps"* if prompted).
3. Open RUACH and grant standard storage and nearby device permissions to start transferring.

### Windows
- **Installer**: Run [`Ruach.msi`](https://github.com/pbits1/Ruach/releases/latest/download/Ruach.msi) and follow the setup wizard.
- **Portable**: Run [`Ruach.exe`](https://github.com/pbits1/Ruach/releases/latest/download/Ruach.exe) directly from any folder.

### Linux (Debian / Ubuntu)
```bash
curl -LO https://github.com/pbits1/Ruach/releases/latest/download/Ruach.deb
sudo apt install ./Ruach.deb
```

---

## Verification

Official release packages are accompanied by SHA-256 checksums to verify package authenticity.

**Linux / macOS:**
```bash
sha256sum Ruach.deb
```

**Windows (PowerShell):**
```powershell
Get-FileHash .\Ruach.msi -Algorithm SHA256
```

---

## License

RUACH is open-source software licensed under the [MIT License](LICENSE).  
Copyright &copy; 2026 Ekangi Systems Private Limited. All rights reserved.
