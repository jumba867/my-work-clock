# My Work Clock

A lightweight iPhone-friendly attendance tracker (PWA).

## Features
- Check In, multiple Break Out / Break In pairs, and Check Out.
- Company shift policy: 10 hours total at the office, including breaks.
- Up to 30 minutes early departure is allowed when breaks total 0–60 minutes. For breaks between 60 and 90 minutes, every additional break minute reduces the early-departure allowance minute for minute.
- Maximum break allowance: 1 hour 30 minutes. The app warns when the recorded break total exceeds this limit.
- Displays net working time, total break time, remaining office time, expected checkout, early-departure allowance and shift progress.
- Half-day leave retains the existing 4 hours 15 minutes net-working-time target.
- Edit / add missed punch: choose Check In, a specific break event, or Check Out and enter its actual local date/time. The app validates the punch order before saving and recalculates totals.
- Full-day leave, half-day leave, holiday, and absent status.
- Monthly summary, CSV export, JSON backup/restore.
- Offline use after the first successful load.

## Install / update
Host the contents of this folder on GitHub Pages or another HTTPS static host. Open the site in Safari on iPhone and choose Share → Add to Home Screen.

For an existing installation, upload the updated project files to the same GitHub Pages repository and wait for deployment. The service-worker cache version has been incremented so the updated app can be fetched. If the old screen remains, close the installed app completely and reopen it; if needed, open the website in Safari once while online.

## Data and privacy
Attendance data is stored locally in the browser on the device. It is not uploaded to GitHub and does not sync automatically between devices. Use Back up all data regularly and keep the JSON backup somewhere safe.
