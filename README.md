# czye17.github.io

Source for [czye17.github.io](https://czye17.github.io/), built with [Jekyll](https://jekyllrb.com/) and GitHub Pages.

## Editing content

Most updates only touch the files in `_data/`:

| File | Contents |
| --- | --- |
| `research.yml` | Publications, newest first (no `year` = preprint) |
| `coauthors.yml` | Co-author homepages, keyed by name |
| `events.yml` | News items; the three most recent appear on the home page |
| `teaching.yml` | Teaching positions, newest first |
| `navigation.yml` | Sidebar nav links |

Site-wide settings (email, profile links, "last updated" date, analytics ID) are in `_config.yml`.
The bio is in `index.html`; all styling is in `assets/css/main.css`.

## Running locally

Install Ruby and Jekyll ([instructions](https://jekyllrb.com/docs/installation/)), then:

```sh
bundle install
bundle exec jekyll serve
```

and open <http://localhost:4000>.

## Acknowledgements

The original template was created by [Sharon Zhang](https://sxzhang25.github.io).
