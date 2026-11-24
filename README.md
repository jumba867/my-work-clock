# My Work Clock — iPhone attendance tracker

## Features
- Office Check In and Check Out buttons.
- Repeatable Break Out / Break In punches.
- Automatic net working-time and break-time calculation.
- 8 hours 30 minutes daily work target, excluding breaks.
- Full-day leave, half-day leave, holiday, and absent markers.
- Monthly summary, CSV export, and full JSON backup/restore.
- Local browser storage and offline caching after first load.

## iPhone setup
This is a small installable web app (PWA), not an App Store native app.

1. Put the contents of this folder on a static HTTPS host (GitHub Pages is one option).
2. Open the hosted HTTPS address in Safari on your iPhone.
3. Tap Share → Add to Home Screen → Add.
4. Launch **Work Clock** from the Home Screen.

## Data and assumptions
- Attendance records are stored in this browser on this device using local storage.
- Data does not automatically sync between devices. Use **Back up all data** and **Restore backup** when changing devices or browsers.
- Saturdays and Sundays are excluded from monthly working-day/unmarked-day totals.
- Unmarked weekdays are shown separately; they are not automatically counted as absences.
- Half-day leave uses a 4h 15m work target when the user also clocks in. Confirm that this matches your employer's policy.
- This tracker is for personal record-keeping and does not connect to an employer attendance system.
