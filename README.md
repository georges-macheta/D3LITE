# 📱 D3Lite App

D3Lite is a Flutter-based mobile application designed to calculate your Vitamin D3 intake from the sun. Built with Flutter and Dart, the app supports Android, iOS, and web platforms (Chrome).

---

## 🚀 Features

- Cross-platform (Android, iOS, Web, Desktop)
- Built with Flutter 3.7.1 and Dart 2.19.1
- [Add specific features of the app here once finalized]

---

## 🛠️ How to Run the Project (Windows)

> These are the exact steps tested and confirmed on a Windows machine using Visual Studio Code.

### ✅ Step 1: Install Required Tools

1. **Install Flutter SDK**
   - Download and extract [Flutter SDK 3.7.1](https://storage.googleapis.com/flutter_infra_release/releases/stable/windows/flutter_windows_3.7.1-stable.zip)
   - Extract to: `C:\src\flutter` (recommended)

2. **Add Flutter to PATH**
   Open PowerShell and run:
   ```powershell
   [Environment]::SetEnvironmentVariable("Path", $env:Path + ";C:\src\flutter\bin", [System.EnvironmentVariableTarget]::User)
   ```
   Then close and reopen your terminal.

3. **Install Git** (if not already installed)
   ```bash
   git --version
   ```

4. **Install Android Studio and an emulator**, or connect a real Android device with USB debugging enabled.

5. **Install VS Code** (with Flutter and Dart extensions)

---

### ✅ Step 2: Verify Flutter Installation

```bash
flutter doctor
```

Ensure all checks are ✅ (no red Xs). Fix anything the doctor complains about before continuing.

---

### ✅ Step 3: Run the Project

In VS Code terminal:

```bash
cd C:\Users\asus\Downloads\d3lite_app-master
flutter pub get
flutter run
```

This will launch the app on your connected emulator or device.

---


