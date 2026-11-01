# medeacreekarts.org

The Medea Creek Arts Collective's site, and the Marketing URL for Meander. Static HTML on GitHub
Pages; `CNAME` sets the domain.

## Layout

- `index.html`: the Collective.
- `meander/index.html`: Meander and the beta. The App Store, TestFlight and the app's About card all
  link to this site, so this page is what a tester finds.
- `styles.css`: one stylesheet for both pages.
- `img/`: `social-card.png` (the site's link preview, made by hand from the brand kit's fonts and
  palette), `meander-card.png` and `meander-lockup.svg` (copied from the Meander repository,
  `docs/brand/`). `favicon.svg` is the brand kit's `mark-cobalt.svg`.

The brand kit lives in the Meander repository (`medea-creek-meander/docs/brand/README.md`). Copy
files from there; do not redraw them here.

## Before the Instagram wave

The two beta buttons on `meander/index.html` are `mailto:` links until these exist:

1. **TestFlight public link.** In App Store Connect, TestFlight, the external group: turn on the
   public link and cap it at about 50 testers. Replace the iPhone button's `href` with it.
2. **An intake form** (Tally or Google Forms: name, email, platform, how you heard). Replace the web
   button's `href` with it, and issue sign-up codes from the Platform page in a weekly batch.

## At launch

Change every `dev.medeacreekarts.org` link on `meander/index.html` to `app.medeacreekarts.org`, add
the App Store link, and remove the "Testing now" and "What to test" sections. Add three store
screenshots above "Our promise" when they exist.
