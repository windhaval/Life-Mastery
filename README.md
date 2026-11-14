# Life Mastery

Offline app: daily planner, motivational quote of the day, habit tracker with streaks, goals with milestones, Pomodoro focus timer and time stats. All data stays on your device (localStorage).

## Folders
- `web/` – the app (index.html, manifest, service worker, icon)
- `android/` – Android Studio / Gradle project that wraps the app in a WebView
- `.github/workflows/build-apk.yml` – builds the APK automatically on GitHub

## Get the APK (pick one)
1. **GitHub (no installs):** upload this folder to a new GitHub repo → Actions → "Build APK" → download `LifeMastery-apk` → install `app-debug.apk`.
2. **Android Studio:** open the `android/` folder → Build → Build APK(s). Output: `android/app/build/outputs/apk/debug/app-debug.apk`.
3. **Command line:** `cd android && gradle assembleDebug` (needs JDK 17 + Android SDK).

## Install without an APK (instant)
Host `web/` on any HTTPS site (GitHub Pages, Netlify) → open in Chrome on Android → menu → "Install app".
