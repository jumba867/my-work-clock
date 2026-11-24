# My Work Clock

A lightweight iPhone-friendly attendance tracker (PWA).

## Features
- Check In, multiple Break Out / Break In pairs, and Check Out.
- Daily net-work target of 8 hours 30 minutes (breaks excluded).
- **Edit / add missed punch:** choose Check In, a specific break event, or Check Out and enter its actual local date/time. This works for previously selected dates too. The app validates the punch order before saving and recalculates work/break totals.
- Full-day leave, half-day leave, holiday, and absent status.
- Monthly summary, CSV export, JSON backup/restore.
- Offline use after the first successful load.

## Install / update
Host the contents of this folder on GitHub Pages or another HTTPS static host. Open the site in Safari on iPhone and choose Share → Add to Home Screen.

For an existing installation, upload the updated project files to the same GitHub Pages repository and wait for the deployment. The service-worker cache version has been incremented so the updated app can be fetched. If the old screen remains, close the installed app completely and reopen it; if needed, open the website in Safari once while online.

## Data and privacy
Attendance data is stored locally in the browser on the device. It is not uploaded to GitHub and does not sync automatically between devices. Use Back up all data regularly and keep the JSON backup somewhere safe.
