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
- `img/screens/`: three iPhone screens for the Meander page, status bar cropped, 600 wide.
- `img/instagram/`: five 1080 × 1350 posts made from the same screenshots, ready to upload. Both
  sets come from `shots.py` (kept out of the repo) over the raw screenshots; reshoot and rerun when
  the archive holds children's drawings as well as ceramics.

The brand kit lives in the Meander repository (`medea-creek-meander/docs/brand/README.md`). Copy
files from there; do not redraw them here.

## Before the Instagram wave

The iPhone button is the TestFlight public link (capped at 50 testers in App Store Connect; raise
the cap there if it fills). The web button is the Tally intake form (name, email, platform, how
you heard; responses are emailed to hello@medeacreekarts.org). Weekly: export the new responses,
make a sign-up code for each web tester on the admin app's Platform page, and email each one the
code and the dev link.

## At launch

Change every `dev.medeacreekarts.org` link on `meander/index.html` to `app.medeacreekarts.org`, add
the App Store link, and remove the "Testing now" and "What to test" sections. Swap the screens in `img/screens/` for
the store screenshots when they exist.
