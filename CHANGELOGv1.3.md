# 📄 CHANGELOG

## v1.3.0 – Sync Button Safety & UX Improvements

### Added
- Introduced a new **two‑step confirmation system** for the *Sync Logs* button  
  - First click arms the button  
  - Second click executes the sync  
- Implemented a **5‑second automatic timeout** that resets the button if the user does not confirm in time  
- Added clear **visual state indicators**:  
  - **Red** = Locked  
  - **Green** = Ready to sync  

### Improved
- Enhanced user experience by removing modal confirmation dialogs  
- Reduced accidental sync operations through a more intuitive and visual confirmation flow  
- Refined event handling and timer logic for better reliability and maintainability  

### Stability
- Improved error handling to ensure the Sync button always resets correctly after interruptions  
- Resolved conditions that could cause inconsistent UI states when the sync process is cancelled or fails  
