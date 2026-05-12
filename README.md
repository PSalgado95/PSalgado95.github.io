# Pedro Veiga Salgado Website

This repository contains the source for [psalgado95.github.io](https://psalgado95.github.io/), a Jekyll site based on the Academic Pages theme.

## Main Content

- Homepage: `_pages/about.md`
- Research page: `_pages/research.md`
- CV page: `_pages/cv.md`
- CV PDF: `files/Pedro_Salgado_CV.pdf`
- Site configuration: `_config.yml`
- Navigation: `_data/navigation.yml`

## Common Updates

To update homepage text or news, edit `_pages/about.md`.

To update the research summary or presentation list, edit `_pages/research.md`.

To update the downloadable CV, replace `files/Pedro_Salgado_CV.pdf` with a new PDF using the same filename.

## Local Preview

If Ruby and Bundler are installed, run:

```bash
bundle exec jekyll serve -l -H localhost
```

Then open `http://localhost:4000`.