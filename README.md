# p-w-rtm

This is a public GitHub repository for a minimal static website.

## Website Content

- The site content is a single HTML file: `index.html`
- GitHub Pages serves this HTML as the public site

## Automatic Publishing

This repository includes a GitHub Actions workflow at:

- `.github/workflows/deploy-pages.yml`

Publishing behavior:

Prerequisite: GitHub Pages must be configured to deploy from **GitHub Actions** in repository settings.

1. When HTML files (or the deployment workflow file) are changed and pushed to `main`, the workflow runs automatically
2. The workflow deploys repository contents from the root (`.`) to GitHub Pages
3. The live page is refreshed with the latest `index.html` updates

You can also run the workflow manually from the Actions tab using `workflow_dispatch`.

## Notes

- Ensure GitHub Pages is configured to deploy from **GitHub Actions** in repository settings.
- Keep updates focused on HTML content for this minimal site setup.
