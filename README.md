# Moss Companion: downloads

Installers for **Moss Companion**, a calm desktop companion that lives at the top of your screen.

**Get Moss from the [latest release](https://github.com/sailesh720/moss-releases/releases/latest)**, or from the website: https://moss-companion.vercel.app

| Your computer | File |
| --- | --- |
| Mac with Apple Silicon (M1 or newer), macOS 13+ | `Moss-Companion-<version>-mac-arm64.dmg` |
| Intel Mac, macOS 13+ | `Moss-Companion-<version>-mac-x64.dmg` |
| Windows 10 or 11, 64-bit | `Moss-Companion-<version>-windows-x64-setup.exe` |
| Linux x86-64 | `Moss-Companion-<version>-linux-x86_64.AppImage` or `-linux-amd64.deb` |

Each release has a `SHA256SUMS.txt`. To check a download: `shasum -a 256 <file>` (Mac), `certutil -hashfile <file> SHA256` (Windows) or `sha256sum <file>` (Linux), and compare with the list.

The installers aren't signed with paid certificates yet. The first time on a Mac, choose **Open Anyway** in System Settings › Privacy & Security; on Windows, choose **More info › Run anyway**.

This repository holds only release files. Moss's source code is not here.
