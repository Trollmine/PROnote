# PRONOTE 3.5.0

- Added a confirmation screen before a timetable QR changes anything.
- Shows the number of detected Week A and Week B classes.
- Lets you replace only Week A, only Week B, or both weeks.
- Detects weeks that already match the installed timetable and disables pointless duplicate imports.
- Rejects damaged timetable data and explains when a QR was created with an unsupported format version.
- QR imports now preserve date-specific timetable changes and recurring lessons.

- Fixed the PDF scanner dropping the first lesson of every day at the 8h00 timetable boundary.
- The parser now uses the actual top and bottom edges of time labels instead of their center points.
- Enabled AndroidX and Jetifier so the Google QR scanner dependencies compile correctly.
- Restored the Android notification-permission imports after removing the camera permission flow.

- Replaced the crashing embedded QR camera with Android's permissionless Google code scanner.
- Removed PRONOTE's camera permission and obsolete QR capture activity.
- Added QR auto-zoom and a clear in-app error if the system scanner cannot start.

- Fixed PDF imports dropping full-width lessons such as Monday EPS and Tuesday morning classes.
- Fixed nested PDF drawing state so Week A/B blocks are detected consistently.
- Improved tolerance when distinguishing full-week lessons from alternating-week half blocks.

- Preview Week A and Week B before replacing a timetable from PDF.
- Manage exceptional timetable changes for a specific date.
- Export and import Week A and Week B directly with a timetable QR code.
- Check GitHub for new versions, release notes and the latest APK.
- Organize Secret tools into Timetable, Homework, and Account & app sections.
- Fix the QR scanner crashing before opening the camera.
