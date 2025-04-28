# AES-CBC Playground

🛡️ **AES-256-CBC Encryption/Decryption Tester**  

A lightweight client-side web tool for verifying your NestJS AES-256-CBC + SHA-256 key derivation implementation.

## 🔑 Features

- **Key derivation**: SHA-256 of your passphrase → 32-byte AES key  
- **IV**: 16 random bytes, hex-prefixed to ciphertext  
- **Mode**: AES-CBC with PKCS7 padding  
- **UI**: Toggle between Encrypt/Decrypt, view input/output in hex

## 🚀 Live Demo

https://AbdelrahmanBayoumi.github.io/aes-cbc-playground/

## 📋 Usage

1. **Encrypt**  
   - Enter your passphrase and plaintext  
   - Click **Encrypt** → get `ivHex:cipherHex`  

2. **Decrypt**  
   - Enter the same passphrase and ciphertext (`ivHex:cipherHex`)  
   - Click **Decrypt** → retrieve original plaintext  

## 🛠️ Dev

```bash
git clone https://github.com/AbdelrahmanBayoumi/aes-cbc-playground.git
cd aes-cbc-playground
open index.html  # or serve with any static‐file server
```
