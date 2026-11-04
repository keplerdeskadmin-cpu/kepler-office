# Kepler Office — Android App

Free office suite: Kepler Write, Kepler Sheets, Kepler Slides.

## Build the APK (free, on GitHub)
1. Upload this whole folder to a new GitHub repository.
2. Open the **Actions** tab — the "Build Kepler Office APK" workflow runs automatically (or press **Run workflow**).
3. When it finishes (green tick), open the run and download **KeplerOffice-APK** from *Artifacts*. Unzip it to get `KeplerOffice.apk`.

## Update the app
Replace `app/src/main/assets/index.html` with the new version and bump `versionCode` / `versionName` in `app/build.gradle`.
