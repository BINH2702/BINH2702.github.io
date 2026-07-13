# Nguyen Trong Binh — Personal Academic Website

A dependency-free academic website built for GitHub Pages.

## Publish at `BINH2702.github.io`

1. Create a public GitHub repository named exactly `BINH2702.github.io`.
2. Upload every file and folder from this package to the repository root.
3. Commit the files to the `main` branch.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select **main** and **/(root)**, then save.
7. Visit `https://binh2702.github.io` after GitHub finishes publishing.

The empty `.nojekyll` file tells GitHub Pages to serve this as a plain static site.

## Edit the website

- Main text and links: `index.html`
- Colors, typography, and layout: `styles.css`
- Theme toggle and small interactions: `script.js`
- Profile photo: replace `assets/profile.jpg` with a square image using the same filename
- CV: replace `assets/nguyen-trong-binh-cv.pdf` with the latest version using the same filename
- Favicon: `assets/favicon.svg`

## Before publishing

Review these entries because they were assembled from the supplied CV and existing academic profiles:

- Incoming PhD information at CUHK
- Current VinUniversity position
- Research-interest descriptions
- Google Scholar, LinkedIn, and ORCID links
- Public email address (`trongbinh2702@gmail.com`)

## Local preview

From the project folder:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.
