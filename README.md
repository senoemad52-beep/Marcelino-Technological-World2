# Marcelino Technological World — Full Package

This is a full package scaffold for an interactive 3D site (dark tech style).

## Files included
- index.html
- data.json (examples and many categories)
- models/ (place .glb files here)
- scripts/download_models.sh (template)

## How to add realistic GLB models
1. Put your .glb files into `models/` with matching filenames used in data.json.
2. Edit `data.json` to add or update model entries.
3. Run a local server when testing to avoid file:// restrictions:
   - python -m http.server 8000
   - open http://localhost:8000

## Publish to GitHub Pages
1. Create repo and upload files.
2. GitHub Settings -> Pages -> Source: main branch -> root
3. Wait a few minutes and access the provided URL.

If you want, send me links to public-domain GLB files (or allow me to fetch them), and I will embed them into the ZIP and update data.json for you.
