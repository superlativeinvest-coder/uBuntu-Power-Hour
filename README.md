# uBuntu Power Hour Experience

Static landing page for the uBuntu Power Hour Experience.

## Live Site Files

These are the files that should be deployed:

- `index.html`
- `styles.css`
- `language-switcher.js`
- `assets/power-hour-hero.png`
- `assets/hermence-portrait.png`
- `vercel.json`

The comparison page, Version 2 page, and reference docs are intentionally ignored from Git and Vercel.

## Deploy To Vercel

1. Create a new GitHub repository.
2. Push this folder to GitHub.
3. In Vercel, choose **Add New Project**.
4. Import the GitHub repository.
5. Use these settings:
   - Framework Preset: `Other`
   - Build Command: leave blank
   - Output Directory: leave blank
6. Deploy.

## Local Preview

Run a simple static server from this folder:

```powershell
python -m http.server 4177
```

Then open:

```text
http://127.0.0.1:4177/index.html
```
