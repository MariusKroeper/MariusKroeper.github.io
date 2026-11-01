# Marius Kröper — academic website

Source for [mariuskroeper.github.io](https://mariuskroeper.github.io/), built with
Jekyll and the Academic Pages / Minimal Mistakes template.

## Main pages

- `_pages/about.md` — homepage
- `_pages/research.md` — **only** research-page source, published at `/research/`
- `_pages/cv.md` — CV link
- `_pages/contact.md` — contact details
- `_pages/publications.md` — forwards readers to the main research list

## Appearance

- `_sass/_research.scss` — typography and spacing for the research page
- `assets/css/main.scss` — imports `_research.scss` alongside theme styles
- `images/site-logo.png` — source for the website favicon

## Updating the live website

Clone the existing GitHub repository and modify its files. Do **not** create a
new repository or upload the ZIP archive as a single website file.

With Git installed:

```bash
git clone https://github.com/MariusKroeper/MariusKroeper.github.io.git
cd MariusKroeper.github.io

# Copy updated files into this directory and remove intentionally deleted files.
git status
git add -A
git commit -m "Clean academic website and consolidate research page"
git push origin master
```

The publishing branch in the downloaded archive was `master`. Confirm the
actual publishing source under Settings → Pages before pushing.

**Important:** The archive used for this cleanup is a snapshot. If the live
repository has newer changes, review differences before copying over them.

To test locally if Ruby/Bundler/Jekyll are installed:

```bash
bundle install
bundle exec jekyll serve
```

Then open `http://127.0.0.1:4000/`.

See GitHub → Actions for the deployment status after pushing.
