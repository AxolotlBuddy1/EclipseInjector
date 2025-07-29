# Eclipse Injector

## Overview
Eclipse Injector is a prebuilt C++ project designed for advanced DLL injection into Windows processes. It supports multiple injection methods and advanced stealth options to maximize flexibility and detection avoidance.

This project is a **solo project** and has **no collaborations or external contributions**.

## Features
- Fully prebuilt executable (no compilation needed for usage).
- Supports x64 processes on Windows.
- Multiple injection methods:
  - **Standard LoadLibrary Injection**
  - **Manual Map Injection**
  - **Thread Hijacking**
  - **LdrLoadLibrary Injection**
  - **LdrpLoadLibrary Injection** *(stub implementation)*

## Usage
1. Launch `EclipseInjector.exe`.
2. **Select Target PID** (Process ID).
3. **Select Path of the DLL File**.
4. **Choose Injection Method**:
    - **Standard Injection**
    - **Manual Map**
    - **Thread Hijacking**
    - **LdrLoadLibrary**
    - **LdrpLoadLibrary (stub)**
5. **Select Advanced Options**:
    - Enable Stealth Unlink  
    - Erase PE Header  
    - Close Injector After Inject  
    - Delay Injection  
6. **Click Inject → Injection Process Complete!**

### Requirements
- Windows 10 or newer.
- Administrator privileges for protected processes.

## Disclaimer
This software is provided for **educational purposes only**. Misuse for cheating, piracy, or malicious activities is strictly discouraged and is the user's sole responsibility.

## License
This project uses a custom **No-Modification Redistribution License (NMRL)**:

- Redistribution of the original binary is allowed.
- Redistribution or modification of the source code is strictly prohibited.
- No external contributions are accepted.

See [LICENSE](./LICENSE) for full terms.
