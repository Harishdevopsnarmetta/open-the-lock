OPEN THE LOCK — Version 1.0

FILES
- index.html: complete responsive app (HTML, CSS, JavaScript)
- manifest.webmanifest: PWA install metadata
- sw.js: basic offline app-shell caching
- icon.svg: app icon

RUN
1. Open index.html in a supported browser for a quick test.
2. For microphone access and PWA installation, serve this folder over HTTPS (or localhost).
3. On Android, open the HTTPS URL in Chrome, grant microphone permission, and tap Start listening.
4. Use Settings to change phrase/language/sensitivity.

IMPORTANT LIMITATIONS
- Browser speech recognition availability depends on browser/device and may use an online speech service.
- This app only listens while its page is active and supported by the browser. It cannot listen while the phone is locked, after the browser is closed, or reliably in the background.
- A browser/PWA cannot wake or open Android's real secure lock screen. The matched phrase shows an in-app demo lock-screen preview only.
- It does not unlock the device or bypass PIN, password, fingerprint, or face authentication.
- For the original always-on, screen-off behavior, build a native Android app using a permitted foreground microphone service and test Android/OEM restrictions.
