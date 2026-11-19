# HYD Kiosk (Machining Technologies time clock tablet)

Live page: https://mtl-webmaster.github.io/machtech_timeclock/

| File | What it is |
|---|---|
| `index.html` | The kiosk page. Change only the SETTINGS block at the top. |
| `kiosk-config.json` | Remote settings the tablet app checks every 5 minutes. |
| `hyd-kiosk.apk` | The tablet app. Raise `appVersion` in kiosk-config.json when replacing it. |

**To make a change:** open the file here, click the pencil icon, edit, then click **Commit changes**. The tablet picks it up within about 10 minutes.

**To refresh the tablet right now:** change `"reload"` in kiosk-config.json to any new value.

**To undo a change:** open the file → **History** → pick the earlier version.
