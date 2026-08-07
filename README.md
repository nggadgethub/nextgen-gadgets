# NextGen Gadgets — Netlify + Decap CMS

This is a static affiliate-site starter prepared for the `nggadgethub/nextgen-gadgets` GitHub repository.

## Main pages
- `index.html`
- `products.html`
- `product-details.html?id=wireless-earbuds`
- `categories.html`
- `comparison.html`
- `affiliate-disclosure.html`
- `privacy.html`
- `terms.html`

## Product manager
Open `/admin/` on the deployed site.

The Decap CMS dashboard edits `products.json` and uploads product images to `images/products/`.

## Important setup
This package uses the Decap CMS GitHub backend. Netlify must be configured to allow GitHub authentication for the CMS. The repository is expected to be:
`nggadgethub/nextgen-gadgets`

If your Netlify production URL is different, update `site_url` and `display_url` in `admin/config.yml`.

## Before publishing
Replace sample product information, verify MRP/current prices/specifications, add your actual affiliate URLs, and replace the starter legal text with policies appropriate to your site.
