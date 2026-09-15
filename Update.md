# PRONOTE 4.0.0-preview6

## Preview 4 foundation

- Replaced the manual PRONOTE page reader with direct synchronization powered by Pawnote LTS.
- Added one-tap account linking through the school’s normal PRONOTE / ENT sign-in page.
- Automatically detects PRONOTE’s temporary mobile token after login and exchanges it for a renewable session.
- Added the one-time PRONOTE device security-code step when required by the server.
- Kept account QR scanning and direct credentials as collapsed troubleshooting fallbacks.
- Stores the renewable PRONOTE session encrypted with Android Keystore; the password is never retained.
- Added direct timetable and homework synchronization without navigating through official PRONOTE pages.
- Added previews and overwrite confirmations before manually installing synchronized data.
- Added independent automatic synchronization and read-only protection for synchronized categories.
- Preserved custom homework while automatic synchronization temporarily hides it.
- Cleans HTML from homework descriptions and makes synchronized attachments downloadable.
- Makes every relink clear the old embedded session and restart through the school ENT.
- Routed Pawnote requests through Android networking so required cookies and response headers are preserved.
- Added Android build-code comparison so corrected builds of the same preview are detected by the updater.
- Included the Pawnote LTS GPL licence and attribution in the project.

## Preview 5

- Added direct grade synchronization for every grading period available on the linked PRONOTE account.
- Added independent **Sync once** and **Auto sync** controls for grades.
- Added a grade preview and confirmation step before manually replacing synchronized grade data.
- Added a real **Grades** page accessible from the side menu.
- Added offline storage and a grading-period selector for synchronized results.
- Displays the student’s overall average and the class average when PRONOTE provides them.
- Displays subject averages together with class, lowest and highest averages.
- Displays individual marks, special statuses, coefficients, dates and teacher comments.
- Makes assessment subjects and correction files downloadable when supplied by PRONOTE.
- Keeps grade data read-only while automatic grade synchronization is enabled.

## Preview 5 interface fix

- Rebuilt the Grades drawer section to match PRONOTE with **My grades**, **Gradebook**, **Report card**, **Class's report card** and **Old report cards**.
- Replaced the generic grading-period selector with PRONOTE’s left/right period arrows and expandable period list.
- Added the matching PRONOTE-style empty result screen and school-box illustration.
- Added smooth slide-open and arrow-rotation animations to both **Homework notebooks** and **Grades** drawer submenus.
- Corrected the empty-grade illustration using the supplied PRONOTE-style artwork.
- Made the period selector always open, including before any grades are synchronized.
- Fixed the four period labels to **Trimestre 1**, **Trimestre 2**, **Trimestre 3** and **Hors période**.

## Preview 6

- Added direct read-only synchronization of PRONOTE discussions through the linked Pawnote session.
- Added independent **Sync once** and **Auto sync** controls for messages.
- Added a discussion preview and confirmation before replacing the local offline message cache.
- Added a real animated **Communication** drawer section with a functional **Discussions** page.
- Added searchable **All** and **Unread** discussion views with subjects, participants, dates and unread counters.
- Added full offline thread viewing with normalized message text.
- Added downloadable message attachments through Android's download manager.
- Limited each refresh to the 30 newest discussions so automatic synchronization stays responsive.
- Synchronization deliberately does not mark messages as read and cannot send, edit or delete real PRONOTE messages.
- Added last-message-sync status to the synchronization panel.
