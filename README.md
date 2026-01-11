Local User Password Manager (LUPM) v1.2 - 2026
             
**LUPM** is an advanced administrative utility designed for the secure management of local user account passwords on Windows systems. 
Built for **Full Portable** operation from USB media, it ensures data integrity and operational confidentiality through military-grade encryption.


## 🚀 Key Features
- **Zero-Footprint:** No traces left on the host PC; temporary files are wiped upon exit.
- **USB Integrity:** *Atomic Buffering* system prevents file corruption during abrupt USB removal.
- **AES-256 Encryption:** Logs and databases are protected via the 7-Zip engine.
- **Advanced Generator:** Passwords compliant with 2026 security standards (guaranteed entropy with random shuffling).
- **Multilingual:** Native support for English, Italian, German, French, Spanish, and Portuguese.
- (NEW in v1.1) Group Management: Assign or revoke local group memberships for any user account, with full validation and safety checks.

🆕 What’s New in Version 1.1
Local Group Assignment & Revocation:  
Administrators can now add or remove users from local groups directly from the interface.
The system validates group existence, membership status, and prevents inconsistent states.

Extended Logging System:  
All group‑related operations (assignments, removals) are now included in the encrypted log archive, 
ensuring complete traceability with the same AES‑256 protection used for password operations.

🆕 What’s New in Version 1.2
-Multi‑log export support
-Improved group‑change logging (added/removed/final groups)
-Stronger archive password policy (minimum 14 chars, full complexity)
-Refined UI and workflow improvements
-Bug fixes and internal optimizations
-For full details, see the dedicated changelog.

## 🛠 Dependencies & Compilation
The project relies on the following third-party tools:
- **[7-Zip](https://github.com/ip7z/7zip):** Used as the core compression and encryption engine (binaries are embedded in Base64 format).
- **[Win-PS2EXE](https://github.com/MScholtes/Win-PS2EXE):** Used to compile the `.ps1` script into a standalone `.exe` file.

## 🛡 Security & Synchronization Logic
To maximize USB flash memory lifespan and prevent data corruption:
1. The script **does not synchronize** logs during an active session.
2. Merging into the main archive occurs automatically upon **application restart**.
3. The **Sync** button is provided for exceptional needs only and should not be used as a standard exit procedure.
4. **Safe Removal:** Always exit using the "Close" button and use Windows "Safely Remove Hardware" before unplugging the drive.

## 👥 Credits & Collaboration
- **Lead Developer:** M.Giuliano
- **Code Reviewer & Bugfixing:** **[nothing7209](https://github.com/nothing7209):** – Special thanks for the comprehensive code review and security logic optimization.

## ⚖️ License
This project is licensed under the **GPL-3.0 License**. See the `LICENSE` file for details.

---
*Note: Administrator privileges are required to modify system passwords.*
