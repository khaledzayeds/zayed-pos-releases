# Zayed POS releases

Public binary distribution. Application source is private.

Version: 2.1.4 (build 2104), built 2026-09-26.

Each platform has an independent release tag and manifest for Zayed X.

- android: [Zayed-Android-2.1.4-2104.apk](https://github.com/khaledzayeds/zayed-pos-releases/releases/download/android-v2.1.4/Zayed-Android-2.1.4-2104.apk), manifest: [android.json](android.json)
- windows: [Zayed-Windows-2.1.4-2104.zip](https://github.com/khaledzayeds/zayed-pos-releases/releases/download/windows-v2.1.4/Zayed-Windows-2.1.4-2104.zip), manifest: [windows.json](windows.json)

Windows: extract the complete ZIP, then run Zayed.exe; keep data and DLL files together.

Android: this existing APK uses the Android Debug signing certificate. It is the previously delivered build; no new signing or rebuild was performed.

Source tests: 71 passed on 2026-10-20. Physical phone, two-device sync, and printer acceptance tests are not established by this upload.

