# Ace Loader

**Ace Loader** is a custom Windows launcher(injector) designed to securely manage, download, and inject Java-based mod binaries into a running `java.exe` process.

The loader supports multiple mod variants and includes account authentication, license validation, HWID checks, and system protection mechanisms.

---

## What Ace Loader Does

Ace Loader functions as a centralized **mod distribution and injection launcher** with the following capabilities:

- Downloads mod binaries (`.dll`) from a remote source (database or Pastebin)
- Injects the selected mod into a running `java.exe` process
- Supports mods originally built as `.jar` files and converted into `.dll` format
- Allows users to select different mod versions through the launcher
- Eliminates the need for manual file handling or setup

---

## Security & Authentication

Ace Loader includes multiple security layers to control access and protect licensing:

- Account login system
- License key verification
- HWID (Hardware ID) validation
- System checks to prevent unauthorized use

---

## Mod Versions

Ace Loader provides multiple mod variants to suit different playstyles:

### Ace Lite (Ghost / Legit)
- Designed for **legit-style gameplay**
- Subtle, low-visibility features
- Intended to blend in and appear natural during gameplay
- Minimal footprint and discreet behavior

### Ace Extreme (Rage / Blatant)
- Designed for **aggressive and blatant gameplay**
- Full feature set with maximum impact
- No focus on subtlety or concealment
- Intended for users who want unrestricted functionality

---

## Typical Workflow

1. Launch **Ace Loader**
2. Log in using your account credentials
3. Select the desired mod version (Lite / Extreme)
4. Ace Loader downloads the required `.dll`
5. The loader injects the mod into `java.exe`

---

## Repository Purpose

This repository is used to host:

- Compiled mod binaries (`.dll`)
- Java components (`.jar`)
- Version check files used by the launcher

> Source code is not publicly available in this repository.

---

## Requirements

- Windows operating system
- Java (required for the target process)
- Valid Ace Loader account and license key

---

## Disclaimer

This project is intended for **educational and experimental purposes only**.  
Users are responsible for how they use the software and must comply with all applicable terms of service and local laws.

---

## License

No license is currently provided. All rights reserved unless stated otherwise.
