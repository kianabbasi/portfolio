# Kian Abbasi · Engineering Portfolio

Open `index.html` in a browser to preview the site. It uses plain HTML and CSS and has no dependencies or build step.

## Edit your portfolio

- **Content** lives in `index.html` and `projects/`. The Schedulix page summarizes the product and credits its two developers.
- **Contact** near the bottom of `index.html` uses résumé-sourced links. For a PDF you choose to publish, add it to the repository and link it as `./resume.pdf`.
- **Evidence** lives in `assets/`. Schedulix screenshots came from the product website files. Compass images came from `PolarizationCameraDesignKian.pdf`. The QSET chart uses the three values in the antenna design notes and the DSP chart shows theoretical BER. Add approved simulator outputs or a public repository to `projects/simulator.html` when available. Review product and research figures for sharing permission before publishing. Keep Nokia descriptions at a public-safe level and exclude internal reports, screenshots, and data.
- **Design** lives in `styles.css`. The color palette is at the top. The geometric graphics are CSS illustrations.

## Publish for free on GitHub Pages

1. Create a **public** GitHub repository named `portfolio` (or use `YOUR-USERNAME.github.io` for a site at your GitHub Pages root).
2. Upload the **contents** of this folder to the root of the repository’s default branch, typically `main`. Keep `projects/` and `assets/` alongside `index.html` and `styles.css`. Include `.nojekyll` if your upload tool shows hidden files.
3. Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**. Select `main` and `/(root)`, then save.
4. Once deployed, open **Visit site** in Pages settings. For a repository named `portfolio`, the address looks like `https://YOUR-USERNAME.github.io/portfolio/`. New commits to the publishing branch update the site.

The GitHub Pages link is public and independent of OneDrive. Upload only the portfolio folder’s contents and review the contact details and project images before publishing.

[GitHub Pages publishing source documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
