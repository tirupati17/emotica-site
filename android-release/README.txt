EMOTICA — ANDROID STORE RESOURCES
App version: 1.0.8 / version code 20
Screenshots: English, Hindi, German and Russian 1.0.8 release UI (stored in the 1.0-beta.6 folder for stable URLs).

Open index.html to preview the English, Hindi, German and Russian resources offline.
The page also lives at https://emotica.me/android-release/

Each language folder contains:
- feature-graphic.png: 1024 x 500, 24-bit PNG without transparency
- 01 through 07 screenshots: 1080 x 1920, 24-bit PNG without transparency
- Screens: Mental Sky, onboarding feeling, exercises, exercise cards, journal, emotion log, audio player
- title.txt, short-description.txt, full-description.txt, release-notes.txt
- metadata.json: all text and accessibility alt text

Upload graphics and text to their matching English/Hindi/German/Russian Google Play listings.
The PNG compositions use actual Android release screenshots and demonstration
entries with Android system font scale 1.3, captured at 1080 x 2424 / 360 dpi
(Russian onboarding: 340 dpi to fit longer labels).
The Pixel 9-style frames preserve the screen ratio, with larger close-up framing.
The bottom edge of the handset extends beyond the poster. The feature graphics use a
white background and five filled emotion clouds with symbols, labels and dots.
The app icon appears on every poster and feature graphic. The phone
posters use solid emotion-palette backgrounds. There are no store badges,
ratings, pricing or download claims. Existing artwork inside the app is retained.

The interface supports 17 languages. Catalogue titles and spoken audio may use
a different language. The descriptions state that distinction.

Image requirements:
https://support.google.com/googleplay/android-developer/answer/9866151?hl=en-GB
Text limits:
https://support.google.com/googleplay/android-developer/answer/9859152

Font licenses are included in fonts/. Lexend, Noto Sans and Noto Sans Devanagari use the
SIL Open Font License. The graphics can be regenerated from release captures with
scripts/render-android-store-pack.cjs in the landing-page repository; then run
scripts/package-android-store-pack.py to check sizes and produce the ZIPs.

The signed APK is available from the main Emotica website. The matching AAB is
provided separately on Desktop. Build 20 is published to Google Play production.

For terminal listing uploads, run scripts/export-play-listings.py with a new
output directory. It prepares Fastlane metadata and upload.sh for all four
languages. Credentials are supplied separately and are never included in this kit.
