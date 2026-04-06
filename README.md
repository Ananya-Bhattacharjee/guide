# GUIDE Project Website

Static project page for paper content (title, authors, abstract, results, code link, BibTeX).

## Files

- `index.html` — page content
- `styles.css` — styling
- `assets/` — figures and media

## Local preview

From this folder, run any static server. For example:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy with GitHub Pages

1. Create a new GitHub repo (recommended name: `guide-project-website`).
2. Push this folder:

```bash
git add .
git commit -m "Initial project website"
git branch -M main
git remote add origin https://github.com/<your-org-or-user>/guide-project-website.git
git push -u origin main
```

3. In GitHub: **Settings → Pages**
   - Source: **Deploy from a branch**
   - Branch: `main` / root

4. Your site URL will be:
   - `https://<your-org-or-user>.github.io/guide-project-website/`

## Customize checklist

- Replace paper title and authors in `index.html`.
- Replace abstract text.
- Add your figure at `assets/teaser-placeholder.png` (or change file path).
- Update code repo link.
- Replace BibTeX entry.
