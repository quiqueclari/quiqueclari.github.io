# Quique Clari — academic website

The source pages are Quarto `.qmd` files. Shared navigation and settings are in
`_quarto.yml`; typography, colours, and layout are in `html/styles.scss`.

To preview locally without overwriting the existing `docs/` output:

```sh
quarto preview --profile preview
```

The preview is available at `http://localhost:22222/`. If that port is already
serving a preview, use `--port 22223`. To build without starting a server:

```sh
quarto render --profile preview
```

To prepare the GitHub Pages output in `docs/`, run `quarto render --no-clean`.
The preview profile is only for local review.

The publication list follows the full academic CV reviewed in October 2026.
Fonts are hosted locally, with their open licences in `html/fonts/`.

## Original template

This repository contains the template for the website tutorial at <https://www.marvinschmitt.com/blog/website-tutorial-quarto/>.

<p align="center">
  <img src="img/website_template_screenshot_1.png" width="45%">
&nbsp; &nbsp; &nbsp; &nbsp;
  <img src="img/website_template_screenshot_2.png" width="45%">
<br/><br/>
  <img src="img/website_template_screenshot_3.png" width="45%">
&nbsp; &nbsp; &nbsp; &nbsp;
  <img src="img/website_template_screenshot_4.png" width="45%">
</p>
