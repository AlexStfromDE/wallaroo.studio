# Wallaroo Studio Website

Static public website for `wallaroo.studio`.

## Pages and URLs

- Homepage: `https://wallaroo.studio/`
- About / Company: `https://wallaroo.studio/about/`
- Products / Games: `https://wallaroo.studio/products/`
- Contact / imprint-style page: `https://wallaroo.studio/contact/`
- Sortiago privacy policy: `https://wallaroo.studio/sortiago/privacy/`
- Legacy privacy URL: `https://wallaroo.studio/privacy/` redirects permanently to the Sortiago policy

## STRATO Deployment

This is a production-ready static website. No build step is required.

1. In STRATO, make sure the `wallaroo.studio` domain points to the webspace folder for this project.
2. Upload the contents of this directory to the document root for `wallaroo.studio` using STRATO's file manager, FTP, or SFTP.
3. Keep the folder structure unchanged, especially `sortiago/privacy/index.html`.
4. Confirm these files are present at the web root: `index.html`, `robots.txt`, `sitemap.xml`, `.htaccess`, `assets/`, `about/`, `products/`, `contact/`, `privacy/`, and `sortiago/`.
5. Test:
   - `https://wallaroo.studio/`
   - `https://wallaroo.studio/products/`
   - `https://wallaroo.studio/sortiago/privacy/`
   - `https://wallaroo.studio/privacy/` (must redirect to the URL above)
6. Use `https://wallaroo.studio/sortiago/privacy/` as the Google Play Console privacy policy URL for Sortiago.

The included `.htaccess` keeps `index.html` as the directory index, redirects HTTP traffic to HTTPS, and permanently redirects `/privacy/` to the canonical Sortiago policy when Apache rewrite support is enabled by the hosting plan.

## Legal Information Used

The contact/imprint and privacy pages use the legal information from the existing `wallaroo.gmbh` site:

- Wallaroo GmbH
- Bonhoefferstr. 31, 90473 Nürnberg, Germany
- Managing Director: Alex Stoilovski
- Commercial register: HRB 44703, Amtsgericht Nürnberg
- VAT ID: DE456811191
- General email: `info@wallaroo.gmbh`
- Studio/app support email: `support@wallaroo.studio`

## Notes

- The website is independent from the Android Sortiago project.
- The visual design is aligned with the existing `wallaroo.gmbh` black/yellow brand system, logo treatment, dark panels, pill navigation, and display typography.
- Product images are stored in `assets/`: `sortiago.jpg`, `Hexa_sprint.jpg`, `MA_strategy.jpg`, and `Lexion_dict.jpg`.
- The app privacy policy covers local game data, Google Play Billing, Google User Messaging Platform, conditional Google AdMob processing, retention and deletion, security, user choices, and support contact details.
- Main support email: `support@wallaroo.studio`.

## Sortiago Terms of Service

- Page: `sortiago/terms/index.html`
- Intended public URL: `https://wallaroo.studio/sortiago/terms/`
- Upload the new page, updated HTML pages, and sitemap to STRATO together. No build is needed.
- After upload, confirm the HTTPS URL opens without login and enter it in Google Play Console as the Terms of Service URL.
- The terms identify Wallaroo GmbH as provider, consistent with the existing imprint and privacy policy. Confirm that this is the actual contracting provider for the app and that the Play Console declarations agree before publishing.
- Publication of this webpage alone does not incorporate terms into an existing player agreement or replace any purchase-specific disclosures, consent, or notices required by law.
