# 🔐 Poxvirid Vault

<p align="center">
  <strong>A completely free, local-first password manager for Windows and Android.</strong>
</p>

<p align="center">
  Your passwords shouldn't live in somebody else's database.<br>
  Poxvirid keeps your credentials <strong>encrypted, offline, and under your control.</strong>
</p>

<p align="center">
  <a href="https://www.axinomyus.com/products/poxvirid">
    <img src="https://img.shields.io/badge/🌐_Website-Visit_Poxvirid-18181b?style=for-the-badge" alt="Website">
  </a>
</p>

<p align="center">
  <strong>Completely free • Fully local • No telemetry • No subscriptions</strong>
</p>

---

## ✨ Poxvirid

<!--
Replace the image below with your main showcase image.

Recommended:
assets/poxvirid-showcase.png
-->

<p align="center">
  <img src="https://www.axinomyus.com/public/assets/uploads/products/f4ddffb7-5f93-4832-8485-ad6196ad08c8.png" alt="Poxvirid Windows and Android" width="100%">
</p>

Poxvirid is a **privacy-first password manager** designed around one simple principle:

> **If your vault doesn't need to leave your device, why send it to a server?**

There is no cloud vault, no advertising network, no telemetry system and no subscription standing between you and your passwords.

Your encrypted vault belongs to **you**.

---

## 💻 Desktop Experience

<!--
DESKTOP SCREENSHOT

Put your Windows/Desktop screenshot here:

assets/poxvirid-desktop.png
-->

<p align="center">
  <img src="https://github.com/user-attachments/assets/17266b24-479f-4812-b60c-27b9620d09c0" alt="Poxvirid Desktop Application" width="90%" />
</p>

Poxvirid provides a full desktop vault experience for Windows with quick access to your credentials, categories, favorites, custom fields and security tools.

### Desktop features

* 🔐 Encrypted local vault
* 🔎 Password security analysis
* 🎲 Secure password generator
* 📁 Categories and organization
* ⭐ Favorites
* 📝 Encrypted notes
* 🧩 Custom fields
* 💾 Encrypted backups
* 📦 Portable Pocket Edition
* 📋 Timed clipboard clearing
* 🔒 Automatic vault locking

---

## 📱 Mobile Experience

<!--
MOBILE SCREENSHOTS

You can replace these with 2-3 Android screenshots:

assets/poxvirid-mobile-1.png
assets/poxvirid-mobile-2.png
assets/poxvirid-mobile-3.png
-->

<p align="center">
  <img src="https://github.com/user-attachments/assets/2a46e595-a192-42ae-a7c6-49aa9c68e8ae" width="30%" alt="Poxvirid Mobile Vault">
  &nbsp;
  <img src="https://github.com/user-attachments/assets/4f2d2980-9a06-491b-91c5-ca53f3eee6aa" width="30%" alt="Poxvirid Mobile Password">
  &nbsp;
  <img src="https://github.com/user-attachments/assets/ced1f8bd-ecd3-4c31-b939-29a03c702820" width="30%" alt="Poxvirid Mobile Security">
</p>

Take your encrypted vault with you on Android while maintaining the same local-first security philosophy.

* 👆 Biometric unlocking
* 📵 Screenshot protection
* 🔐 OS-backed secure key storage
* 🔒 Automatic locking
* 📋 Clipboard protection
* 💾 `.poxvirid` backup support
* 🛡️ Minimal permissions

---

## 🛡️ Privacy by Architecture

Poxvirid is designed to minimize how much trust you need to place in anyone else.

|                      | Poxvirid |
| -------------------- | -------- |
| ☁️ Cloud Vault       | ❌ No     |
| 👁️ Telemetry        | ❌ No     |
| 📢 Advertising       | ❌ No     |
| 👤 Account Required  | ❌ No     |
| 💳 Subscription      | ❌ No     |
| 🔓 Recovery Backdoor | ❌ No     |
| 💾 Local Storage     | ✅ Yes    |
| 🔐 Encrypted Vault   | ✅ Yes    |

**Your passwords remain on your device.**

---

## 🔐 Strong Encryption

### AES-256-GCM

Sensitive vault data is protected using **AES-256-GCM authenticated encryption**, providing confidentiality, integrity and tamper detection.

Each encryption operation uses a fresh nonce and authentication tag.

### Argon2id

Your master password is processed using **Argon2id**, a memory-hard password derivation algorithm designed to make brute-force attacks significantly more expensive.

Poxvirid generates a random **256-bit vault key**, while the master password-derived key protects that vault key.

**Your master password itself is never stored.**

---

## 🔍 Local Security Analysis

<!--
Optional security analysis screenshot:

assets/poxvirid-security.png
-->

<p align="center">
  <img src="https://github.com/user-attachments/assets/690ed7e9-b64a-4017-a778-cc67164a66d6" alt="Poxvirid Security Analysis" width="85%">
  
