# Execution OS

A lightweight, offline-first daily execution tracker for:

- Health
- APPSC Group-I preparation
- Wealth
- Value / Impact
- Knowledge → Action
- Daily review

## Run locally

Open `index.html` in a browser.

For full PWA installation/offline service-worker behavior, host it on HTTPS (GitHub Pages works).

## Publish on GitHub Pages

1. Create a new GitHub repository, e.g. `execution-os`.
2. Upload all files in this folder to the repository root.
3. In GitHub: **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the main branch and `/ (root)`.
6. Save and open the generated Pages URL.
7. On a supported mobile browser, use the browser's **Add to Home screen / Install** option.

## Data

Daily data is stored in the browser's `localStorage` on the device/browser you use. It is not sent to a server by this app.

Use **Export** regularly to download a JSON backup. Use **Import** to restore it.

## Design principle

The app intentionally tracks outputs rather than merely time spent:

Learn → Recall → PYQs → Analyse mistakes → Write → Apply → Review.
