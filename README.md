# Daily Recon (Android)

1. Create a new GitHub repository and upload everything in this folder (keep the `.github` folder).
2. Open the **Actions** tab, choose **Build Android APK**, click **Run workflow** (it also runs on every push to `main`).
3. When it finishes (about 5-10 minutes), open the run and download the **daily-recon-debug-apk** artifact. Unzip it to get `app-debug.apk`.
4. Copy the APK to your phone and install it (allow "Install unknown apps" when asked).

The app lives in `www/index.html`. Edit it, push, and the APK rebuilds.
Records are saved on the phone. Share as PDF / CSV opens the Android share sheet.
This is a debug build for your own use; a signed release build is needed for the Play Store.
