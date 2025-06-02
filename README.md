# Gorilla-Tag-Loader

# 🦍 Gorilla Tag C++ Loader - First of Its Kind (XOR Encrypted)

> ⚠️ For educational & research purposes only. Misuse may violate Gorilla Tag's Terms of Service.

---

## 🚀 Overview

This is the **first-ever C++ external loader for Gorilla Tag**, built from scratch for stealth, speed, and simplicity.  
It injects **XOR-encrypted DLLs** into the Gorilla Tag process with **manual mapping**, no `LoadLibrary`, and **zero dependencies**.

---

## 🔧 Features

- ✅ **Manual Mapping Injection** (Bypasses basic detection)
- 🧠 **XOR-Encrypted Payloads** (Decrypted in memory only)
- 👁️ **Zero UI** (Silent terminal-based loader)
- 🧼 **Auto-cleanup** (Removes decrypted DLL after injection)
- 🎯 **Gorilla Tag Compatible** (Mono or IL2CPP)

---

## 🛠️ How to Use

1. Encrypt your Gorilla Tag DLL:
   ```bash
   xor_encrypt.exe YourMod.dll > encrypted_payload.bin
   ```

2. Run the loader as admin (Gorilla Tag must be running):
   ```bash
   GorillaTagLoader.exe
   ```

3. If injection succeeds, loader terminates silently.

---

## ⚙️ Build Instructions

1. Open `GorillaTagLoader.sln` in Visual Studio 2022+.
2. Set configuration to `Release x64`.
3. Compile → Output will be `GorillaTagLoader.exe`.

---

## 🧠 Notes

- Only supports **XOR encryption**.
- Designed for **external DLL injection**, not internal hacks.
- Does **not use HWID checks**.
- Simple and stealthy: no GUI, logging, or network activity.

---

## ⚠️ Disclaimer

This project is for **educational and ethical research** only.  
I take no responsibility for misuse, game bans, or violations of terms of service.

---
