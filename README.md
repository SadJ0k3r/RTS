# RTS (Tampermonkey Userscripts)

A collection of custom Tampermonkey userscripts managed and versioned in **RTS**.

## Repository Structure

- `*.user.js` — Individual Tampermonkey userscript files with metadata headers (`==UserScript==`).
- `README.md` — Setup and installation documentation.

## Installing on Mobile Devices

### Android
1. Install a mobile browser that supports extensions or userscripts (such as **Firefox** or an extension-capable browser), or check **Tampermonkey** availability for your device/browser.
2. Open the userscript manager and enable it in your browser's add-ons / extensions menu.
3. Navigate to the `.user.js` file in this repository and tap **Raw** so the raw script URL loads.
4. Confirm the installation prompt in your userscript manager to add the script.

### iOS (iPhone / iPad)
1. Install **Tampermonkey** from the Apple App Store (iOS 15.0 or later) or use a compatible Safari userscript extension.
2. Go to **Settings > Safari > Extensions** (or tap the page/extension menu in Safari) and enable your userscript extension.
3. Grant website access permissions when prompted so the script can run on target pages.
4. Open the raw `.user.js` link from this repository in Safari and confirm the install prompt.

## Managing & Updating Scripts
- Open the userscript manager dashboard to toggle scripts on/off, check for updates, or edit `@match` / `@include` rules.
- Push changes to the `main` branch in this repository to keep your scripts backed up and versioned.
