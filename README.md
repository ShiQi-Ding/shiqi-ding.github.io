# shiqi-ding.github.io

Personal academic website for Shiqi Ding, hosted on GitHub Pages at
<https://shiqi-ding.github.io>.

## Local development

Requires Ruby 3+, Jekyll, and Bundler.

```sh
jekyll serve
```

Open <http://127.0.0.1:4000/>. Jekyll auto-rebuilds on file changes.

## Editing content

Most updates only require touching the YAML files in `_data/`:

- `_data/main_info.yaml` — name, title, email, header social links
- `_data/news.yaml` — news items (newest first, MM/YYYY date format)
- `_data/publications.yaml` — papers, grouped by `type` (`journal`, `conference`,
  `under_review`); set `selected: y` to include in the "Selected" tab
- `_data/locations.yaml` — points on the Vitæ map (chronological order)
- `_data/teaching.yaml` — teaching items shown on the Teaching page

Page templates live in `_layouts/default.html` and the per-page `*.html` files
at the repo root. Shared partials are in `_includes/`.

## Credit

Built on the [Jekyll personal-site template by Martin Saveski](https://github.com/msaveski/www_personal).
