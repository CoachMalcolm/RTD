# RTD · Running To Do

A weekly running to-do list, rebuilt from a paper-and-spreadsheet system used for more than 15 years.

The idea is simple. Everything on your plate lives in a few **blocks**. You **cross things off** instead of deleting them, so the list doubles as a journal. Anything not crossed off **rolls into next week** until it's handled. The rule behind every design choice is **WMtMS: whatever makes the most sense** for what's on your plate right now. Blocks, statuses and the shape of your day can all change as your life does.

**Open the app:** `https://YOUR-USERNAME.github.io/rtd/`

## What it does

| | |
|---|---|
| **List** | Your blocks and their items. Capture bar at the top, Coming up (events and heads-ups) below it. |
| **Days** | Each day split into time-of-day blocks, with your events and planned items. A week-notes box at the top. |
| **Journal** | Everything you did this week, by day and time. Printable PDF and "Copy my week as text". |
| **Patterns** | Your strongest day for finishing things, what keeps rolling, who you're waiting on, progress by block. |
| **Setup (⚙)** | Sync, backup, blocks, statuses, week start, time-of-day blocks, device names. |

- Items carry **WWW notes** (who, where, what, why), a **next action**, a **status** and a **log**.
- **Waiting states:** wth (waiting to hear back) and wcb (waiting for callback). You can add your own. Each gets a nudge after a set number of days.
- **Repeating events** with per-date done, skip and note, plus heads-up reminders.
- **Works offline.** Installs on your phone's home screen. Syncs across devices through your own GitHub account.

## Docs

- [How to use the RTD: tips, tricks and hints](docs/how-to-use.md)
- [Share it: email and first-time setup for friends](docs/share-with-friends.md)
- [Troubleshooting and FAQ](docs/troubleshooting.md)
- [Privacy and security](docs/privacy-and-security.md)
- [Feedback log](docs/feedback-log.md): notes for the next round of changes
- [Changelog](CHANGELOG.md)

## Host it yourself (one time, on a computer)

1. Sign in at github.com (a free account is fine).
2. Go to github.com/new. Name the repository `rtd`, keep it **Public**, and click **Create repository**. Only the app's code is public. Your data is stored separately.
3. Click **uploading an existing file**. Drag in every file and the `docs` folder, then click **Commit changes**.
4. Open **Settings → Pages**. Set Source to **Deploy from a branch**, choose **main** and **/ (root)**, and click **Save**.
5. In a minute or two it's live at `https://YOUR-USERNAME.github.io/rtd/`.

## Sync your devices

In the app, tap ⚙, then **Sync your iPhone and MacBook**:

1. Follow the link to make a GitHub key. Leave only **gist** ticked and set an expiration (90 days to 1 year).
2. Paste the key and tap **Connect**.
3. Do the same on each device with the same key.

When the key expires, the app says so. Make a new key and paste it into the **Reconnect** box. Nothing is lost.

## Updating the app

1. Open the repository on github.com.
2. Choose **Add file → Upload files**.
3. Drag in the changed files and click **Commit changes**.

Devices pick up the new version the next time the app opens with a connection. Close and reopen it once if it doesn't show right away.

## Files

| File | What it is |
|---|---|
| `index.html` | The whole app |
| `manifest.webmanifest`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` | What makes it installable, with its own icon |
| `sw.js` | Lets the app open with no connection |
| `docs/` | Guides |
| `CHANGELOG.md` | What changed and when |

## Where your data lives

- **On each device:** the browser's storage for this site. It's saved instantly and works offline.
- **In your GitHub account (if sync is on):** a secret gist named "RTD 2.0 data (do not edit)", holding one file, `rtd-data.json`.
- **In backups you export:** `RTD backup YYYY-MM-DD.json`.

Nothing is sent anywhere else. There's no server, no account with us, and no tracking.
