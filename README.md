# Prompt Starter Library

Static site ready for GitHub Pages deployment.

## Deploy

1. Push this repository to GitHub.
2. Ensure your default branch is `main` or `master`.
3. In GitHub, open **Settings > Pages**.
4. Under **Build and deployment**, set **Source** to **GitHub Actions**.
5. Push any commit (or run the workflow manually from the **Actions** tab).

The workflow file is:

- `.github/workflows/deploy-pages.yml`

It deploys the repository root (this includes `index.html`) to GitHub Pages.

## Local preview

You can open `index.html` directly in a browser, or run a local static server.
