# Gembuk website

Static marketing website for https://gembuk.com. Production hosting stays on GitHub Pages. The IT support application at https://support.gembuk.com is separate and is not changed by this repository.

## Local preview

No package installation or build is needed. Serve this directory with a static HTTP server, for example `python3 -m http.server 4173`, then open http://localhost:4173.

Files: `index.html`, `styles.css`, `script.js`, `assets/fonts/`, `favicon.svg`, `site.webmanifest`, `robots.txt` and `sitemap.xml`. Preserve `CNAME` when deploying. Historical `backups/` content is unchanged.

## Brand assets

The existing Gembuk Support green (#185c43), rounded G brand mark, favicon and locally served DM Sans font are retained. Brand reference: https://support.gembuk.com, inspected 11 October 2026. Font license is included in `assets/fonts/OFL.txt`.

## Contact and privacy

All project enquiries open an email to admin@gembuk.com. There is no contact form, analytics, tracking script, cookie banner, third-party font request or booking widget. Illustrative workflows are labelled; there are no invented client logos, testimonials, results or certifications. Support links lead to the existing support site. Support-specific legal terms are not presented as broader project terms.

## Deployment

The owner approved the redesign, with the later illustrative example section removed. Original source baseline: `9dac9820ba06e6181eeff0782f9dd2ebdc567d99` on `main`.

1. Fetch current `main` and review any changes since the baseline.
2. Create a review branch based on the latest compatible main. Commit the changes normally; do not force-push or replace repository history.
3. Open a draft pull request. Confirm GitHub Pages still publishes this repository/root and keep `CNAME` unchanged.
4. After design approval and browser QA, merge the review into `main` through the normal repository workflow.
5. Verify the exact deployed commit, HTTPS, desktop and phone layout, navigation, email links, favicon, metadata and the existing support link at https://gembuk.com.
6. Roll back using a normal revert commit if needed. Do not alter DNS or the support deployment.

The private Sites review is only a review copy, not the production hosting destination. Its access settings must remain owner-only unless the owner requests a change.
