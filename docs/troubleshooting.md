# Troubleshooting and FAQ

## The page is blank, or only shows "RTD" and "Loading…"

The app's code didn't run.

- **Opened from Files, Mail or a preview?** Previews show text but don't run apps. Open the web address (`https://YOUR-USERNAME.github.io/rtd/`) in Safari or Chrome instead.
- **Just set up GitHub Pages?** The first build takes a few minutes. Wait, then refresh.
- **Files in a folder?** In the repository, `index.html` must sit at the top level, not inside a folder. If it's inside one, upload the files again directly.
- **Still blank?** Close the app or tab completely and open it again.

## The header says "Not synced · this device only"

Sync isn't set up on this device. Your list still saves here. To share it with your other devices, see ⚙ Setup → Sync.

## The header says "Sync key expired"

Your GitHub key ran out or was deleted. Everything keeps saving on the device.

1. ⚙ Setup → follow the link to make a new key (only **gist** ticked, with an expiration).
2. Paste it into **Reconnect**.
3. Do the same on your other devices.

Everything you did in the meantime merges back in.

## The header says "Sync problem · see Setup"

Usually a weak connection or GitHub being briefly unavailable. Tap **Sync now** in Setup, or just keep going. The app retries when you reopen it and every couple of minutes while it's open.

## Something I added on my phone isn't on my laptop

- Check that both devices show "Synced…" under the dates.
- Changes sync about 3 seconds after you make them, and whenever you reopen the app. Close and reopen on the device that's behind.
- Both devices must use a key from the **same GitHub account**.

## I got a red warning: "Unexpected change" or "New device"

- **New device joined:** if you just connected another device of yours, tap **That was me**.
- **Changed by a device not on your list** or **edited outside the RTD app:** if that wasn't you, tap **It wasn't me** and follow the steps. In short: delete the key at github.com/settings/tokens, make a new one, and reconnect your own devices.

See [Privacy and security](privacy-and-security.md).

## My list disappeared

- **iPhone:** Safari can clear website data for sites you haven't visited in a while, unless the site is on your **home screen**. Always open the RTD from its home-screen icon.
- **Sync on?** Open the app and connect again with your key. Your list comes back from GitHub.
- **Backup?** ⚙ Setup → **Import backup…** and pick your latest `RTD backup ….json`.
- **None of these?** The data was only on that device and can't be recovered. Turn on sync or export a backup once a month.

## I got a new phone

Open the link on the new phone, add it to the home screen, then ⚙ Setup → paste your key → **Connect**. Your whole list loads.

## The PDF button doesn't do anything

- The PDF maker loads from the internet the first time. Connect and try again.
- **iPhone:** you'll see a download prompt or a preview of the PDF. From there, tap **Share → Save to Files** or **Print**.

## The app didn't update after I uploaded a new version

Close the app completely and reopen it. With a connection, it fetches the new version.

## Can I use it on more than two devices?

Yes. Connect each one with the same key. They all show in Setup under "Devices on your sync".

## Can two people share one list?

Not yet. Each person should use their own GitHub key and gets their own list. A shared family or team list is on the ideas list.

## Does it cost anything?

No. GitHub Pages, gists and the app are free.
