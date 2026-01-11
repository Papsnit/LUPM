🚀 New Features
Multi‑log export support  
Added the Export Selected feature, allowing users to select and export multiple log files at once.
Enhanced group‑management logging  
Group changes now generate detailed logs including:
Added groups
Removed groups
Final group membership
Improved password‑change logging  
Password logs now use the _Pswrds_ suffix for clearer identification.
Better log viewer experience  
The log selection window now supports double‑click actions and improved navigation.

🔐 Security Improvements
Stronger archive password policy  
Minimum length increased to 14 characters, requiring:
Uppercase letters
Lowercase letters
Digits
Symbols
Improved validation of archive password  
More robust checks when opening or rebuilding the encrypted 7z archive.
Safer session buffer handling  
Enhanced integrity checks before merging logs into the main archive.

🛠 Functional Enhancements
Improved group manager window  
Minimum window size added for better usability.
Automatic user list refresh  
The user list updates immediately after group modifications.
Cleaner log naming structure  
Log files now follow a more consistent and descriptive naming pattern.
Better UI clarity  
Updated labels, buttons, and messages for a more intuitive experience.

🧹 Bug Fixes
Fixed a typo in password generation (Get-RRandom → Get-Random).
Corrected session buffer handling during log synchronization.
Fixed missing or incorrect notes in group‑change logs.
Resolved issues with error messages not displaying correctly.
Improved handling of empty or missing log archives.

📦 Miscellaneous Updates
Updated version number in the About window to 1.2.
Improved internal code structure and consistency.
Enhanced readability and maintainability of the script
