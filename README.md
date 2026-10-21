# RTD 2.0 · Running To Do

Your weekly running to-do: repurposable blocks, items that roll forward until you cross them off, wth/wcb waiting states with nudges, time-of-day days, repeating events, a journal and patterns.

It runs as a free website on GitHub Pages and installs on your iPhone home screen. Nothing here costs money.

## Put it online (one time, on your MacBook)

1. Sign in at github.com (or create a free account).
2. Go to github.com/new. Name the repository `rtd`, keep it **Public**, and click **Create repository**. (The app's code is public. Your data is not stored here.)
3. On the new repository page, click **uploading an existing file**. Drag in every file from this folder and click **Commit changes**.
4. Open **Settings → Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, Branch to **main** and **/ (root)**, then click **Save**.
5. After a minute or two your app is live at `https://YOUR-USERNAME.github.io/rtd/`.

## Put it on your iPhone

Open that address in **Safari**, tap **Share**, then **Add to Home Screen**.

## Sync iPhone and MacBook

In the app, tap ⚙ and find **Sync your iPhone and MacBook**. Follow the three steps to make a GitHub key (a "token" with gist access only), paste it in, and tap **Connect**. Do the same on your other device with the same key. The second device loads the RTD you already have.

Give the key an expiration: 90 days, or a custom date up to a year out. GitHub emails you before it runs out. When it expires, the app shows "Sync key expired". Make a new key the same way and paste it into Setup on each device. Your entries stay on the device and merge back in, so nothing is lost.

Each sync is stamped with the device that made it (rename devices in Setup). The app warns you at the top of the screen if your file is changed by anything other than your devices, edited by hand on GitHub, or joined by a new device. If a warning wasn't you, delete the key at github.com/settings/tokens and make a new one. Someone who only reads the file can't be detected.

Tip: add a yearly event in the RTD itself ("Renew RTD sync key") with a 7-day heads-up.

Your data lives in a secret (unlisted) gist in your account called "RTD 2.0 data". Setup also has **Export backup** if you want a copy of everything as one file.

## Updating the app later

Upload the new `index.html` the same way (step 3). Devices pick it up the next time they open the app with a connection.

## Files

- `index.html` — the whole app
- `manifest.webmanifest`, `icon-*.png`, `apple-touch-icon.png` — what makes it installable with its own icon
- `sw.js` — lets the app open with no connection
