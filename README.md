# Personal Website

Source for [dylanlosey.com](https://dylanlosey.com/), built with [Jekyll](https://jekyllrb.com/) and published by GitHub Pages from the `master` branch. GitHub builds the site itself on every push, so the generated `_site/` folder is not committed.

## Preview locally

Requires Ruby 3 and Bundler.

```bash
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000/>.

## Keep the local gems in step with GitHub Pages

```bash
bundle update github-pages
```

## Layout

- `index.html`, `teaching.html`, `contact.html` are the real pages.
- `lab.html`, `publications.html`, `CV.html` exist only to appear in the navigation; each redirects to its target.
- `_includes/`, `_layouts/`, `_sass/` hold the (trimmed) Pixyll theme.
- `pdfs/` holds course evaluations linked from the teaching page.
