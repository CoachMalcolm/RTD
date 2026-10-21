# Changelog

All notable changes to the RTD (Running To Do). Newest first. Dates are when the change was made.

## 1.2 · 2026-10-21 · Device stamps

- Every sync is stamped with the device that made it.
- Warnings at the top of the app when:
  - a new device joins your sync,
  - your file is changed by a device that isn't on your list,
  - your file is edited by hand on GitHub, or written without a stamp.
- "That was me" dismisses a warning. "It wasn't me" shows what to do.
- Setup: name each device and see every device on your sync with its last sync time.
- "Help & tips" link and version number in Setup.

## 1.1 · 2026-10-21 · Safer sync keys

- Instructions now use a GitHub key with an expiration date (90 days to 1 year) instead of "no expiration".
- When a key expires, sync pauses. Entries keep saving on the device, and a Reconnect box takes a new key. Everything made while paused merges back in.
- The sync section moved to the top of Setup.

## 1.0 · 2026-10-21 · Your own copy

- Runs as a free website on GitHub Pages under your own account. No Claude subscription needed.
- Installs on the iPhone home screen with its own icon, and opens offline.
- Sync between devices through a secret gist in your GitHub account.
- Export and import backup (one JSON file).
- "Copy my week as text" to paste into any AI chat, notes app or email.
- Printable PDF summary saves straight to the device.
- Removed: the Claude-only features (Assist, "Describe it", drafted follow-ups).

## 0.2 · 2026-10-21 · Time of day and repeating events (Claude version)

- The hour-by-hour grid was replaced by six time-of-day blocks: Early AM, Morning, Afternoon, Late afternoon, Evening and Night. All of them can be edited.
- Repeating events:
  - Daily, weekdays, weekly on chosen days, every N weeks, monthly (date or "3rd Wednesday"), or yearly.
  - Ends never, on a date, or after N times.
  - Per-date done, skip and note.
  - "End the series after this".
  - Heads-up reminders a set number of days before.
- Coming up panel on the List tab.
- Printable PDF summary of the week.

## 0.1 · 2026-10-21 · First draft (Claude version)

- Rebuilt the 2016 spreadsheet RTD as an app.
- Repurposable blocks you can rename, recolor and reorder.
- Items roll forward week to week until crossed off, with a "wk N" badge.
- Crossed-off items stay visible with a strike-through and become the journal.
- Waiting states wth (waiting to hear back) and wcb (waiting for callback), with nudges. You can add your own.
- WWW notes, next action, per-item log with one-tap entries (lvm, called, texted…).
- Weekly items for recurring sessions.
- Journal and Patterns tabs (strongest day, what keeps rolling, who you're waiting on).

## Before · 15+ years · The spreadsheet

- The original RTD: an Excel or Google Sheets template, one tab per week, printed and kept in a binder. Blocks at the top for whatever projects were on the plate, an hour grid below, a "Weekly ToDo" column, and the habit of crossing things off rather than deleting them.
