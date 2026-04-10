# Hay Day Companion (Offline Web App)

This is a lightweight, offline-first web app you can run on **computer** or **phone**. It stores content in your browser's local storage.

## What it includes (seeded)
- NPC/Helper **characters** (starter list) sourced from Hay Day Wiki character category.
- **XP & leveling** overview and XP sources.
- **Marker Stake** details: unlock level, storage, and acquisition methods.
- **Expansion** overview and required supplies for Farm/Fishing/Town.
- **Town upgrade materials** examples.

## Sources used for seeded content
- Hay Day Wiki — Experience: https://hayday.fandom.com/wiki/Experience
- Hay Day Wiki — Marker Stake: https://hayday.fandom.com/wiki/Marker_Stake
- Hay Day Wiki — Expansion: https://hayday.fandom.com/wiki/Expansion
- Hay Day Wiki — Characters category: https://hayday.fandom.com/wiki/Category:Characters
- Hay Day Wiki — Expansion Permit: https://hayday.fandom.com/wiki/Expansion_Permit
- Supercell Support — Land Expansion: https://support.supercell.com/hay-day/en/articles/land-expansion.html
- Supercell Support — Rose & Ernest (Farm Helpers): https://support.supercell.com/hay-day/en/articles/farm-helpers-rose-ernest.html
- Supercell Support — Upgrade Service Building: https://support.supercell.com/hay-day/en/articles/upgrade-service-building.html

## Run it locally (computer)
1. Unzip the folder.
2. Open `index.html` in a browser.

## Install on phone/computer (recommended)
For proper install as an app (PWA), most browsers require the app to be served over **https** or from `localhost`.

### Option A: Quick local server (computer)
- Python: `python -m http.server 8080`
- Open: http://localhost:8080/hayday-companion/

### Option B: Host it (best for phone install)
Upload the folder to any static host (GitHub Pages, Netlify, etc.). Then:
- Android/Chrome: open site → menu → **Install app** / **Add to Home Screen**
- iPhone/Safari: open site → share button → **Add to Home Screen**

## Move data between devices
Use the in-app **Export JSON** button, then import that file on the other device.

