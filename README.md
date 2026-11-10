# Vella Coffee website

Static React + Tailwind site, ready for GitHub Pages.

## Put it online
1. Upload everything in this folder to the **root** of your GitHub repo (replace the old files).
2. In the repo go to **Settings → Pages → Build and deployment → Source** and choose **GitHub Actions**.
3. Push to `main`. The workflow in `.github/workflows/deploy.yml` builds and publishes the site.
   It appears at `https://<username>.github.io/<repo-name>/`.

Custom domain: add it under Settings → Pages, then point your DNS at GitHub.

## Replace the placeholder photos
`src/assets/vella-logo.jpg` and `src/assets/vella-masaka-01.jpg` … `08.jpg` are placeholders.
Overwrite them with the real files, keeping the same names.

## Run locally
```
bun install
bun run dev
```
