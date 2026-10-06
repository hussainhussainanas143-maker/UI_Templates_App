# UI Template Collection

Five original interactive product dashboards in HTML, CSS and vanilla JavaScript. All data is simulated.

| App | Folder |
|---|---|
| CampusIQ | apps/campusiq |
| ClimatePulse | apps/climatepulse |
| MoneyPilot | apps/moneypilot |
| FitSense | apps/fitsense |
| CityPulse | apps/citypulse |

`index.html` at the root is a single self-contained page with all five apps (tab bar on top). Each app also works standalone from its own folder.

## Run locally
Extract the zip, then double-click `index.html`.

## Deploy on GitHub Pages
1. Push this folder to a repo (see commands below).
2. Settings > Pages > Source: Deploy from a branch > main > / (root) > Save.
3. Open https://USERNAME.github.io/REPO/ after about a minute.

## Git
git init -b main
git add .
git commit -m "feat: add UI collection with five apps"
git remote add origin https://github.com/USERNAME/REPO.git
git push -u origin main
