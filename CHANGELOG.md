# 📜 Changelog

## **v1.1 – 2026**
### **Added**
- **Local Group Management**
  - Ability to assign or revoke membership in local groups for any user.
  - Automatic validation of group existence and current membership status.
- **Extended Logging**
  - All group‑related operations (add, remove, errors, confirmations) are now recorded inside the encrypted logs.
  - Improved internal log structure for better traceability.

### **Improved**
- Optimized internal operation handling to reduce the number of write cycles on USB storage.
- Increased stability of the synchronization process in case of unexpected restarts.

### **Fixed**
- Corrected an edge case where password generation could fail to respect the randomization order under heavy load.
- Fixed a minor issue in the German localization.

---

## **v1.0 – 2026**
### **Initial Release**
- Local password management.
- Advanced password generator compliant with 2026 standards.
- AES‑256 encrypted logs using the 7‑Zip engine.
- Full‑portable mode with *Atomic Buffering*.
- Multilingual support.
