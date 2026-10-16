# BFBL Hoops Hub

Static build of the BFBL (Hoops) league scoring app.

- index.html is a self-contained single-file app. Open it in any modern browser.
- Click "Edit" to enable editing. Saves persist to your browser's localStorage.
- Use "Export state" to download a JSON backup. Use "Import state" to restore.
- Use "Export HTML" to download a self-contained snapshot with the current league state embedded.

Deploying with GitHub Pages
1. Go to Settings → Pages in the repository.
2. For Source pick branch: `main` and folder: `/` (root). Save.
3. The site will be available at: `https://<your-username>.github.io/bfbl-hoops-hub/` shortly.

If you want further changes (API-backed saving, React rewrite, or additional features), tell me and I can add them.
