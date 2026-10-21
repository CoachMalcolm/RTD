# Privacy and security

## Where your list is kept

| Place | What | Who can see it |
|---|---|---|
| Your device | The browser's storage for the RTD site | Anyone who can use your unlocked device |
| Your GitHub account (if sync is on) | A **secret gist** named "RTD 2.0 data (do not edit)" with one file, `rtd-data.json` | You. A secret gist isn't listed or searchable, but anyone given its exact web address can read it. |
| Backups you export | `RTD backup YYYY-MM-DD.json` wherever you save it | Whoever can open that file |

The app has no server, no accounts, no analytics and no tracking. It talks to exactly one place: GitHub's API, and only when sync is on.

The **app's code** sits in a public repository. That's fine, because the code contains none of your data.

## Your sync key

- It's a GitHub "personal access token" with **only the gist permission**. It can read and change your gists. It can't touch your repositories, password, email or account settings.
- It's stored in the app's storage on each of your devices and sent only to GitHub.
- Give it an **expiration** (90 days to 1 year). GitHub emails you before it expires.
- Don't save the key in notes, texts or email. If you need it on a new device, make a fresh key instead.
- To cancel a key immediately, go to **github.com/settings/tokens** and delete it.

## Device stamps and warnings

Every sync records which of your devices made it. The app warns you when:

- a **new device** joins your sync,
- your file is changed by a device **that isn't on your list**,
- your file is **edited by hand** on GitHub's website, or written without a stamp.

**Limits:** someone who only *reads* your file can't be detected. A determined person who copied a stamp could forge it. The stamps catch careless or accidental changes, not a skilled intruder. Expiring keys and keeping the key private are your real protection.

## If you think your key leaked

1. Delete it at **github.com/settings/tokens**. It stops working at once.
2. Make a new key and paste it into ⚙ Setup → Reconnect on each of your own devices.
3. Look over your list. To see every change, open **gist.github.com**, then your "RTD 2.0 data" gist, then **Revisions**.

## Good habits

- Keep passwords, PINs and account numbers out of the RTD.
- Use a passcode on your phone and laptop.
- Export a backup once a month and keep it somewhere safe (Drive, your laptop).
- If you share a device, turn off sync on it (⚙ Setup → Turn off sync on this device).
