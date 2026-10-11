# Riftbound

Riftbound is a small, mobile-friendly top-down action/social-deduction game prototype. It combines arena combat, objectives, a hidden saboteur, collectible rift shards, character colors, and a portal escape goal.

## Play
Open [the GitHub Pages game](https://p480y7y-debug.github.io/riftbound/) after Pages deployment finishes, or open `index.html` locally in a modern browser.

- Move: on-screen joystick, WASD, or arrow keys
- Pulse attack: button or `F`
- Blink dash: button or `Space`
- Scan terminal: button or `E`
- Emergency meeting: button or `R`

## Project status
This is a solo playable prototype. The other characters are bots; it does not yet include online multiplayer, accounts, chat, or matchmaking. It is not a finished native Android app yet.

## GitHub Pages
Repository Settings → Pages → Build and deployment → Deploy from a branch → `main` → `/ (root)` → Save. Or enable GitHub Actions if using the included workflow.

## Android / Play Store
The browser game is the current prototype. To publish a native Android app, package it with a maintained Android WebView/Capacitor wrapper, test on physical devices, build a signed Android App Bundle (.aab), create a Play Console developer account, and complete Google Play's current testing, content rating, privacy, and target API requirements. Google Play Console has a one-time registration fee; publishing there is not entirely free. Do not upload until tested and all store declarations are accurate.

## License
MIT. See LICENSE.
