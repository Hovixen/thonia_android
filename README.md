# Recon Desk (Android APK)

## Get the APK (no Android Studio needed)
1. Create a free account at github.com and make a new repository (private is fine).
2. Upload everything in this folder to it (drag and drop on the "Add file > Upload files" page; keep the .github folder).
3. Open the repository's **Actions** tab > **Build APK** > wait about 5-8 minutes for the green tick.
   (If it does not start by itself: Build APK > Run workflow.)
4. Open the finished run, download **ReconDesk-apk** at the bottom, unzip it to get app-debug.apk.
5. Send the file to your phone, tap it, and allow "Install unknown apps" when asked.

## First use
Open the app > "API key" > paste your Anthropic API key (console.anthropic.com). Reading a screenshot needs internet; typing figures and the calculations work offline.

## Edit the app
All the app code is in www/index.html. After editing, push again and a new APK is built.
