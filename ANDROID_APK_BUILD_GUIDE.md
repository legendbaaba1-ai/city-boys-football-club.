# CITY BOYS FOOTBALL CLUB — Android APK build

This project packages the existing CITY BOYS React/Firebase app as an installable Android APK using Capacitor. It is a hybrid Android app with bundled web UI, not a website shortcut/PWA.

## Build using a phone only
1. Extract this ZIP on your phone.
2. Open https://github.com and sign in/create your account.
3. Create a new repository named `city-boys-football-club` (Public or Private).
4. Upload the CONTENTS of the `cityboys_work` folder to the repository root (including hidden `.github` folder and its workflow file). GitHub's mobile website may hide dotfolders; use the browser's Desktop site option if needed.
5. Open the repository → Actions. If asked, enable workflows.
6. Choose `Build CITY BOYS Android APK` → Run workflow.
7. Wait for the workflow to finish. Open the completed run, scroll to Artifacts, and download `CITY-BOYS-FOOTBALL-CLUB-APK`.
8. Extract the downloaded artifact ZIP and install `app-debug.apk`. Android may ask you to allow installation from that browser/files app.

## Notes
- This creates a debug APK for testing and direct installation. A Play Store release needs a signed release build and Play Console setup.
- Firebase Auth/Firestore/Storage still require correct Firebase console configuration and security rules.
- Never upload Firebase service-account JSON, passwords, or private signing keys.
