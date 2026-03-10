# SCI Dispatch PWA

Branded Progressive Web App for Stallbaumer Concrete Industries.

## Included
- Public homepage
- Weather-aware evaporation calculator
- Hourly evaporation forecast
- Public order form
- Employee login simulation
- Dispatch board
- Driver workflow
- Customer tracking
- PWA install support for iPhone and Android

## Local preview
Run a local server in this folder:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Deploy to GitHub Pages
1. Create a new GitHub repository.
2. Upload all files from this folder to the repository root.
3. Commit and push.
4. In GitHub, open **Settings > Pages**.
5. Under **Build and deployment** set:
   - **Source** = Deploy from a branch
   - **Branch** = `main`
   - **Folder** = `/ (root)`

Your site will publish to a URL like:

```text
https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/
```

## Install on Android
1. Open the GitHub Pages link in Chrome.
2. Tap the 3-dot menu.
3. Tap **Install app** or **Add to Home screen**.

## Install on iPhone
1. Open the GitHub Pages link in Safari.
2. Tap **Share**.
3. Tap **Add to Home Screen**.

## Notes
- Weather lookup uses public browser API calls.
- Login, push notifications, SMS, and dispatch actions are prototype/demo logic in this version.
- This package is static-site friendly and ready for GitHub Pages.
