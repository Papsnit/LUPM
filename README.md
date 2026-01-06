             Local User Password Manager (LUPM) v1.0 - 2026
             
**LUPM** is an advanced administrative utility designed for the secure management of local user account passwords on Windows systems. 
Built for **Full Portable** operation from USB media, it ensures data integrity and operational confidentiality through military-grade encryption.
Features AES-256 encrypted atomic buffering to prevent data corruption on USB drives. 
Includes a high-entropy password generator and persistent encrypted logging.

## 🚀 Key Features
- **Zero-Footprint:** No traces left on the host PC; temporary files are wiped upon exit.
- **USB Integrity:** *Atomic Buffering* system prevents file corruption during abrupt USB removal.
- **AES-256 Encryption:** Logs and databases are protected via the 7-Zip engine.
- **Advanced Generator:** Passwords compliant with 2026 security standards (guaranteed entropy with random shuffling).
- **Multilingual:** Native support for English, Italian, German, French, Spanish, and Portuguese.

## 📂 Repository Content
- `LUMP.ps1`: The original PowerShell source script.
- `LUPM-Portable.exe`: Compiled executable version, ready for portable use.
- `7z.exe.b64` / `7z.dll.b64`: 7-Zip binaries encoded in Base64 (used for self-extraction).
- `archive.ico`: Official project icon.

## 🛠 Dependencies & Compilation
The project relies on the following third-party tools:
- **[7-Zip](www.7-zip.org):** Used as the core compression and encryption engine (binaries are embedded in Base64 format).
- **[Win-PS2EXE](github.com):** Used to compile the `.ps1` script into a standalone `.exe` file.

## 🛡 Security & Synchronization Logic
To maximize USB flash memory lifespan and prevent data corruption:
1. The script **does not synchronize** logs during an active session.
2. Merging into the main archive occurs automatically upon **application restart**.
3. The **Sync** button is provided for exceptional needs only and should not be used as a standard exit procedure.
4. **Safe Removal:** Always exit using the "Close" button and use Windows "Safely Remove Hardware" before unplugging the drive.

## 👥 Credits & Collaboration
- **Lead Developer:** M.Jiuliano
- **Code Reviewer & Bugfixing:** [nothing7209](github.com) – Special thanks for the comprehensive code review and security logic optimization.

## ⚖️ License
This project is licensed under the **GPL-3.0 License**. See the `LICENSE` file for details.

---
*Note: Administrator privileges are required to modify system passwords.*
