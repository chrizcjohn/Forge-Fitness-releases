# Forge Fitness releases

Public Android APK downloads for Forge Fitness. The application source is maintained in a separate private repository.

## Install

Open [Releases](https://github.com/chrizcjohn/Forge-Fitness-releases/releases/latest), download the `Forge-vX.Y.Z.apk` asset, and approve Android's installer. Install over your existing Forge app to retain workout history and settings. Do not uninstall first.

## Updates inside Forge

Starting with version 1.1.0, Forge checks this public repository when you open or return to the app, at most once every six hours. No GitHub login or access token is needed. A small notice appears when a newer stable version is available; you can continue your workout and update later.

You can also open **Settings → App updates** to check manually or turn automatic checks off. Choose **Download update** and confirm the download. Forge shows progress and lets you cancel. It verifies the SHA-256 checksum, APK size, package name, newer Android version code, version name, and signing certificate before installation.

Once the download is verified, choose **Install update**. If Android asks, allow installations from Forge, return to Forge, and tap **Install update** again. Approve the Android installer to finish. Save your active workout before installing. Installation always needs your approval.

Existing versions need a one-time manual installation of 1.1.0 or later to gain this updater. Future updates must use the same package ID and signing key.

Only stable releases with a universal `Forge-vX.Y.Z.apk` asset are offered in the app. Older releases remain available here.

## Try sample workouts

From version 1.3.8, open **You → Test the app → Load sample workouts** to practice with dummy journal entries, charts and an unfinished workout. Sample edits save locally. **Reset sample workouts** reloads fresh examples, and **Exit sample data** restores your original history, preferences, exercise lists and unfinished session. Cloud sync and account actions pause while samples are loaded.
