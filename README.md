# IronLog iPhone PWA

This version works from a web host and can be added to the iPhone Home Screen.

## Included
Push, Pull, Legs, Upper Body, Full Body, templates, set/rep/weight logging, warm-ups, workout history, PRs, estimated 1RM, previous working set, automatic rest timer, plate calculator, custom exercises, progress chart, offline service worker, and local browser storage.

## Test on Windows
1. Extract the ZIP.
2. Open Command Prompt inside the IronLog_PWA folder.
3. Run: `python -m http.server 8080`
4. Open `http://localhost:8080` on the PC.

## Install on iPhone
The PWA must be hosted over HTTPS. Upload the contents of the folder to a static web host such as GitHub Pages, Netlify, or Cloudflare Pages.

Then:
1. Open the hosted site in Safari on iPhone.
2. Tap Share.
3. Tap Add to Home Screen.
4. Tap Add.

The app then launches from the Home Screen in standalone mode.

## Data note
Workout data is saved using localStorage. Clearing Safari website data can delete the workout history.
Apple Health / HealthKit is not available directly from the browser PWA.
