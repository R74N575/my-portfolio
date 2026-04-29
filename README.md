# Portfolio Website

Static portfolio website built with plain HTML, CSS, and JavaScript.

## Recommended Free Hosting

Best long-term free option for this portfolio: **Cloudflare Pages**.

Why:

- Free plan supports unlimited static requests and unlimited bandwidth.
- Free plan supports 500 builds per month.
- Free plan supports custom domains.
- No build command is needed for this project.
- The `_headers` file in this repo adds basic security and caching headers on Cloudflare Pages.

## Deploy To Cloudflare Pages

1. Create a GitHub repository for this folder.
2. Push these files to the repository.
3. Go to Cloudflare Dashboard > Workers & Pages > Create application > Pages.
4. Connect the GitHub repository.
5. Use these settings:

```text
Framework preset: None
Build command: leave empty
Build output directory: /
Root directory: /
```

6. Deploy.

Cloudflare will give you a free `pages.dev` URL. You can add a custom domain later in the Cloudflare Pages project settings.

## Backup Option: GitHub Pages

GitHub Pages is also free and reliable for a simple portfolio.

1. Push this folder to a GitHub repository.
2. Go to Repository Settings > Pages.
3. Set source to `Deploy from a branch`.
4. Select the `main` branch and `/root`.
5. Save.

GitHub will publish the site at a `github.io` URL.
