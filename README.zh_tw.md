# 🔒 CryptoCore 檔案加密器 (Mnemonic File Encryptor)

一款基於 BIP-39 助記詞和 AES-256-GCM 軍規級加密的檔案保險庫。
*A file vault built on military-grade AES-256-GCM encryption and BIP-39 mnemonics.*

---

## 🚀 如何下載 (How to Download)

**本專案的「原始碼」暫未公開。** 您可以從「Releases」頁面下載已打包好的 Windows 執行檔 (`.exe`)。

**➡️ [點擊這裡前往 v1.0 下載頁面 (Click Here for Releases)](https://github.com/eric520888/CryptoCore-Encryptor/releases/tag/v1.0)**

---

## ✨ 核心功能 (Features)

* **軍規級加密 (Military-Grade Encryption):**
    * 使用 AES-256-GCM 演算法，您的金鑰有 $2^{256}$ 種組合，目前無法被暴力破解。
* **BIP-39 助記詞金鑰 (Mnemonic Keys):**
    * 您的「密碼」不再是 `Password123`，而是一組 24 詞的助記詞 (例如錢包)，提供最強大的金鑰安全性。
* **多語言介面 (Multi-Language UI):**
    * 支援 英文 (English)、繁體中文 (zh_TW)、简体中文 (zh_CN)、日本語 (ja)。
* **主題切換 (Theme Switcher):**
    * 支援「蘋果 (Apple)」風格的淺色模式，與專業的深色模式。
* **(未來支援) 多簽加密 (Multi-Sig Support):**
    * 核心引擎已支援 Shamir's Secret Sharing (SSS)，未來將開放此功能，允許多人共同保管檔案。

---

## 📸 介面截圖 (Screenshots)

### 淺色模式 (Light Mode)
![淺色模式](https://i.imgur.com/image_934be2.png) 
*(請把這裡的 `https://i.imgur.com/...` 網址，換成您自己上傳截圖的網址)*

### 深色模式 (Dark Mode)
![深色模式](httpsIAmAFakeURL/image_dark.png)
*(請把這裡的 `...` 網址，換成您自己上傳截圖的網址)*

---

## ⚠️ 執行 .exe 警告！ (Windows 使用者必讀)

您的 .exe 是使用 PyInstaller 打包的，這會觸發**正常但必要**的警告：

1.  **【防毒軟體警告】**：執行 .exe 時，Windows Defender **極有可能**會報警 (誤報)。
    * **原因**：PyInstaller 的打包方式和病毒很像。
    * **解決**：請手動選擇「信任」或「允許執行」。

2.  **【啟動速度警告】**：程式啟動**非常慢**！點兩下後請**耐心等待 5-15 秒**，介面才會彈出。

3.  **【系統限制】**：此檔案僅支援 Windows 64-bit 系統。

---

## 📜 授權狀態 (License Status)

* **發行版 (Binary / .exe):** 免費提供給個人使用 (Freeware)。
* **原始碼 (Source Code):** 暫不開放 (Closed-Source)。
* **版權 (Copyright):** © 2025 [狐狸鬆餅Sonbing_tw]. All Rights Reserved.
