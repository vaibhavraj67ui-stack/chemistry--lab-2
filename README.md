# Chemistry Lab PWA — Class 12

Hindi + Hinglish revision web app for Class 12 Chemistry.

## Features
- Notes with chapter search
- Formula bank for common numerical topics
- Organic reaction revision
- Interactive MCQ quiz with explanations and score
- Installable PWA support and offline cache

## GitHub Pages setup (Android-friendly)
1. Extract the ZIP.
2. In your GitHub repository, upload all files from this folder to the repository root. Do not upload only the folder itself.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then Save.
6. Wait until GitHub Pages says the site is published, then open the URL shown there.

Important: this project uses relative paths (`./app.js`, `./styles.css`, etc.), so it works when published under a repository path like `https://USERNAME.github.io/REPOSITORY/`.

## If an older version is cached
Open the site in Chrome, refresh once while online. If an old version still appears, clear that site's cache/site data and reopen it. The service worker cache name is `chemistry-lab-v2`.

## Local test
Open `index.html` in a browser for core navigation, notes, formulas and quiz. PWA installation and offline caching require a secure context such as GitHub Pages (HTTPS) or localhost.
