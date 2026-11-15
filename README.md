# thanosandr.github.io

Source of my personal website, [thanosandr.github.io](https://thanosandr.github.io): who I am, my experience, selected projects and my CV.

Built with Jekyll and served by GitHub Pages, using a customized copy of the [Prologue](https://html5up.net/prologue) theme by HTML5 UP ([Jekyll port](https://github.com/chrisbobbe/jekyll-theme-prologue) by Chris Bobbe).

## Editing

- Homepage sections live in `_sections/` (ordered by `order:` in the front matter).
- Project pages are the top-level `*.html` files (`/spkrec`, `/sensors`, ...).
- Site title, links and social profiles are in `_config.yml`.
- `assets/images/cv.pdf` is a copy of the PDF built from my LaTeX CV repository; replace it whenever the CV changes.

## Running locally

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.

## License

Theme: [CC BY 3.0](https://html5up.net/license) (HTML5 UP); see [LICENSE.md](LICENSE.md).
