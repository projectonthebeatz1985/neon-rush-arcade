# Neon Rush Arcade — installable app package

This is the same Neon Rush Arcade game packaged as an installable Progressive Web App (PWA) for Windows 11, Android, and iPhone/iPad.

## Run locally
Open `index.html` in a browser to play. For installation testing, the app must be served from HTTPS (or localhost); opening the file directly does not enable PWA installation.

## Free hosting and installation
1. Create a free GitHub account if you do not already have one.
2. Create a new **public** repository named `neon-rush-arcade`.
3. Upload the contents of this folder (not the folder itself) to the repository's root.
4. In the repository, open **Settings → Pages**.
5. Under Build and deployment, choose **Deploy from a branch**, select **main** and **/(root)**, then Save.
6. Wait for GitHub Pages to publish. Your address will look like `https://YOUR-USERNAME.github.io/neon-rush-arcade/`.

### Windows 11
Open the published address in Microsoft Edge or Chrome. In Edge, use **… → Apps → Install this site as an app**. In Chrome, use **Install** in the address bar/menu when offered.

### Android
Open the published address in Chrome. Tap **⋮ → Install app** or **Add to Home screen**.

### iPhone / iPad
Open the published address in Safari. Tap **Share → Add to Home Screen → Add**. Launch it from the new home-screen icon.

## Notes
- The game and core files are cached for offline play after the first successful load.
- This is a web app installed on each device, not a native App Store / Google Play Store package.
- Publishing to the Apple App Store or Google Play requires separate store developer accounts and packaging/review steps. The PWA route avoids those fees.
- GitHub Pages is free for public repositories. A custom domain is optional and costs extra.
