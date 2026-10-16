# maximevdk.github.io

Personal site and app legal pages, built by GitHub Pages with Jekyll.

- Apps on the home page: `_data/apps.yml` (set `app_store` once an app is live)
- Open-source projects: `_data/projects.yml`
- Legal pages: `<app-slug>/privacy-policy.md` and `<app-slug>/terms-of-service.md`

## Preview locally

Needs Ruby 3.3 (the macOS system Ruby is too old, and Ruby 3.4+ is too new for the Jekyll version GitHub Pages uses):

```sh
brew install ruby@3.3
export PATH="/opt/homebrew/opt/ruby@3.3/bin:$PATH"
bundle install
bundle exec jekyll serve --livereload
```

Then open http://localhost:4000.
