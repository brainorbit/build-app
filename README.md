# StudyVault (standalone WebView app)

Loads https://studyvault.alwaysdata.net/welcome in its own WebView.
Login/cookies/localStorage live in THIS app's storage, not Chrome's.

## Build option A: Android Studio
Open this folder, let it sync, then Build > Build APK(s).
Output: app/build/outputs/apk/debug/app-debug.apk

## Build option B: GitHub (no PC needed)
1. Create a GitHub repo and upload everything in this folder.
2. Actions tab > "Build APK" > Run workflow.
3. Download the "StudyVault-apk" artifact (zip), extract, install app-debug.apk.

Note: uninstall the old Chrome WebAPK "StudyVault" first (different package).
