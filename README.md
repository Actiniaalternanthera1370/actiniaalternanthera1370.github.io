# Cyber Mindscape Portfolio — Version 2.2 — Recruiter SEO

This is a static, privacy-conscious GitHub Pages portfolio for `ryszard-bialach2.com`.

## What is included

- Animated entry experience
- Lightweight animated network background
- Interactive cybersecurity capability map
- Evidence-based project case files
- Certification / education signals
- Selected professional experience
- Public-disclosure boundary section
- Recruiter-oriented contact path
- Responsive layout and reduced-motion support
- No third-party JavaScript libraries

## Publish

Upload these files to the root of `rbcommoncents.github.io`:

- `index.html`
- `styles.css`
- `app.js`
- `.nojekyll`
- `CNAME`

Keep GitHub Pages configured to:

- Source: Deploy from a branch
- Branch: `main`
- Folder: `/ (root)`
- Custom domain: `ryszard-bialach2.com`
- Enforce HTTPS: enabled

## Add LinkedIn

Open `app.js` and edit the `PROFILE` object near the top:

```js
const PROFILE = {
  linkedin: "https://www.linkedin.com/in/YOUR-PROFILE/",
  github: "https://github.com/rbcommoncents"
};
```

If `linkedin` is left blank, the LinkedIn button remains hidden.

## Public-safety design

The site intentionally does not publish:

- phone number
- home address or exact personal location
- certification IDs
- credentials or API secrets
- private lab IP addresses
- private hostnames
- full internal topology
- complete scrape-ready employment history

Important: no public webpage can be made impossible to scrape. The practical control is to avoid placing sensitive information in the public HTML in the first place.

## Suggested next additions

1. Dedicated NetFlow research page
2. Sanitized Maproom architecture diagram
3. Resume-on-request professional contact workflow
4. Project screenshots
5. Open Graph social preview image
6. Optional case-study pages under `/projects/`


## v2.1 reliability fix

This release fixes a rendering condition where the capability map and its
evidence panel could remain invisible because the scroll-reveal observer had
not promoted the large elements from `opacity: 0`.

The capability map is now critical content and always renders. Scroll animation
is treated as progressive enhancement, with a timed fallback for every other
reveal element. Hash navigation is also restored after the entry overlay closes.


## v2.2 recruiter SEO layer

Added recruiter-intent metadata, canonical URLs, ProfilePage/Person JSON-LD, natural target-role language, three crawlable cybersecurity case-study pages, internal links, robots.txt, sitemap.xml, and a public-safe security.txt. No phone number, exact location, credential IDs, private infrastructure, or secrets are included.
