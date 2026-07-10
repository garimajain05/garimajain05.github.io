# Garima Jain — Personal Portfolio

Single-page portfolio site. No build step — just one `index.html`.

## Host on GitHub Pages (5 minutes)

1. Create a new **public** repo named `garimajain05.github.io` (using your exact username makes the site live at the root URL).
2. Add `index.html` (and this README) to the repo:
   ```bash
   git init
   git add index.html README.md
   git commit -m "Add portfolio site"
   git branch -M main
   git remote add origin https://github.com/garimajain05/garimajain05.github.io.git
   git push -u origin main
   ```
3. In the repo: **Settings → Pages → Source: Deploy from a branch → main / (root) → Save**.
4. Site goes live at **https://garimajain05.github.io** within a few minutes.

Alternative: name the repo anything (e.g. `portfolio`) and it lives at `garimajain05.github.io/portfolio`.

## Before publishing — verify these

- **Google Scholar link** (Publications section): currently a search query. Replace with your actual profile URL (`https://scholar.google.com/citations?user=YOUR_ID`).
- **Project descriptions**: I inferred descriptions for capstone-agenticai, Data-Analyst-Agent, and Domain-Q-A-ChatBot from their names — tweak to match reality.
- **Private repos** (capstone, PosteriorOcclusalStudy, Face-Recognition): links will 404 for visitors. Either make them public, remove the links, or keep the cards link-free (CPat/QPERT cards already have no links since they're Dell internal).

## Editing

Everything is in `index.html` — styles at the top, content sections below. To add a project, copy any `<div class="card">…</div>` block in the Projects section.