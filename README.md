# 🔐 Cloud-Encryption  

---

## 📌 Project Overview

The goal of this project is to develop a **secure cloud storage application** for services like **Dropbox, Google Drive, Box, Office365**, etc. All uploaded files are **automatically encrypted**, ensuring only users within a defined **"Secure Cloud Storage Group"** can decrypt and access them. Unauthorized users will only see encrypted versions.

---

## 🎯 Features

- File encryption before uploading to cloud
- Only authorized group members can decrypt files
- Secure **key management system**:
  - Share access securely
  - Add/remove users from the group
- Cross-platform design (CLI and GUI options)
- Uses open-source cryptographic libraries

---

## ⚙️ How to Run

### 1. Setup Google Drive API
- Create API credentials and download `client_secret.json`
- Place the file inside the `src/` directory

### 2. Run CLI Version
```bash
Navigate to:
src/
Run:
main.exe
```

### 3. Run GUI Version
```bash
Navigate to:
src/GUI/
Run:
main.exe
```

---

## 🖼️ UI Preview

![Cloud Encryption UI](https://github.com/sasunts/Cloud-Encryption/blob/master/UI.PNG)

---

## 🧪 Technologies Used

- **Google Drive API**
- **Python + PyInstaller** (for `.exe` generation)
- **Cryptographic Libraries** (e.g., `cryptography`, `PyCrypto`)
- **Tkinter** (GUI version)

---

## 📄 License

This project is developed for academic purposes under CS3031 and is open-source.

---

> 🔐 *"In the cloud, security isn't optional—it's fundamental."*
