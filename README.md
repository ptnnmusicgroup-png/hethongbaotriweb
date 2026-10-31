# PTNN Maintenance Page

A lightweight, responsive static maintenance page for Phương Thích Nghe Nhạc (PTNN).

## Deploy on Netlify

1. Push or merge this repository branch into the branch you want Netlify to deploy (usually `main`).
2. In Netlify, choose **Add new site → Import an existing project** and connect this GitHub repository.
3. Set the production branch to `main`.
4. Leave **Build command** empty (no build step is required).
5. Set **Publish directory** to `.`.
6. Deploy.

The repository includes `netlify.toml` and `_headers`, so Netlify can use the static-site configuration automatically.

## Local preview

Open `index.html` in a browser, or run a static HTTP server from the repository root.

## Notes

- The progress indicator is indeterminate; it does not show a fabricated completion percentage.
- The page includes a `noindex, nofollow` directive while used as a maintenance screen.
- No build dependencies or environment variables are required.
