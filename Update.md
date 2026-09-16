# PRONOTE 4.0.0 — Complete release notes

## Stable

- Rebuilt Communication to closely match the supplied PRONOTE recording.
- Added the complete Communication navigation: Discussions, Information & Surveys, My meetings, Agenda and Menu.
- Added discussion search, unread and open/closed filters, offline thread access and downloadable attachments.
- Added recipient lookup and new-discussion sending to teachers and other authorized school personnel.
- Added synchronized Information & Surveys with search, unread state, detail pages and attachments.
- Added the school-holiday Agenda and synchronized cafeteria menus.
- Added the PRONOTE-style notification panel and empty states.
- Rebuilt Discussions and Information & Surveys to closely follow the real PRONOTE mobile list and thread layouts.
- Fixed Information & Surveys synchronization so failures are retried and reported instead of silently producing an empty list.
- Removed the unwanted 20:00–07:00 message-reception banner from every Communication page.
- Replaced the fixed notification number with the real combined unread Communication count.
- Opening a discussion or information item now marks it read locally and on PRONOTE.
- Strengthened offline mode: the first key activation still requires internet, but a previously verified installation can subsequently open offline.
- Added automatic key revalidation on connected launches and whenever connectivity returns.
- Finished and polished the English/French translations across synchronization, grades and Communication.
- Kept synchronized categories read-only while their automatic synchronization is enabled.
- Updated the final Android release to version **4.0.0**, `versionCode 52`.

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
