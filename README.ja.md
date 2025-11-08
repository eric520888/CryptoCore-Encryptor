#  CryptoCore ファイル暗号化 (Mnemonic File Encryptor)

BIP-39 ニーモニックと AES-256-GCM 軍用レベル暗号化に基づくファイルボールトです。
*A file vault built on military-grade AES-256-GCM encryption and BIP-39 mnemonics.*

---

##  ダウンロード方法 (How to Download)

**現在、このプロジェクトのソースコードは公開されていません。** パッケージ化された Windows 実行可能ファイル（`.exe`）は、「Releases」ページからダウンロードできます。

**➡️ [v1.0 ダウンロードページはこちら (Click Here for Releases)](https://github.com/eric520888/CryptoCore-Encryptor/releases/tag/v1.0)**

---

##  主な機能 (Features)

* **軍用レベルの暗号化 (Military-Grade Encryption):**
    * AES-256-GCM アルゴリズムを使用。キーには $2^{256}$ 通りの組み合わせがあり、総当たり攻撃（ブルートフォース）による解読は不可能です。
* **BIP-39 ニーモニックキー (Mnemonic Keys):**
    * 「パスワード」はもはや `Password123` ではなく、24単語のシードフレーズ（ウォレットなど）であり、最強のキーセキュリティを提供します。
* **多言語 UI (Multi-Language UI):**
    * 英語 (English)、繁体字中国語 (zh_TW)、簡体字中国語 (zh_CN)、日本語 (ja) をサポート。
* **テーマ切り替え (Theme Switcher):**
    * クリーンな「Apple スタイル」のライトモードと、プロフェッショナルなダークモードをサポート。
* **(近日対応) マルチシグ暗号化 (Multi-Sig Support):**
    * コアエンジンはすでに Shamir's Secret Sharing (SSS) をサポートしています。将来的には、複数人でのファイル共同保管を可能にするこの機能を公開する予定です。

---

##  スクリーンショット (Screenshots)

### ライトモード (Light Mode)
![ライトモード](https://i.imgur.com/image_934be2.png) 
*(この URL をご自身のスクリーンショット URL に置き換えてください)*

### ダークモード (Dark Mode)
![ダークモード](httpsIAmAFakeURL/image_dark.png)
*(この URL をご自身のスクリーンショット URL に置き換えてください)*

---

##  .exe 実行時の警告 (Windows ユーザー必読)

この .exe は PyInstaller でパッケージ化されており、**正常ですが必要**な警告が表示されます：

1.  **【ウイルス対策ソフトの警告】**: .exe を実行すると、Windows Defender が**高い確率**でウイルスとして警告します（誤検知）。
    * **理由**: PyInstaller のパッケージ化方法は、多くのウイルスの手法と似ているためです。
    * **解決策**: 手動で「信頼する」または「実行を許可する」を選択してください。

2.  **【起動速度の警告】**: プログラムの起動は**非常に遅い**です！ダブルクリックした後、UI が表示されるまで**5〜15秒ほど辛抱強くお待ちください**。

3.  **【システム要件】**: このファイルは Windows 64-bit システムのみをサポートしています。

---

##  ライセンス状況 (License Status)

* **バイナリ版 (Binary / .exe):** 個人使用は無料 (Freeware)。
* **ソースコード (Source Code):** 現在非公開 (Closed-Source)。
* **著作権 (Copyright):** © 2025 [狐狸鬆餅Sonbing_tw]. All Rights Reserved.
