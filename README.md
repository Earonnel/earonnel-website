# EARONNEL. — Creator-style personal website

A custom-coded, responsive multi-page website for Prince Earonnel Del Mundo Arroyo. The approach is inspired by creator-style personal sites that combine a clear personal introduction, topic-based exploration, and a mixed-media journal. The design, copy, and illustrations here are original rather than a copy of Ali Abdaal's site.

## Pages
- `index.html` — homepage, full-name identity, topic cards, about summary, journal teasers, and public-link placeholders
- `about.html` — biography and interests
- `learn.html` — accountancy, business, and learning notes
- `cycling.html` — cycling and ride-journal home
- `running.html` — running and training-journal home
- `projects.html` — academic project portfolio
- `journal.html` — mixed-media archive with working Read / Photo / Watch filters
- `journal/why-im-building-earonnel.html` — first personal note
- `styles.css`, `script.js`, `assets/`, `favicon.svg` — design, interactivity, and original vector illustrations
- `robots.txt`, `sitemap-template.xml` — basic search-engine files/templates

## Design choices
- Warm beige, charcoal, and muted gold palette; serif editorial headings with clean sans-serif body copy
- Original vector visuals instead of a portrait (can be added later)
- Responsive navigation for mobile and desktop
- Explicit full name in homepage text, title, metadata, and `Person` structured data
- No invented ride metrics, race results, leadership titles, public profile URLs, or publication history

## Before publication
1. Review every biography statement and confirm the current education/status details.
2. Verify exact student leadership titles, scope, and dates before adding them.
3. Add your real LinkedIn URL and approved public academic-project links.
4. Add actual photos/videos and captions as you publish them. Use image alt text and credit third-party material where required.
5. Do not upload private class materials, classmates' personal information, your home address, or private identification/financial details.
6. Decide whether to use the free GitHub Pages URL first or purchase a domain such as `earonnel.com` if available. No availability claim is made here.

## Publish free with GitHub Pages
1. Sign in at https://github.com/ and create a public repository, for example `earonnel-website`.
2. Upload the **contents** of this folder into the repository root, preserving the `assets/` and `journal/` directories. Do not upload only the ZIP archive.
3. In repository **Settings → Pages**, select **Deploy from a branch**, choose `main` and `/(root)`, and save.
4. Open the URL shown by GitHub Pages and check desktop/mobile layouts and every navigation link.
5. If adding a custom domain later, configure it in Pages settings and follow the DNS instructions from your registrar. Enable HTTPS when available.

Official guide: https://docs.github.com/en/pages/quickstart

## Google Search setup
1. Once live, add the site to Google Search Console and verify ownership.
2. Inspect the live homepage and request indexing.
3. For a custom domain, replace the placeholder domain in `sitemap-template.xml`, save it as `sitemap.xml`, and submit it through Search Console. For a GitHub Pages project URL, build the sitemap using the exact deployed paths instead of using this placeholder.
4. Keep your full name consistent across the site and relevant public profiles. Google controls indexing and ranking; no particular result position or knowledge panel is guaranteed.

## Technical note
This is a static site. It uses local relative paths so it can work in a GitHub Pages project repository. Google Fonts are loaded externally; system fallbacks are defined if they cannot load.
