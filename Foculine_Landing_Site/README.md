# Foculine landing page

A one-page static website (HTML + CSS, no JavaScript, no frameworks, no external requests, no tracking or cookies).

## Preview locally
From this folder:

    python3 -m http.server 8000

Then open http://localhost:8000 (on Windows use `python` or `py` if `python3` is not found). Press Ctrl+C to stop.

## Files
- `index.html`: the page
- `css/style.css`: styles
- `assets/downloads/Foculine_Free_Sample.zip`: the free challenge (primary download)
- `assets/downloads/Foculine_20_Minute_QA_Challenge.pdf`: the guide on its own

Links are relative, so they work from any folder or sub-path.

## Deploy free with GitHub Pages
1. Create a new public repository on GitHub and upload the contents of this folder (so `index.html` is at the top level).
2. In the repository, open Settings, then Pages.
3. Under Build and deployment, choose Deploy from a branch, select `main` and `/ (root)`, and save.
4. After a minute the site appears at `https://<your-username>.github.io/<repository-name>/`.
5. Open the page and click both download links to confirm they work.

Other free hosts (Netlify, Cloudflare Pages) also work: upload the folder as-is.

## Updating the sample
Replace the ZIP and PDF in `assets/downloads/` with the same file names.
