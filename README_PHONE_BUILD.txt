POCKET BDT — ANDROID APK BUILD PACKAGE

This is an Android application project, not the APK itself. It wraps the Pocket BDT expense tracker in a real Android WebView app, with local offline assets, persistent app-local browser storage, JSON/CSV export to Downloads, and JSON restore through the Android file picker.

PHONE-ONLY BUILD VIA GITHUB ACTIONS
1. Download and extract this ZIP on your phone (or keep the ZIP for upload).
2. Sign in/create an account at https://github.com/ .
3. Create a new repository named pocket-bdt-android. For personal financial data, keep the repository PRIVATE.
4. Upload the extracted PROJECT FILES and FOLDERS (not the enclosing pocket_bdt_android folder) to the repository. Ensure .github/workflows/build-apk.yml is included. GitHub's web upload may be easier from Chrome's Desktop site mode.
5. Open the repository's Actions tab and select “Build Pocket BDT APK”. Tap “Run workflow”. If Actions are disabled, enable them for this repository.
6. When the run completes successfully, open the run and download the artifact named “Pocket-BDT-Android-APK”. GitHub may download it as a ZIP. Extract it to get app-debug.apk.
7. Tap app-debug.apk and allow Chrome/Files to install unknown apps if Android asks. Review the install prompt and install.

NOTES
- This creates a debug APK for personal use; it is not Play Store signed/release-ready.
- The repository contains app source, not your transaction records. Do not commit personal backup JSON files.
- App records are stored locally on this phone inside the app's WebView storage. Uninstalling the app or clearing its data can erase records. Use Reports > Download JSON backup regularly.
- Keep the GitHub repository private. Do not upload your expense backup there.
