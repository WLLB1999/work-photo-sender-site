# Work Photo Sender — public website

This is the separate **public static website** for the Work Photo Sender Android and Windows application. It contains no private app source code, Google tokens, API keys, or customer data.

## Deployment using GitHub Pages

This repository's root contains `index.html`, `privacy.html`, `terms.html`, and `style.css`.

To publish, go to **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, branch **main**, folder **/(root)** and Save. Once published, verify:

- https://wllb1999.github.io/work-photo-sender-site/
- https://wllb1999.github.io/work-photo-sender-site/privacy.html
- https://wllb1999.github.io/work-photo-sender-site/terms.html

Before adding these URLs to Google Auth Platform → Branding, verify they open publicly. For sensitive Gmail OAuth-scope verification, Google may require a domain you own and have verified through Search Console. A github.io URL does not guarantee compliance with Google's verified-domain requirement.

Review the privacy/terms text as application operator to confirm accuracy and contact procedures. This is a proposed policy, not legal advice.
