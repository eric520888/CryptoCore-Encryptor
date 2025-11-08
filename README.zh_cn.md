#  CryptoCore 文件加密器 (Mnemonic File Encryptor)

一款基于 BIP-39 助记词和 AES-256-GCM 军规级加密的文件保险库。
*A file vault built on military-grade AES-256-GCM encryption and BIP-39 mnemonics.*

---

##  如何下载 (How to Download)

**本项目的「源代码」暂未公开。** 您可以从 "Releases" 页面下载已打包好的 Windows 可执行文件 (`.exe`)。

**➡️ [点击此处前往 v1.0 下载页面 (Click Here for Releases)](https://github.com/eric520888/CryptoCore-Encryptor/releases/tag/v1.0)**

---

##  核心功能 (Features)

* **军规级加密 (Military-Grade Encryption):**
    * 使用 AES-256-GCM 算法，您的密钥有 $2^{256}$ 种组合，目前无法被暴力破解。
* **BIP-39 助记词密钥 (Mnemonic Keys):**
    * 您的“密码”不再是 `Password123`，而是一组 24 词的助记词（例如钱包），提供最强大的密钥安全性。
* **多语言界面 (Multi-Language UI):**
    * 支持 英文 (English)、繁体中文 (zh_TW)、简体中文 (zh_CN)、日本语 (ja)。
* **主题切换 (Theme Switcher):**
    * 支持“苹果 (Apple)”风格的浅色模式，与专业的深色模式。
* **(未来支持) 多签加密 (Multi-Sig Support):**
    * 核心引擎已支持 Shamir's Secret Sharing (SSS)，未来将开放此功能，允许多人共同保管文件。

---

##  界面截图 (Screenshots)

### 浅色模式 (Light Mode)
![浅色模式](https://i.imgur.com/image_934be2.png) 
*(请将此 URL 替换为您自己的截图 URL)*

### 深色模式 (Dark Mode)
![深色模式](httpsIAmAFakeURL/image_dark.png)
*(请将此 URL 替换为您自己的截图 URL)*

---

##  执行 .exe 警告！ (Windows 用户必读)

您的 .exe 是使用 PyInstaller 打包的，这会触发**正常但必要**的警告：

1.  **【杀毒软件警告】**：执行 .exe 时，Windows Defender **极有可能**会报警 (误报)。
    * **原因**：PyInstaller 的打包方式和病毒很像。
    * **解决**：请手动选择“信任”或“允许执行”。

2.  **【启动速度警告】**：程序启动**非常慢**！双击后请**耐心等待 5-15 秒**，界面才会弹出。

3.  **【系统限制】**：此文件仅支持 Windows 64-bit 系统。

---

##  授权状态 (License Status)

* **发行版 (Binary / .exe):** 免费提供给个人使用 (Freeware)。
* **源代码 (Source Code):** 暂不开放 (Closed-Source)。
* **版权 (Copyright):** © 2025 [狐狸鬆餅Sonbing_tw]. All Rights Reserved.
