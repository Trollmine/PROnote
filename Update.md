# PRONOTE 4.0.0-preview4-fixed

## Preview 4

- Replaced the manual PRONOTE page reader with direct synchronization powered by Pawnote LTS.
- Added one-tap account linking through the school’s normal PRONOTE / ENT sign-in page.
- Automatically detects PRONOTE’s temporary mobile token after login and exchanges it for a renewable session.
- Added the one-time PRONOTE device security-code step when required by the server.
- Kept account QR scanning and direct credentials as collapsed troubleshooting fallbacks.
- Stores the renewable PRONOTE session encrypted with Android Keystore; the password is never retained.
- Added direct timetable synchronization without navigating through official PRONOTE pages.
- Added direct homework synchronization, including completion state and attachments.
- Added previews and overwrite confirmations before manually installing synchronized timetable or homework data.
- Added independent automatic timetable and homework synchronization while the app is running.
- Makes automatically synchronized categories read-only until their automatic synchronization is disabled.
- Routed Pawnote requests through Android networking so required PRONOTE cookies and response headers are preserved.
- Added Android build-code comparison so corrected builds of the same preview are detected by the updater.
- Included the Pawnote LTS GPL licence and attribution in the project.
- Grades remain planned for Preview 5 and messages for Preview 6.

## Fixed build

- Fixed account relinking so every new connection clears the old embedded session and starts through the school’s ENT again.
- Preserved custom homework separately from synchronized PRONOTE homework. Custom entries are hidden while automatic homework sync is enabled and return when it is disabled.
- Converted PRONOTE homework HTML into clean readable text, removing tags such as `<div>` while preserving useful line breaks.
- Made synchronized homework attachments downloadable by tapping their file buttons.
