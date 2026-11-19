SHOPTRACK INSTALLABLE WEB APP — v2.10.10

Upload these files to the ROOT of the same GitHub Pages folder that currently serves ShopTrack:

- Replace the current index.html with this package's index.html.
- Add manifest.webmanifest.
- Add service-worker.js.
- Add the icons folder with icon-192.png and icon-512.png inside it.

Keep the files together at the same level. Commit the changes, wait for GitHub Pages to publish, then open the same ShopTrack address in Chrome on Android. Reload once, open Chrome's menu, and choose Install app. The app button may also appear in ShopTrack's header when Chrome makes the install prompt available.

The app icon is a gold gear with a clear white ST monogram on navy. This is an installable web app, not an APK from the Play Store. ShopTrack keeps its records in this browser's local storage; using the same hosted address preserves the same browser-origin data.
