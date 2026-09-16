# PRONOTE 4.2.0

## 4.2.0 — Self

- Added **Self** to Secret Tools with Monday–Friday cafeteria menus from the linked PRONOTE/ENT session.
- Added week navigation, separate lunch/dinner sections and offline cafeteria-menu storage.
- Cafeteria synchronization checks every eligible student resource instead of depending on the resource active after login.
- Rebuilt Communication installation as an explicit, verified cache transaction.
- Information & Surveys are deduplicated, tracked explicitly and read back from storage; the app no longer reports success if detected items were not actually saved.
- If long discussion histories approach Android WebView’s storage limit, older message bodies are compacted before retrying so Information & Surveys still import successfully.
- Reset the Information & Surveys unread-only filter after an import so newly installed read items remain visible.
- Homework synchronization now removes the previous PRONOTE layer before importing the current remote list.
- Migrates and removes legacy synchronized homework entries that lacked a source marker, preventing repeated imports from creating duplicates.
- Preserves genuinely custom homework while deduplicating the new PRONOTE set by its remote identifier.
- Updated Android to version **4.2.0**, `versionCode 56`.
- Replaced the Notebook’s placeholder missed-hours and tardiness symbols with the supplied PRONOTE-style clock and running-student icons.

## 4.1.0 — Student Administration

- Added direct Student Administration synchronization through the linked PRONOTE session.
- Added independent one-time and automatic synchronization controls for Student Administration.
- Added the real PRONOTE-style Notebook overview and detail pages for absences, tardiness, punishments, observations and precautionary measures.
- Added justified-state, reason, duration, subject and date details when supplied by the school.
- Added downloadable documents attached to punishments and precautionary measures.
- Added Student Administration to **Sync all once**, last-sync reporting and the animated drawer navigation.
- Completed the English and French interface for the new pages.
- Rebuilt the notification panel to match the supplied full-height PRONOTE overlay instead of the incorrect compressed bottom sheet.
- Fixed Communication synchronization so Information & Surveys establishes presence, checks every eligible student resource, and retries false empty responses before discussion threads are downloaded.
- Enabling any automatic synchronization switch now performs its first synchronization immediately instead of waiting for a later app launch or timer.
- Updated the Android release to version **4.1.0**, `versionCode 55`.

## 4.0.0 Stable

- Rebuilt Communication to closely match the supplied PRONOTE recording.
- Added the complete Communication navigation: Discussions, Information & Surveys, My meetings, Agenda and Menu.
- Added discussion search, unread and open/closed filters, offline thread access and downloadable attachments.
- Added recipient lookup and new-discussion sending to teachers and other authorized school personnel.
- Added synchronized Information & Surveys with search, unread state, detail pages and attachments.
- Added the school-holiday Agenda and synchronized cafeteria menus.
- Added the PRONOTE-style notification panel and empty states.
- Rebuilt Discussions and Information & Surveys to closely follow the real PRONOTE mobile list and thread layouts.
- Removed the unwanted 20:00–07:00 message-reception banner from every Communication page.
- Replaced the fixed notification number with the real combined unread Communication count.
- Opening a discussion or information item now marks it read locally and on PRONOTE.
- Strengthened offline mode: the first key activation still requires internet, but a previously verified installation can subsequently open offline.
- Added automatic key revalidation on connected launches and whenever connectivity returns.
- Finished and polished the English/French translations across synchronization, grades and Communication.
- Kept synchronized categories read-only while their automatic synchronization is enabled.
- Released the final Android V4 build as version **4.0.0**, `versionCode 51`.

## Preview 6

- Added real PRONOTE message synchronization.
- Added the first functional Communication page and its drawer navigation.
- Added synchronized teacher discussions, message threads, dates and unread states.
- Added offline caching for previously synchronized conversations.
- Added support for viewing and downloading files attached to messages.
- Added the animated drawer expansion used by sections such as Homework notebooks and Communication.

## Preview 5

- Added real PRONOTE grade synchronization.
- Added a complete Grades area with My grades, Gradebook, Report card, Class's report card and Old report cards.
- Added grading periods, subject averages, class averages, marks, coefficients and comments.
- Added downloadable assessment and correction files when supplied by PRONOTE.
- Reworked the grade pages to match the supplied mobile PRONOTE references.
- Added the PRONOTE-style period menu, which remains accessible even when periods contain no grades.
- Added the supplied school-box illustration and polished empty-period screens.

## Preview 4

- Added real PRONOTE homework synchronization.
- Added independent one-time and automatic homework synchronization settings.
- Synchronized subjects, due dates, completion state, instructions and downloadable homework files.
- Normalized PRONOTE HTML homework text so tags such as `<div>` no longer appear in assignments.
- Added direct attachment downloading from synchronized homework.
- Automatic homework synchronization now hides the built-in demonstration homework and restores it when synchronization is disabled.
- Improved account linking through the school's normal PRONOTE/ENT sign-in flow.
- Fixed relinking so logging out and linking again restarts the ENT login instead of falling back to an unwanted PRONOTE login page.
- Stored renewable PRONOTE sessions securely using Android Keystore without saving the account password.

## Preview 3

- Added automatic timetable synchronization using Android background work.
- Added an independent timetable auto-sync switch, disabled by default.
- Added periodic refreshes while preserving the last successfully synchronized timetable for offline use.
- Made synchronized timetable data read-only while automatic synchronization is enabled.
- Added account-session renewal for background synchronization.

## Preview 2

- Added one-time timetable synchronization from a linked PRONOTE account.
- Synchronized courses, teachers, rooms, groups, cancellations and exceptional timetable changes.
- Added a timetable preview and overwrite warning before installing synchronized data.
- Added automatic Lunch and No course gaps while ensuring Wednesday never receives an artificial lunch period.
- Added gray styling for classes that already happened on the current day.
- Kept PDF import and timetable QR transfer available as optional alternatives.

## Preview 1

- Added the Synchronization section to the secret settings tab.
- Added optional PRONOTE account linking; the app remains fully usable without a real PRONOTE account.
- Added the foundation for direct synchronization using Pawnote LTS as an independent connector without copying Papillon application code.
- Added separate one-time and automatic switches for timetable, homework, grades and Communication, all disabled by default.
- Added overwrite warnings explaining that synchronized categories replace their custom equivalents.
- Added encrypted renewable-session storage and account unlinking controls.
- Added the first synchronization status, last-update and error displays.
