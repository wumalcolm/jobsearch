# Malcolm's Job Outreach Tracker

Static HTML app ready for GitHub Pages deployment.

Last Pages refresh: 2026-04-14

## Local preview

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000/index.html`.

## Deploy to GitHub Pages

1. Create a new GitHub repository.
2. Push this folder to the repository.
3. In GitHub, open `Settings` -> `Pages`.
4. Under `Build and deployment`, choose `Deploy from a branch`.
5. Select the `main` branch and the `/ (root)` folder.
6. Save and wait for GitHub Pages to publish.

Your site URL will look like:

`https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/`

## Important note

This app currently stores and uses the Gemini API key in the browser. That is okay for private/personal use, but it is not safe for a public deployment with a shared key.
