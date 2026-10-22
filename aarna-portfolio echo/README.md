# Aarna Pandey | Supply Chain and Finance Portfolio

A single-page portfolio site. No build step: it is plain HTML and CSS.

## Files
- `index.html`: the whole site
- `resume.pdf`: linked from the "Download resume" buttons (replace it with your latest resume, same file name)

## Publish on GitHub Pages
1. On GitHub, create a new public repository, for example `supply-chain-portfolio`.
2. Click **Add file > Upload files**, drag in `index.html`, `resume.pdf` and this README, then click **Commit changes**.
3. Go to **Settings > Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, choose the `main` branch and the `/ (root)` folder, then click **Save**.
4. After a minute or two the site is live at `https://aarnaap.github.io/supply-chain-portfolio/`.

To make this your main site at `https://aarnaap.github.io/` instead, upload the files to the repository named `aarnaap.github.io`. That will replace whatever is there now, so back it up first.

## Editing
Everything is in `index.html`. Projects are `<article class="project">` blocks, roles are `<div class="role">` blocks, and the key figures sit in the small tables next to each project.
