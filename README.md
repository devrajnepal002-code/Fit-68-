# FIT68 Android-installable fitness tracker

This is an installable Progressive Web App (PWA), designed for Android Chrome. It includes:
- Monday–Saturday home workout plans with exercise instructions and completion checkboxes
- Rest timer
- Weekly weight log toward 68 kg
- Waist and stamina tracking
- Offline caching after first load

## Install on Android
A PWA must be served from an HTTPS website (or localhost) to install reliably. It cannot be installed by simply opening `index.html` from your Downloads folder.

1. Upload the contents of this folder to an HTTPS static host, such as GitHub Pages.
2. Open the published website in Chrome on your Android phone.
3. Tap Chrome's ⋮ menu, then **Install app** or **Add to Home screen**.
4. Open FIT68 from your home screen.

## Publish with GitHub Pages
1. Create a GitHub repository.
2. Upload `index.html`, `manifest.json`, `sw.js`, and the `icons` folder to the repository root.
3. In repository Settings → Pages, choose deploy from the `main` branch and `/ (root)`.
4. Wait for the HTTPS Pages URL, then open it in Android Chrome and install.

## Privacy
Workout checkmarks, weight entries and measurements are stored locally in the browser on your device. They are not sent to a server. Clearing Chrome site data may erase them.

## Fitness note
The workout schedule is general fitness guidance, not a medical assessment. Start at a manageable level, use low-impact substitutions where needed, and stop if you experience chest pain, dizziness or unusual breathlessness.
