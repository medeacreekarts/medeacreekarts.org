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
- `img/instagram/`: seven 1080 × 1350 posts made from the same screenshots, ready to upload, and
  `README.md` there with the captions and slide order for the first two posts. Both sets come from
  `shots.py` (kept out of the repo, in `~/Downloads/meander_screens/` with the raw screenshots);
  reshoot and rerun when the archive holds children's drawings as well as ceramics.

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

## Handoff, 2026-11-02

Everything below is on `main` and live at https://medeacreekarts.org (GitHub Pages deploys in about
a minute; the push is the deploy).

Done:
- The home page names Meander and links to `/meander/`; favicon, link preview card and JSON-LD fixed.
- `/meander/`: the lockup, three app screens, the promise, "Testing now" with two panels (the
  TestFlight public link, capped at 50; the Tally form at https://tally.so/r/vXMLgQ for a web code),
  what to test, questions, and links to the dev support, privacy and terms pages.
- The Instagram kit and the captions for the introduction post and the tester call
  (`img/instagram/README.md`). Nothing has been posted yet.

Next, in order:
1. Post the introduction, then the tester call, with the bio link set to
   https://medeacreekarts.org/meander/. The Meander repository's gates come first: the lawyer's
   review of the Terms and Privacy Policy, and a week of the report-only CSP with no violation.
2. Each week, export the new Tally responses, make a code per web tester on the admin app's
   Platform page, and email the code and the dev link.
3. When the archive holds children's drawings, reshoot, rerun `shots.py`, and commit the new
   `img/screens/` and `img/instagram/` files. The Friends piece still shows "Not set" fields.
4. At launch, the "At launch" section above.

Checks that were not run: no browser screenshot of the pages was taken in the last session (the
browser tools were unavailable). Ryan checked the Meander page on mobile Safari and approved it.
