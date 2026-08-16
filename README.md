# 🔐 Poxvirid Vault

**A completely free, local-first password manager for Windows and Android.**

Your passwords shouldn't live in somebody else's database.

Poxvirid Vault keeps your credentials **encrypted, offline, and under your control** - without cloud accounts, subscriptions, telemetry, or advertising.

> **Completely free. Fully local. All your data in your pocket.**

## 🛡️ Privacy by Architecture

Poxvirid follows a simple principle:

**If your vault never needs to leave your device, why send it to a server?**

There is:

* ☁️ **No cloud vault**
* 📡 **No password transmission**
* 👁️ **No telemetry**
* 📢 **No advertising SDK**
* 👤 **No Poxvirid account required**
* 💳 **No subscription**
* 🔒 **No master-password recovery backdoor**

Your encrypted vault stays on your device.

## 🔐 Strong Encryption

Poxvirid uses modern cryptographic primitives designed to protect sensitive credentials.

### AES-256-GCM

Sensitive vault data is protected using **AES-256-GCM authenticated encryption**, providing confidentiality, integrity, and tamper detection.

Each encryption operation uses a fresh nonce and authentication tag.

### Argon2id

Your master password is processed using **Argon2id**, a memory-hard password derivation algorithm designed to make brute-force attacks significantly more expensive.

Poxvirid generates a random **256-bit vault key**, while the master password-derived key is used to protect that vault key.

Your master password itself is never stored.

## 💻 Windows + Android

Use the same security model across your devices.

| Platform                  | Availability |
| ------------------------- | ------------ |
| 🪟 Windows                | ✅ Available  |
| 🤖 Android                | ✅ Available  |
| 📦 Windows Pocket Edition | ✅ Available  |

Encrypted `.poxvirid` backups can be transferred between Windows and Android.

## ⚡ Built for Everyday Security

Poxvirid isn't just encrypted storage.

It includes practical protections designed to reduce credential exposure during normal use:

* 🔒 Automatic vault locking
* 🧠 Vault-key memory cleanup
* 📋 Timed clipboard clearing
* 📱 Android screenshot & screen-recording protection
* 👆 Biometric unlocking on supported Android devices
* 🔑 OS-backed secure key storage
* 🛡️ Minimal Android permissions
* 🔎 Local password security analysis

## 🔍 Local Security Analysis

Analyze your vault without sending password hashes or credentials to an external service.

Poxvirid can locally detect:

* Weak passwords
* Reused passwords
* Old passwords
* Passwordless entries
* Missing account identity information

**The analysis happens on your device.**

## 🎲 Secure Password Generator

Generate cryptographically secure:

* Passwords
* Passphrases

without relying on an online password-generation service.

## 💾 Encrypted Backups

Poxvirid uses its own portable:

```text
.poxvirid
```

encrypted backup format.

Exports use **Argon2id + AES-256-GCM** and can be protected with a separate export password.

During import, Poxvirid validates the file structure, checksum, cryptographic configuration, and authentication data before accepting the vault.

Import modes include:

* Merge
* Full replacement
* Selected items
* Skip conflicts
* Update existing entries
* Duplicate entries

## 📦 Poxvirid Pocket Edition

Don't want to install another application?

**Poxvirid Pocket Edition** provides a setup-free Windows build that can be kept in a folder or on portable storage and launched when needed.

Same vault.

Same encryption.

No traditional installation required.

## 🧩 Organized Vault

Poxvirid provides more than a simple password list.

Organize credentials using:

* Categories
* Favorites
* Custom tabs
* Workspaces
* Usernames
* Email addresses
* Websites
* Encrypted notes
* Custom fields
* Sensitive encrypted custom fields

Everything is designed around keeping the vault useful **without requiring a cloud backend**.

## 🆓 Actually Free

No trial.

No premium security tier.

No monthly subscription.

No advertising.

Core security features, encrypted storage, password generation, security analysis, backups, Windows, Android, and Pocket Edition are available **completely free**.

## 🎯 Who Is Poxvirid For?

Poxvirid is built for:

**Developers • System Administrators • Privacy-conscious users • Independent professionals • Small organizations • Offline systems • Restricted environments**

and anyone who prefers:

```text
Local ownership > Cloud dependency
Privacy > Telemetry
Encryption > Trust
```

## ⚠️ No Backdoor

Poxvirid intentionally has **no master-password recovery backdoor**.

If you lose your master password and don't have access to a valid encrypted backup, your vault cannot be recovered.

That's not a missing feature.

That's what owning your encryption keys means.

## 🚀 Download Poxvirid

Poxvirid is currently available for:

**Windows • Windows Pocket Edition • Android**

👉 **Official website:**
https://www.axinomyus.com/products/poxvirid

Download Poxvirid only from official Axinomyus distribution channels and verify the provided SHA-256 checksum when appropriate.

---

### 🔐 Your vault should not be somebody else's database.

**Poxvirid Vault**

Completely free.
Fully local.
No telemetry.
No subscriptions.
No cloud vault.

**All your data in your pocket.**

Made by **Axinomyus**
