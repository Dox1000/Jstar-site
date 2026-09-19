# jstar-site

Static pages for jstar.tv, served by GitHub Pages.

- `index.html` — landing page
- `radar-privacy/` — privacy policy for a private internal tool

## Notes

This repository is public, because GitHub Pages will not serve a private
one on a free plan. Assume anything committed here is world-readable, and
keep operational detail out of it — including in this file, which Jekyll
renders as the site's homepage when no `index.html` exists.

`CNAME` binds the site to the apex domain; removing it drops the custom
domain and every published URL under it stops resolving.
