# Academic Website (Pure HTML/CSS)

A minimalist, responsive academic website in **emerald green + white**. No frameworks, no build tools — just HTML & CSS. Perfect for GitHub Pages.

## Quick Start

1. **Edit content** in the HTML files:
   - `index.html`: name, bio, headshot path, links.
   - `publications.html`: add your entries (use `<details>` for BibTeX).
   - `cv.html`: place your CV at `assets/cv.pdf` (update the link text if needed).
2. **Add assets**:
   - Put your headshot at `assets/headshot.jpg` (or update the `<img>` path in `index.html`).
   - Put your CV PDF at `assets/cv.pdf`.
3. **Deploy on GitHub Pages**:
   - Create a repo named `<username>.github.io` (or any repo).
   - Commit these files to the repo’s root.
   - If using `<username>.github.io`, it’s live at `https://<username>.github.io` automatically.
   - Otherwise, enable **Settings → Pages → Deploy from Branch** (root), then visit the URL it shows.
4. **Customize theme**:
   - Tweak colors in `styles.css` under the `:root{ --emerald: ... }` variables.
   - Replace the inline SVG favicon in `index.html` with your own if desired.

## Tips

- Keep publications in two sections: **Preprints** and **Peer-reviewed**.
- Add DOI/arXiv links, and a `Code` button when relevant.
- Obfuscate email (e.g., write `name [at] domain [dot] edu`) in HTML if spam is a concern.
- You can add a `contact.html` later by copying the page scaffold from `publications.html`.

## License

MIT — do whatever you like. Attribution appreciated but not required.
