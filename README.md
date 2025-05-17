# AES Encryption Lab

This is a basic lab where I practiced encrypting and decrypting files using **AES Crypt** on Linux (Ubuntu).

---

## 🧩 Objective

To learn how to:
- Install **AES Crypt** on Ubuntu using a `.tar.gz` archive
- Encrypt a file using AES
- Decrypt it using the same password "M123"

---

## 🔧 Installing AES Crypt

Since `aescrypt` wasn't available on my system, I downloaded and installed it manually:

```bash
wget https://www.aescrypt.com/download/aescrypt_cli-4.2.6-Linux-x86_64.tar.gz
tar -xzvf aescrypt_cli-4.2.6-Linux-x86_64.tar.gz
cd aescrypt_cli-4.2.6-Linux-x86_64/bin
sudo mv aescrypt /usr/local/bin/
