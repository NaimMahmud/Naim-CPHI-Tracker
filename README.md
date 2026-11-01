# CPHI Supplier Tracker (Android project)

Offline-first Android app for recording pharmaceutical API suppliers during CPHI visits.

## Included
- Supplier create, edit, delete and search
- Company/contact, manufacturing, regulatory, API, commercial and follow-up fields
- High / Medium / Low priority filters
- Optional business-card / certificate attachments (images and PDFs)
- CSV export (opens in Excel)
- JSON backup and restore
- Local device storage; no account or internet connection required for normal use

## Build APK with Android Studio
This environment does not include the Android SDK or Gradle, so a compiled APK is not included.
1. Install Android Studio on a computer.
2. Open this folder as an existing Android Studio project.
3. Allow Android Studio to install the required Android SDK (compile SDK 35) and Gradle plugin.
4. Select **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. Android Studio will show the generated APK location, usually `app/build/outputs/apk/debug/app-debug.apk`.
6. Transfer the APK to your Android phone and install it. You may need to allow installation from that file manager.

## Data and privacy
Supplier records are saved in WebView local storage on the phone. They are not synchronized to a cloud account. Export a CSV for spreadsheet use and make JSON backups regularly. Uninstalling the app or clearing its app data can erase records. Large attachments may use substantial device storage.

## Package details
- App name: CPHI Supplier Tracker
- Application ID: com.gentry.cphisuppliertracker
- Minimum Android: Android 6.0 (API 23)
- Version: 1.0
