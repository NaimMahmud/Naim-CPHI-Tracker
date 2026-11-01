# Build the APK online (no Android Studio required)

This project includes a GitHub Actions workflow at `.github/workflows/build-apk.yml`.

1. Sign in to GitHub in a modern supported browser and create a new **Private** repository.
2. Upload the contents of this ZIP (not the ZIP file itself), keeping the `.github/workflows/build-apk.yml` folder path intact, then commit to the `main` branch.
3. Open the repository's **Actions** tab. Select **Build CPHI Supplier Tracker APK** and click **Run workflow** if it has not started automatically.
4. Wait for the workflow to finish successfully. Open the completed run and download the artifact named **CPHI-Supplier-Tracker-APK**.
5. Extract the downloaded artifact ZIP. It contains `app-debug.apk`. Transfer it to your Android phone and install it. You may need to allow installation from that browser/file manager.

The cloud build requires internet access and a GitHub account. No Android Studio or Android SDK is needed on your Windows 7 PC. If GitHub does not work in your old browser, use a supported browser/device to upload the project.
