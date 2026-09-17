# Emotica Android

Emotica is on Google Play: [play.google.com/store/apps/details?id=com.emotica.android](https://play.google.com/store/apps/details?id=com.emotica.android). Installing from Play is the easiest way to get updates.

[Download Emotica 1.0-beta.10](https://github.com/tirupati17/emotica-site/releases/download/android-1.0-beta.10/emotica-android-1.0-beta.10.apk) for Android 8.0 or later, if you would rather install the APK directly.

Keeps the Health Connect explanation screen clear of the status and navigation bars on Android 15 and later, where it could sit underneath them.

Every screen now speaks the language you pick. Controls, player and exercise sheets, journal tools, widgets, empty states, error messages and screen-reader labels were still English in places; all 17 languages now cover the full interface. Exercise catalogue titles and spoken audio remain English.

Fixes blank text in German, Hindi and Russian, where the entry save error, the empty search state, the delete confirmation and the share error showed nothing at all. Sharing a journal entry with a friend is hidden while that feature is still in progress.

Keeps Settings feedback, shake-to-report with a reviewable screenshot, report status and feature voting, encrypted backup restore after a deletion, and iOS-compatible ZIP backups. Existing users can open Settings, then Replay introduction.

Android may ask you to allow installation from your browser when using the direct APK.

The installer is hosted as a GitHub release asset, keeping the 32MB APK out of Pages build artifacts.

- Package: `com.emotica.android`
- Version: 1.0-beta.10 (version code 11)
- Target SDK: Android 16 / API 36; Play Billing Library 8.0.0
- APK SHA-256: `12d0f2b9592db34e5e0635abcc84c87e73b1f268b2e769f0ff762cfcabb19ad0`
- Signing certificate SHA-256: `982b545d37dcdc102245250837b42f1312fcb3a86781d9c5b892657f98d7096b`

The signing certificate is unchanged from beta.1, so an existing public beta install updates in place. A debug install cannot be updated by it; the keys differ.
