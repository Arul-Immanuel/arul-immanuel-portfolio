# Arul Immanuel T — Portfolio

A responsive, static portfolio website built with HTML, CSS and vanilla JavaScript.

## Run locally
1. Extract the ZIP file.
2. Open `index.html` in a modern browser.

No build tools, package installation or server are required.

## Publish
This repository is configured for GitHub Pages using the GitHub Actions workflow in `.github/workflows/pages.yml`.

## Update your content
- Edit `index.html` to update text, links, project cards and certifications.
- Edit `styles.css` to change the visual design.
- Edit `script.js` to change navigation and certificate interactions.
- Replace the `resume.pdf` entry inside `assets/documents_bundle.zip` to update your résumé.
- Add future project case studies in the `#projects` section.

## Notes
- Project outcomes are not fabricated. The project section is clearly marked as in development until completed case studies are added.
- The résumé and 14 distinct certificate PDFs supplied for this portfolio are included in `assets/documents_bundle.zip`.
- A duplicate upload of the Information & Media Literacy certificate was included once.
- Contact and LinkedIn details are taken from the supplied résumé.
- The website loads individual PDFs from the ZIP with JSZip from jsDelivr and provides a direct ZIP download fallback.
