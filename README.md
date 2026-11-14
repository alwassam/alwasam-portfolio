# Alwasam Alshammari — Engineering Portfolio

A lightweight, responsive portfolio website designed for **GitHub Pages**. No React, Node.js, build tools, or paid hosting are required.

## Preview locally

Open `index.html` in a browser. For a more accurate preview, serve this folder:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish to GitHub Pages (no coding required)

1. Create a free account or sign into [GitHub](https://github.com/).
2. Choose **New repository**, and name it `alwasam-portfolio` (or any other repository name). Choose **Public**, then create the repository.
3. **Extract the ZIP file** you received. In the new GitHub repository, choose **Add file → Upload files**. Upload **all items inside the extracted folder**, not the ZIP itself and not the enclosing folder. Keep `index.html`, `styles.css`, `script.js`, `favicon.svg`, `assets/`, and `Alwasam_Alshammari_Resume.pdf` in the same relative structure.
4. Click **Commit changes**.
5. Go to **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**. Choose **main** and **/(root)**, then **Save**.
6. After GitHub publishes the site, select **Visit site** in Settings → Pages. Your address will normally be `https://YOUR-USERNAME.github.io/alwasam-portfolio/`.

**Important:** GitHub Pages requires `index.html` at the root of the selected publishing folder. The previous ZIP put it inside another folder; this package is already organized correctly.

## File layout

```
index.html                           # Homepage and portfolio content
styles.css                           # Responsive styling
script.js                            # Mobile navigation
favicon.svg                          # Browser tab icon
.nojekyll                            # Tells GitHub Pages to serve static files as-is
Alwasam_Alshammari_Resume.pdf       # Linked PDF résumé
assets/
  wyie-award.webp                    # Kuala Lumpur award photo
  wyie-silver-certificate.webp       # Silver Medal certificate
  wyie-merit-certificate.webp        # Merit certificate
  cubi-certificate.webp              # Penn State design award
  profile.webp                       # Portrait
  research/README.md                 # Where future lab photos go
```

## Why pictures might have been broken before

- The old ZIP contained an enclosing folder; `index.html` must be at the published root.
- If only `index.html` is uploaded, the `assets/` files are missing.
- GitHub filenames are case-sensitive. `wyie-award.webp` is not the same as `WYIE-Award.webp`.
- Keep relative paths like `./assets/wyie-award.webp` — do not change them to `/assets/...` because GitHub project sites are hosted in a repository subpath.

This version has relative paths and local images; it does not depend on Google Drive, Instagram, or hotlinked photographs.

## Update the website

- Edit text in `index.html`.
- Adjust design in `styles.css`.
- Change the top photograph by replacing `assets/wyie-award.webp` with a file of the same name.
- To add lab photos, read `assets/research/README.md`.
- Change the résumé by replacing `Alwasam_Alshammari_Resume.pdf`.
- Push or commit changes to `main`; GitHub Pages publishes updated content automatically.

## Privacy and research-publication considerations

This public portfolio includes a name, university, email address, awards, and user-supplied images. Review these before publishing. Lab data, unreleased manuscripts, and photographs of experiments should be shared only after permission from your research supervisor.

Created November 2026.
