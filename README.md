# Rudra — Static Portfolio

This repository contains a simple static portfolio site for Rudra Kumar under the `public/` directory. The site is intended to be published to GitHub Pages (gh-pages branch) using the included GitHub Actions workflow.

What this PR adds

- `public/` — HTML, CSS, JSON and assets for a small portfolio site
- `.github/workflows/deploy.yml` — GitHub Actions workflow to publish `public/` to the `gh-pages` branch when `main` is updated

How to customize

- Edit content in `public/index.html` (name, bio, contact email) or update `public/projects.json` to change projects.
- Replace images in `public/assets/` with your own screenshots and avatar.

Publishing flow

1. Merge this pull request into `main`.
2. The workflow `Publish site to gh-pages` will run on `push` to `main` and deploy the `public/` folder to the `gh-pages` branch.
3. After deployment, the site will be available at: `https://Rudra-RNC.github.io/Rudra/` (allow a minute for GitHub Pages to publish).

Custom domain

- This PR does not add a `CNAME`. If you want to use a custom domain, add a `CNAME` file to the `gh-pages` branch containing your domain (e.g. `rudrakumar.com`) and configure DNS at your registrar.

If you want any text changes (email, projects, socials) I can update the branch before you merge.