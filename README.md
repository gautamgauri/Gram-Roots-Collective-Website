# Gram Roots Collective Foundation — Hugo + PaperMod (GitHub Pages)

Free, fast, low‑maintenance website for a small NGO.

## Quick start

1. Create repo on GitHub: `gram-roots-website`
2. Upload/push this folder to `main`.
3. In GitHub → **Settings → Pages** → Source: **GitHub Actions**.
4. Deploys to: `https://gautamgauri.github.io/gram-roots-website/`

## Local dev (optional)

- Install **Hugo (extended)**: https://gohugo.io/installation/
- Add PaperMod theme as submodule:  
  ```bash
  git submodule add https://github.com/adityatelange/hugo-PaperMod themes/PaperMod
  ```
- Run locally:
  ```bash
  hugo server -D
  ```

## Customize
- Edit Markdown in `content/`.
- Images → `static/images/` (replace `og.jpg`, `favicon.ico`).
- Update `config.toml` texts & menu.

## Notes
Theme is fetched as a submodule by the GitHub Action (no extra config needed).
