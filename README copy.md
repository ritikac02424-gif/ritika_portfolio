# Ritika Chauhan Portfolio

A responsive static portfolio built with HTML, CSS and JavaScript.

## Run locally
Open index.html in a browser. For the animated canvas portrait, serve the folder over HTTP:

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Upload to GitHub
1. Extract this ZIP.
2. Create an empty GitHub repository.
3. Upload the contents of the ritika-portfolio folder, keeping the assets folder intact.
4. Keep index.html at the repository root.

Or from inside the extracted folder:

```sh
git init
git add .
git commit -m "Add Ritika portfolio"
git branch -M main
git remote add origin YOUR_GITHUB_REPOSITORY_URL
git push -u origin main
```

## GitHub Pages
In repository Settings > Pages, select Deploy from a branch, main, and / (root), then Save. GitHub will show the published address when deployment completes.

No package installation, build step, API keys, or backend is required. Typography loads from Google Fonts and falls back to local fonts when offline. Email buttons open the visitor's email application. Credential and project links point to the supplied Google Drive files.

## Edit
- index.html: content, experience tabs, links and images
- style.css: styling and responsive layout
- script.js: navigation, experience tabs and animated portrait
- assets/: the photos and downloadable resume used by the site

This export includes the latest resume content and original About photo. The enhanced portrait remains included because the homepage particle animation uses it.
