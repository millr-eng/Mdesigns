# M Designs & Drafting — proposed website rebuild

A lightweight, static, accessible site for GitHub Pages and the `m-designs.uk` domain. No build dependencies.

## Review before publishing

1. **Confirm or remove** proposed `From £60` and `From £90` prices on `pricing.html`, and check VAT wording. They are draft suggestions, not authorised business rates.
2. Review the About page for accurate qualifications and business statements.
3. Replace illustrative portfolio drawings with permitted real examples; the EV cable guide model is retained from the current site.
4. Confirm `Mdesigns.engineering@gmail.com` remains the preferred public contact.
5. Confirm insurance, employer conflicts, terms and privacy policies where applicable.
6. Confirm you're ready for Google indexing: `robots.txt` **now allows crawling** (the existing site blocked all crawlers).

## Publishing

Back up the original repository first. Upload the files in this folder to the repository root and keep any existing `/images` or `/projects` assets needed elsewhere. In GitHub Settings → Pages, continue deploying from `main` / root. Keep existing DNS settings.

## Structure

- `index.html` — Homepage
- `services.html` — Service details
- `pricing.html` — Indicative pricing (requires approval)
- `work.html` — Illustrative examples + existing model
- `about.html` — About
- `contact.html` — Quote enquiry via email
- `styles.css`, `script.js` — Shared layout and mobile navigation
- `robots.txt`, `sitemap.xml`, `CNAME` — Search and domain configuration

No contact data is collected by the site. The external Sketchfab model iframe may use third-party storage/cookies; consider a privacy notice and consent approach as appropriate.
