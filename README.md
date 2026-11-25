# OpsFable website — updated brand assets

Responsive static site for GitHub Pages. This update integrates the OpsFable infinity-flow logo, favicon, social preview metadata, and LinkedIn assets while preserving the original page content and layout.

## What's updated

- Header and footer use the refreshed icon + OpsFable wordmark styling.
- Contact-panel decorative mark uses the refreshed icon.
- Updated SVG favicon and Apple touch icon.
- Added Open Graph and Twitter card metadata plus a 1200×630 social preview image.
- Added Organization JSON-LD with the business website and email only (no personal identity).
- Included LinkedIn company logo and cover assets under `brand/linkedin/`.

## Files

- `index.html` — page content, metadata, logo markup
- `styles.css` — layout and refreshed brand styles
- `script.js` — existing interactions
- `assets/opsfable-icon.svg` — refreshed icon used in the website
- `assets/opsfable-wordmark.svg` — full wordmark asset
- `assets/opsfable-social-preview.png` — link-sharing image
- `brand/linkedin/company-profile-logo.png` — LinkedIn company profile logo
- `brand/linkedin/company-cover.png` — LinkedIn company cover

## Publish to the existing GitHub Pages repository

1. Download and extract this ZIP.
2. Open the existing repository `https://github.com/opsfable/opsfable-automations`.
3. Upload the updated files/folders to the repository root (same level as the current `index.html`).
4. If GitHub asks, choose **Commit changes**. A commit to the configured Pages branch should trigger deployment automatically.
5. Wait for Pages deployment, then open `https://opsfable.github.io/opsfable-automations/` and hard-refresh (Ctrl+F5).

For easiest replacement, upload the whole extracted contents. Keep the same root structure; do not upload the outer ZIP folder as a nested directory.

## Contact

The contact link is set to `hello.opsfable@gmail.com`. The site is static and the contact button opens the visitor's email client via `mailto:`.

## Branding

Colors: deep navy, electric blue and cyan. Tagline: **Make operations work smarter.**
