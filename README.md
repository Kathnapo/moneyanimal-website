# MoneyAnimal — GitHub Pages website

This is a complete static site. No build tools are required.

## Publish to GitHub Pages

1. Create a GitHub repository, for example `moneyanimal-website`.
2. Upload **all files from this ZIP to the repository root** (including `index.html`), then commit.
3. Open repository **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, `main`, and `/(root)`; save.
5. Visit the URL shown in the Pages settings after deployment completes.

## Domain and SEO

The canonical URL, social preview metadata, robots.txt, and sitemap.xml are configured for **https://moneyanimal.app/**. To use that domain, configure DNS as recommended by GitHub Pages, and set `moneyanimal.app` under **Settings → Pages → Custom domain**. You can also rename `CNAME.example` to `CNAME` once you are ready to use the custom domain. Enable HTTPS when available.

If publishing to a default project URL like `https://USERNAME.github.io/REPO/`, update the absolute URLs in `index.html`, `robots.txt`, and `sitemap.xml` to that exact destination (including `/REPO/`).

## Files

- `index.html`: website, including CSS and embedded media.
- `favicon-32x32.png`, `icon-192.png`, `apple-touch-icon.png`: your actual paw favicon and app icons.
- `social-preview.png`: social sharing preview artwork.
- `google-search-preview.png`: illustrative preview using **the actual favicon**; not required by Google Search.
- `robots.txt`, `sitemap.xml`: indexing support.
- `.nojekyll`: disables Jekyll processing.
- `404.html`: fallback page.

## After publishing

Check the home page, favicon and download buttons; then verify your canonical domain, sitemap and social sharing image. Submit the sitemap in Google Search Console. Google chooses its own snippet and may not show exactly what appears in the included illustrative preview.
