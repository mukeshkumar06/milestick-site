# MileStick website

The public landing page for MileStick, served by GitHub Pages from the `main` branch, root folder
(https://mukeshkumar06.github.io/milestick-site/). One static page, no build step and no dependencies.

- `index.html`: the page (styles and the small script are inline).
- `assets/`: globe renders made with the app's own globe shader, the logo, favicons and the social preview image.
  App screens on the page are recreated with illustrative names and data; no real users appear.

## Early-access form
In `index.html`, set `EARLY_ACCESS_FORM_URL` (near the end of the file) to the Google Form link. While it is empty,
the early-access buttons scroll to the last section, which says the form is being set up.

## Preview locally
`python -m http.server` in this folder, then open http://localhost:8000.
