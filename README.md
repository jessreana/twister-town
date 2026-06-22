# 🌪️ Twister Town

A single-file browser game built for the Build-A-Game Challenge. Steer a tornado
down a top-down map, weave around houses and city buildings (deadly — red
borders), smash through trees and cars for bonus distance, grab map pins for
combos, and clear town after town all the way to the Big City. Distance traveled
is your score.

**Play:** open `index.html` in any browser. No build, no server.

- `index.html` — the game (served at the site root by Netlify / Firebase)
- `tornado.html` — identical canonical copy used during development

## Controls
- **← → / A D** or **mouse / finger** to steer
- Fill the progress bar to clear each town
- Avoid red-bordered buildings; smash trees & cars; collect 📍 pins

## Deploy
Static site, no build step.

- **Netlify:** `netlify deploy --prod` (config in `netlify.toml`)
- **Firebase Hosting:** set your project in `.firebaserc`, then `firebase deploy`
