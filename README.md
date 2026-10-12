# BLACK EXCHANGE — Android APK project

This project wraps the HTML/CSS/JavaScript BLACK EXCHANGE frontend in a basic Android WebView app.

## Build a downloadable APK using GitHub Actions (phone-friendly)
1. Download and extract `BLACK_EXCHANGE_APK_Project.zip`.
2. Create a new GitHub repository.
3. Upload all files and folders from this project into the repository root (including the `.github` folder).
4. Open the repository's **Actions** tab and choose **Build BLACK EXCHANGE APK**.
5. Tap **Run workflow** (or wait for the workflow to run after pushing files).
6. When the workflow finishes successfully, open that workflow run, scroll to **Artifacts**, and download `BLACK-EXCHANGE-APK`.
7. Extract the downloaded artifact ZIP to get `app-debug.apk`, then open it on your Android phone to install. Android may ask you to allow installs from that browser/file manager.

## Important
- This is a buildable Android APK project, but the APK must be compiled by GitHub Actions; this environment has not compiled or tested the APK.
- The current app is a frontend prototype. Deposits and withdrawals only create local pending requests; they do not move real money. Do not collect or process real funds until a secure backend and official payment-provider API integrations are implemented.
- The displayed football fixtures/odds are sample UI, not live data.
