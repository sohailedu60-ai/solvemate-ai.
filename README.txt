# SolveMate AI — PWA starter

## Publish free with GitHub Pages
1. Sign in or create an account at https://github.com.
2. Create a **public** repository named `solvemate-ai`.
3. Upload the contents of this ZIP to the repository root. Keep `index.html`, `manifest.webmanifest`, and `service-worker.js` at the top level and retain the `icons` folder.
4. Open repository **Settings → Pages**.
5. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/(root)`, then Save.
6. Wait for the exact HTTPS website URL displayed in Settings → Pages. It should resemble `https://YOUR-USERNAME.github.io/solvemate-ai/`; use the actual URL GitHub provides.
7. Open that URL in Chrome on Android. Tap ⋮ → **Install app** or **Add to Home screen**.
8. Open the installed app and test it. After first load, try airplane mode to test cached app shell.

## Included
- `index.html`: the problem-solving app
- `manifest.webmanifest`: PWA settings
- `service-worker.js`: offline cache
- `icons/`: 192px and 512px app icons

## Limitations
This is a PWA starter, not an APK or a Google Play release. It uses built-in rule-based guides, not a connected AI model. Saved plans stay in local browser storage and do not sync between devices. HTTPS is required for service workers and normal PWA installation; opening the HTML file directly from Files is not enough.
