# 🛡️ Canadian Shield

**Canadian Shield** is a secure, client-side offline encryption application designed for maximum privacy and simplicity. It allows you to encrypt and decrypt sensitive text messages and files directly in your browser without any data ever leaving your device or touching a remote server.

## ✨ Features
* **Zero-Knowledge / Local-Only:** All cryptographic operations happen entirely client-side using the native browser Web Crypto API.
* **Dual Functionality:** Supports both text encryption/decryption (with Base64 output) and file encryption (supporting any file format up to 500 MB).
* **Strong Cryptography:** Utilizes **AES-GCM** authenticated encryption coupled with **PBKDF2** key derivation (600,000 iterations with high-entropy salt and IV).
* **Secure Passphrase Generator:** Built-in generator to create strong, custom-length cryptographic passphrases with symbol and number toggles.
* **Progressive Web App (PWA):** Fully functional offline support with a network-first service worker to ensure you always run the latest version, ready to install to your desktop or mobile home screen.

## 🚀 Built With
* **HTML5 / CSS3 / Vanilla JavaScript** (Single-file architecture, no external JS frameworks or telemetry)
* **Web Crypto API** (`SubtleCrypto` for hardware-accelerated cryptographic performance)
