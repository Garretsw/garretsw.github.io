# garretsw.github.io

Garret Wagers' personal site, built with Jekyll using the remote theme [`garretsw/minimal-mistakes`](https://github.com/garretsw/minimal-mistakes) (a fork of Minimal Mistakes).

## Local development

```bash
bundle install             # install Ruby gems (first run / after Gemfile changes)
bundle exec jekyll serve   # build and serve locally at http://localhost:4000
bundle exec jekyll build   # build the static site into _site/
```

`_config.yml` is not reloaded by `jekyll serve` — restart the server after editing it.

## Structure

- `_pages/` — About, Education, Projects, and 404
- `_data/navigation.yml` — top nav bar entries
- `index.html` — homepage content
- `assets/images/` — images referenced by pages/config

## Troubleshooting

- [Jekyll Forum](https://talk.jekyllrb.com/) / [StackOverflow](https://stackoverflow.com/questions/tagged/jekyll)
- [Ruby 101](https://jekyllrb.com/docs/ruby-101/)
- [Setting up a Jekyll site with GitHub Pages](https://jekyllrb.com/docs/github-pages/)
