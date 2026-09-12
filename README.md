# Suntrail Rangers support website

Prepared for the intended public repository **samweelsedrak-alt/suntrail-rangers-support**. Creating or publishing that repository is a separate step; these files do not establish that the site is live.

The page content is ready for review and publication. The game page accurately says **Preparing for release** and contains no App Store badge, download link, or claim that the game is publicly available. The privacy policy is effective **12 September 2026**.

## Publicly deployable files

Only these seven files belong in the support repository:

- `index.html` — game and release-status page.
- `support.html` — public support contact and gameplay help.
- `privacy.html` — privacy policy.
- `styles.css` — local responsive styles.
- `app-icon.png` — local Suntrail Rangers icon.
- `.nojekyll` — serve the static files without Jekyll processing.
- `README.md` — this public deployment description.

They contain the public contact **samweel.sedrak@gmail.com** and copyright **© 2026 @samweel_sedrak**. Do not add game source, native exports, builds, validation reports, signing material, private account information, or review-contact records to this public repository.

## Intended Pages configuration

Use the repository's `main` branch and `/ (root)` as the GitHub Pages publishing source. No build tools, package installation, scripts, forms, remote fonts, analytics, or environment secrets are required. All local links are relative so they work under a project-site path.

After a successful deployment, verify these intended URLs before entering them into App Store Connect:

- Game: `https://samweelsedrak-alt.github.io/suntrail-rangers-support/`
- Support: `https://samweelsedrak-alt.github.io/suntrail-rangers-support/support.html`
- Privacy: `https://samweelsedrak-alt.github.io/suntrail-rangers-support/privacy.html`

The policy distinguishes the offline game from voluntary support email, Apple's TestFlight service, operating-system backups, and GitHub Pages hosting. GitHub's IP-address security logging is documented in [GitHub Pages data collection](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages#data-collection); beta data handling is documented in [TestFlight & Privacy](https://www.apple.com/legal/privacy/data/en/test-flight/). These official pages were checked on 12 September 2026.

When the game becomes publicly available, update the release-status text and add only a verified App Store product link. Revisit the policy before adding any service that changes data handling.
