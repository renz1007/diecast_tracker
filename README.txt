GARAGE LOG — Diecast Tracker
=============================

This is a self-contained web app for tracking your diecast car collection
and wishlist. It works fully offline and stores everything privately on
your own device (nothing is uploaded anywhere).

⚠️ A note on ".apk": a real Android .apk requires Google's Android build
tools, which aren't available in this environment. This app is built as
a Progressive Web App (PWA) instead — once installed to your home screen
it opens full-screen with its own icon, just like a normal app.


OPTION 1 — Quickest: use it straight from your phone (no hosting)
-------------------------------------------------------------------
1. Copy the whole "diecast-tracker" folder onto your phone (e.g. via
   Google Drive, email it to yourself, or a USB cable).
2. Open "index.html" with Chrome (Android) or Safari (iPhone).
3. Use the browser menu → "Add to Home Screen".
This gives you an icon that opens the tracker. On Android/Chrome this
works fully offline right away. On iPhone/Safari, local files have some
extra restrictions — Option 2 below is more reliable for iPhone.


OPTION 2 — Best experience: host it for free, then install like an app
-------------------------------------------------------------------------
This gives you a real installable PWA (offline caching, standalone app
window, install prompt) on both Android and iPhone.

1. Go to https://app.netlify.com/drop in a browser on your computer.
2. Drag the whole "diecast-tracker" folder onto the page.
3. Netlify gives you a free https:// link in a few seconds.
4. Open that link on your phone, then:
   - Android/Chrome: tap the menu → "Install app" (or "Add to Home Screen").
   - iPhone/Safari: tap the Share icon → "Add to Home Screen".
5. Launch it from your home screen — it opens full-screen, no browser bar.

(Any static host works the same way — GitHub Pages, Cloudflare Pages, etc.)


YOUR DATA
---------
Everything is stored locally in the browser you use to open the app
(this is what "on this device only" storage means). There is no login
and nothing is sent to a server.

Because of that:
- Use the BACKUP tab regularly to export a .json backup file.
- If you switch phones, clear browser data, or move from Option 1 to
  Option 2 hosting, import that backup file to bring your collection
  back — the two "locations" don't automatically share data.


FEATURES
--------
- Log cars you own: brand, model, series, scale, color, year, condition,
  quantity, purchase price, current value, purchase date, notes, photo.
- Wishlist for cars you're hunting, with a target price.
- Quick brand filter chips + search across your whole garage.
- Stats tab: total items, total spent, estimated value, gain/loss, and
  a breakdown by brand.
- Backup tab: export/import a full JSON backup, or erase all data.
