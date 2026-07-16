# Wallaroo Studio Website

Static public website for `wallaroo.studio`.

## Pages and URLs

- Homepage: `https://wallaroo.studio/`
- About / Company: `https://wallaroo.studio/about/`
- Products / Games: `https://wallaroo.studio/products/`
- Contact / imprint-style page: `https://wallaroo.studio/contact/`
- Website privacy overview: `https://wallaroo.studio/privacy/`
- Sortiago privacy policy: `https://wallaroo.studio/sortiago/privacy`

## STRATO Deployment

This is a production-ready static website. No build step is required.

1. In STRATO, make sure the `wallaroo.studio` domain points to the webspace folder for this project.
2. Upload the contents of this directory to the document root for `wallaroo.studio` using STRATO's file manager, FTP, or SFTP.
3. Keep the folder structure unchanged, especially `sortiago/privacy/index.html`.
4. Confirm these files are present at the web root: `index.html`, `robots.txt`, `sitemap.xml`, `.htaccess`, `assets/`, `about/`, `products/`, `contact/`, `privacy/`, and `sortiago/`.
5. Test:
   - `https://wallaroo.studio/`
   - `https://wallaroo.studio/products/`
   - `https://wallaroo.studio/sortiago/privacy`
6. Use `https://wallaroo.studio/sortiago/privacy` as the Google Play Console privacy policy URL for Sortiago.

The included `.htaccess` keeps `index.html` as the directory index and redirects HTTP traffic to HTTPS when Apache rewrite support is enabled by the hosting plan.

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
- The app privacy policy mentions the current Sortiago status conservatively: Google Play Billing is used, Google User Messaging Platform is used, the current release does not serve ads yet, and future versions may use Google AdMob rewarded or interstitial ads after consent where required.
- Main support email: `support@wallaroo.studio`.
