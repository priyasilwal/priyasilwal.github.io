# Priya Silwal — Personal Website

A multi-page, responsive portfolio for GitHub Pages. Design inspired by the editorial navigation and content structure of hirajaved.com, not a copy of that website.

## Publish to existing GitHub repository

1. Open https://github.com/priyasilwal/priyasilwal.github.io
2. In the repository root (main branch), choose **Add file → Upload files**.
3. Upload **all 8 root files and the entire `assets/` folder contents** from this ZIP, preserving the folder name. Replace the previous `index.html` and commit changes.
4. In **Settings → Pages**, set **Deploy from a branch**, `main`, `/(root)`. GitHub Pages may already be configured; don't change it if already live.
5. Open https://priyasilwal.github.io/ and refresh after deployment.

## Files

- `index.html` — Home, About, My Journey, featured research
- `work.html`, `teaching.html`, `research.html`, `publications.html`, `presentations.html` — pages linked in nav
- `styles.css` — all page styling, including mobile layout
- `script.js` — mobile menu and footer date
- `assets/priya-headshot.jpg` — cropped from screenshot of the user's previous website. Replace with the **original high-resolution image** (keep the same path and filename) for the sharpest result.
- `assets/*.svg` — original conceptual illustrations, not charts or measured research data

### To replace the portrait
Rename the original photo `priya-headshot.jpg` and upload it to `assets/`, replacing that file. Its dimensions on the page are controlled by CSS. No initials placeholder is used.

### Links
The website includes confirmed email and GitHub URL but does not invent Google Scholar, LinkedIn or DOI URLs. Add those when you have verified links.

The old `style.css`, `script.js` and `images/` folder can remain in the repository, but the new pages use `styles.css`, `script.js`, and `assets/`. Ensure you replace `script.js` with the new one.
