GAS CYLINDER LOG — IPHONE INSTALL

This is a Progressive Web App (PWA). It is not a signed native iOS .ipa file. To install it, the app must first be hosted at an HTTPS address.

1. Upload every file in this folder to a static web host that serves HTTPS. Keep the files together in the same folder.
2. On the iPhone, open the resulting HTTPS URL in Safari.
3. Tap Share, choose Add to Home Screen, then tap Add.
4. Launch Gas Cylinder Log from the new Home Screen icon.

The app works offline after its first successful load. Cylinder records are stored locally on that iPhone only. They do not sync with the computer or other phones. Use Back up regularly and keep the JSON backup somewhere safe. Restoring replaces all records currently on the device.

The app bundle includes index.html, manifest.webmanifest, service-worker.js, and PNG icons. Do not open index.html directly from Files; iPhone installation requires an HTTPS site opened in Safari.
