# Homepage

Personal academic homepage for `lirj233`, built with the Academic Pages Jekyll template and hosted on GitHub Pages.

## Site URL

This repository is configured as a project page:

- Repository: `lirj233/homepage`
- URL: `https://lirj233.github.io/homepage/`
- Jekyll `url`: `https://lirj233.github.io`
- Jekyll `baseurl`: `/homepage`

If this repository is renamed to `lirj233.github.io`, update `_config.yml` by setting `baseurl` to an empty string.

## Main Files

- `_config.yml`: site title, URL, author sidebar, social/profile links
- `_data/navigation.yml`: top navigation
- `_pages/about.md`: homepage content
- `_pages/publications.html`: publications list page
- `_pages/cv.md`: CV page
- `_publications/`: one Markdown file per publication
- `files/`: PDFs, slides, BibTeX, CV attachments
- `images/profile.png`: sidebar profile photo

## Local Preview

Use Ruby 3.x. The macOS system Ruby 2.6 is too old for the current GitHub Pages dependency stack.

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

Then open `http://localhost:4000/homepage/`.

## Next Content Pass

See `CONTENT_GUIDE.md` for the profile details needed to finish the site.
