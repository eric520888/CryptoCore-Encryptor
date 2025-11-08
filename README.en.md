# 🔒 CryptoCore File Encryptor

A file vault built on military-grade AES-256-GCM encryption and BIP-39 mnemonics.

---

## 🚀 How to Download

**The source code for this project is currently not public.** You can download the packaged Windows executable (`.exe`) from the "Releases" page.

**➡️ [Click Here for the v1.0 Download Page (Releases)](https://github.com/eric520888/CryptoCore-Encryptor/releases/tag/v1.0)**

---

## ✨ Core Features

* **Military-Grade Encryption:**
    * Uses the AES-256-GCM algorithm. Your key has $2^{256}$ possible combinations, making it impossible to brute-force.
* **BIP-39 Mnemonic Keys:**
    * Your "password" is no longer `Password123`, but a 24-word seed phrase (like a crypto wallet), providing maximum key security.
* **Multi-Language UI:**
    * Supports English (en), Traditional Chinese (zh_TW), Simplified Chinese (zh_CN), and Japanese (ja).
* **Theme Switcher:**
    * Features a clean, "Apple-style" light mode and a professional dark mode.
* **(Coming Soon) Multi-Sig Support:**
    * The core engine already supports Shamir's Secret Sharing (SSS). This feature will be enabled in the future to allow for multi-person file custody.

---

## 📸 Screenshots

### Light Mode
![Light Mode](https://i.imgur.com/image_934be2.png) 
*(Please replace this with your own screenshot URL)*

### Dark Mode
![Dark Mode](httpsIAmAFakeURL/image_dark.png)
*(Please replace this with your own screenshot URL)*

---

## ⚠️ IMPORTANT! (Windows User Guide)

This `.exe` is packaged with PyInstaller, which will trigger **normal but necessary** warnings:

1.  **【Antivirus Warning】**: Windows Defender will **very likely** flag this as a virus (False Positive).
    * **Why**: PyInstaller's packaging method is identical to how many viruses are packed.
    * **Solution**: You must manually select "Trust" or "Allow this app to run".

2.  **【Startup Speed】**: The app starts **very slowly**! After double-clicking, please **wait patiently for 5-15 seconds** for the UI to appear.

3.  **【System Limit】**: This file only supports Windows 64-bit systems.

---

## 📜 License Status

* **Binary / .exe:** Freeware for personal use.
* **Source Code:** Closed-Source (for now).
* **Copyright:** © 2025 [狐狸鬆餅Sonbing_tw]. All Rights Reserved.
