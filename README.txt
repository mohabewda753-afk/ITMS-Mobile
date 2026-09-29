ITMS Mobile PWA v0.9 - Apps Script Gateway / Name + HR

Gateway URL embedded:
https://script.google.com/macros/s/AKfycbzu6KY8w7_EtwulReU2SGYPL6tZQQc7OW9Qo0B23kKA-umdPPohc6BIrKLrar-3RsM-/exec

Changes from v0.8:
- Removed Google OAuth and Drive folder configuration from lecturer UI.
- Added lecturer Name + HR / staff number sign-in.
- Login is validated by the Apps Script gateway.
- Lecturer package is downloaded only after successful gateway authentication.
- Attendance uploads through the gateway into Attendance-Inbox.
- Smart sync retained: only new/changed records are uploaded.
- Synced records remain stored locally.
- Changed attendance becomes pending again.
- Cached timetable/registers and attendance remain available offline.
- Manual JSON import was removed from the lecturer UI.

GitHub Pages update:
Replace the existing index.html and manifest.webmanifest in the ITMS-Mobile repository with these two files, commit, and wait for GitHub Pages to refresh.
