# SuperCF – Superset × CrossFit

Progressive strength training with supersets + CrossFit finishers & benchmarks.  
Works as an installable iPhone app (PWA).

## Live on GitHub Pages

1. Create a new repository on GitHub (e.g. `supercf` or `workout-app`).
2. Upload **all** these files to the root of the repo:
   - `workout-app.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
   - `apple-touch-icon.png`
   - `README.md` (optional)
3. Go to **Settings → Pages**.
4. Under **Source**, choose **Deploy from a branch**.
5. Select branch `main` (or `master`) and folder `/ (root)`.
6. Click **Save**.
7. Wait 30–60 seconds. Your site will be at:

   `https://YOUR-USERNAME.github.io/REPO-NAME/workout-app.html`

   (Example: `https://johndoe.github.io/supercf/workout-app.html`)

## Install on iPhone

1. Open the link above in **Safari** (not Chrome).
2. Tap the **Share** button (square with arrow).
3. Scroll and tap **Add to Home Screen**.
4. Name it **SuperCF** → Add.

It now opens fullscreen like a native app and works offline after the first load.

## Local testing

Just open `workout-app.html` in a browser. For full PWA features (install + offline) it needs to be served over HTTPS (GitHub Pages does this automatically).
