# Mitchell_Site

This repository contains a simple HTML site intended to be hosted with GitHub Pages.

## What's included

- `index.html` — main site file (already copied into `docs/` for GitHub Pages)
- `docs/` — directory served by GitHub Pages (contains `index.html` and `.nojekyll`)

## How to publish on GitHub Pages

1. Commit and push your repository to GitHub.
2. In your repository on GitHub, go to Settings → Pages.
3. Under "Source", select "Deploy from a branch" and choose the branch (usually `main`) and the `/docs` folder.
4. Save — GitHub Pages will build and publish the site. The URL will be shown on the Pages settings page.

## Custom domain (optional)

If you have a custom domain, create a `CNAME` file in the `docs/` folder containing only your domain (e.g. `www.example.com`).

## Troubleshooting

- If assets or files with underscores or specific filenames are not showing, ensure `.nojekyll` exists in `docs/` (it does by default here).
- If changes don't appear, wait a few minutes and clear your browser cache, or check the Pages build logs in GitHub.

## Next steps

- Update `docs/index.html` with your real name, links, and content.
- Add images or assets under `docs/` and reference them with relative paths.
