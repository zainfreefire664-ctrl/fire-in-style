FIRE IN STYLE — INSTALLABLE PWA
================================

WHAT'S INCLUDED
- Offline-capable, original single-player battle arena
- Mobile joystick, fire/reload/weapon controls
- Keyboard and mouse controls on computers
- Four weapon types, rival bots, shrinking safe zone, loot
- Sound effects with mute toggle
- Coins, wins, and progress saved on this device
- PWA manifest, icon, and service worker

IMPORTANT INSTALL REQUIREMENT
A PWA cannot be installed reliably by opening index.html directly from a ZIP or file:// location. It must be served from HTTPS (or localhost for development). This ZIP is a web app package, not an Android APK.

EASIEST PHONE INSTALL ROUTE
1. Extract this ZIP. Keep index.html, style.css, game.js, manifest.webmanifest, sw.js, and icon.svg together in one folder.
2. Upload the folder's CONTENTS to an HTTPS static web host (for example, a static site host such as Netlify or GitHub Pages). Do not upload the ZIP as the website itself; deploy the extracted files.
3. Open the resulting HTTPS site in Chrome on your Android phone.
4. Wait for it to load once while online. Then use Chrome's menu (⋮) and choose "Install app" or "Add to Home screen" if offered.
5. Open Fire In Style from the new home-screen icon. After the first successful load, the game files are cached for offline use. Test offline by opening it once, then turning off internet.

CONTROLS
- Mobile: left joystick to move; tap/hold FIRE to shoot; tap arena to aim; RELOAD and WEAPON buttons.
- Desktop: WASD/arrows to move; mouse to aim and hold left mouse button to fire; R reloads; Q changes weapon; Space fires.
- Safe zone shrinks after 15 seconds. Stay inside it.

LIMITATIONS
- This is an original offline arcade prototype, not Free Fire, not online multiplayer, and not an APK.
- Progress is saved locally in the browser on that device. Clearing site data or changing browsers may erase it.
- Sound begins after a user interaction because of browser audio policies.
- This package has been checked for JavaScript syntax and ZIP contents, but has not been tested on every browser/device.
