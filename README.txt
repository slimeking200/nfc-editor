# NFC Editor • PWA (with Install button)

This bundle is ready for **HTTPS hosting** (GitHub Pages / Netlify / Vercel) or **localhost**. It includes a manual **Install** button using the `beforeinstallprompt` event.

## How to deploy on GitHub Pages
1. Create a repo (public).
2. Upload all files in this folder.
3. Repo Settings → Pages → Source: `main` branch, root (`/`).
4. Open: `https://<your-username>.github.io/<repo>/` (HTTPS).

## Use
- Open the site in **Chrome on Android**.
- Tap **Install App** when the button enables (depends on `beforeinstallprompt`). 
- Paste or load your JSON, choose MIME/Text, then **Write to Tag** or **Read Tag**.

## Notes
- Web NFC requires **HTTPS or `http://localhost`**.
- `makeReadOnly()` is experimental; if it fails, lock with NXP TagWriter/NFC Tools.
