NFC Writer PWA
==============

How to run:
-----------
1. Unzip this package.
2. On desktop, run a local server in the unzipped folder:
   - Example: `python -m http.server 8000`
3. On your Android phone (same Wi-Fi), open Chrome and visit:
   - http://<your-desktop-IP>:8000/
4. You'll see NFC Writer app. Use buttons to Read, Write, or Lock tags.
5. Install it as a PWA (Add to Home Screen).

Notes:
------
- Works only in Chrome on Android.
- NFC requires HTTPS or localhost, so direct file:/// won't work.
- Tag locking (Make Read-Only) is experimental. Use NXP TagWriter for reliable locking.