</p>

Analyze the security of your vault **without sending your credentials to an external service.**

Poxvirid can locally detect:

* Weak passwords
* Reused passwords
* Old passwords
* Passwordless entries
* Missing account information

> **The analysis happens on your device.**

---

## 🎲 Secure Password Generator

<!--
Optional password generator screenshot:

assets/poxvirid-generator.png
-->

<p align="center">
  <img src="https://github.com/user-attachments/assets/4344ddd7-58e6-46f5-8572-fb5370f3d30e" alt="Poxvirid Password Generator" width="30%">
  
</p>


Generate cryptographically secure **passwords and passphrases** directly inside Poxvirid without relying on an online password-generation service.

---

## 💾 Encrypted Backups

Poxvirid uses its own portable encrypted backup format:

```text
.poxvirid
```

Exports use **Argon2id + AES-256-GCM** and can be protected with a separate export password.

During import, Poxvirid validates the file structure, checksum, cryptographic configuration and authentication data before accepting the vault.

### Import options

* Merge
* Full replacement
* Selected items
* Skip conflicts
* Update existing entries
* Duplicate entries

This also makes it possible to move encrypted vault backups between your **Windows and Android devices**.

---

## 📦 Poxvirid Pocket Edition

<!--
Optional Pocket Edition screenshot:

assets/poxvirid-pocket.png
-->

<p align="center">
  <img src="assets/poxvirid-pocket.png" alt="Poxvirid Pocket Edition" width="85%">
</p>

Don't want to install another application?

**Poxvirid Pocket Edition** provides a setup-free Windows build that can be kept in a folder or on portable storage and launched when needed.

**Same vault. Same encryption. No traditional installation required.**

---

## 🧩 Everything Organized

Your vault can contain much more than a simple username and password.

Organize your data using:

* 📁 Categories
* ⭐ Favorites
* 🗂️ Custom tabs
* 🏢 Workspaces
* 👤 Usernames
* 📧 Email addresses
* 🌐 Websites
* 📝 Encrypted notes
* 🧩 Custom fields
* 🔐 Sensitive encrypted fields

Everything is designed around keeping your vault useful **without requiring a cloud backend.**

---

## 🪟 Windows + Android

| Platform                  | Availability |
| ------------------------- | :----------: |
| 🪟 Windows                |       ✅      |
| 📦 Windows Pocket Edition |       ✅      |
| 🤖 Android                |       ✅      |

Your encrypted `.poxvirid` backups can be transferred between supported platforms.

---

## 🆓 Actually Free

**No trial. No premium security tier. No monthly subscription.**

Poxvirid's core security features are available completely free.

```text
✓ Encrypted local storage
✓ Password generator
✓ Security analysis
✓ Encrypted backups
✓ Windows application
✓ Android application
✓ Pocket Edition
✓ No advertisements
✓ No telemetry
✓ No subscription
```

---

## 🎯 Built For

**Developers • System Administrators • Privacy-conscious users • Independent professionals • Small organizations • Offline systems • Restricted environments**

And anyone who believes:

> **Local ownership > Cloud dependency**
> **Privacy > Telemetry**
> **Encryption > Trust**

---

## ⚠️ No Backdoor

Poxvirid intentionally has **no master-password recovery backdoor**.

If you lose your master password and don't have access to a valid encrypted backup, your vault cannot be recovered.

**That's not a missing feature. That's what owning your encryption keys means.**

---

## 🚀 Get Poxvirid

<p align="center">
  <a href="https://www.axinomyus.com/products/poxvirid">
    <img src="https://img.shields.io/badge/Official_Website-Poxvirid-18181b?style=for-the-badge" alt="Poxvirid Website">
  </a>
  <a href="https://www.axinomyus.com/downloads/releases/5/Poxvirid-Setup-1.2.0-x64.exe">
    <img src="https://img.shields.io/badge/Windows-Download-0078D4?style=for-the-badge&logo=windows" alt="Windows">
  </a>
  <a href="https://www.axinomyus.com/downloads/releases/3/Poxvirid-Android-1.2.0.apk">
    <img src="https://img.shields.io/badge/Android-Download-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android">
  </a>
</p>

> ⚠️ Download Poxvirid only from official **Axinomyus** distribution channels and verify the provided SHA-256 checksum when appropriate.

---

<p align="center">
  <strong>🔐 Your vault should not be somebody else's database.</strong>
</p>

<p align="center">
  <strong>Poxvirid Vault</strong><br>
  Completely free. Fully local. No telemetry. No subscriptions.<br>
  <strong>All your data in your pocket.</strong>
</p>

<p align="center">
  Made by <a href="https://www.axinomyus.com"><strong>Axinomyus</strong></a>
</p>
