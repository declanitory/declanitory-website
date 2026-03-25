# guns.lol static recreation

This is a repo-ready static recreation of the guns.lol landing page based on the provided screenshots and saved page source.

## Files

- `index.html` – page structure
- `styles.css` – full styling
- `script.js` – mobile navigation + FAQ accordion behavior
- `.gitignore` – basic ignores for a static repo

## Run locally

Open `index.html` directly in your browser, or use a simple local server.

### Python

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Push to GitHub

```bash
git init
git add .
git commit -m "Initial guns.lol recreation"
git branch -M main
git remote add origin YOUR_GITHUB_REPO_URL
git push -u origin main
```

## Notes

- This is a front-end recreation, not the original production application.
- Images are referenced from publicly accessible remote asset URLs used by the source page.
- Content and layout were recreated from the saved HTML and screenshots.
