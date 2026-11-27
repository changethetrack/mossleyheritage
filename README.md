# Mossley Heritage Society's website

This site is built with Jekyll and published with GitHub Pages.

## Requirements

- Ruby 2.7.x. We reccomend using a version manager for this such as `rvm` or `rbenv`. Current version we are using is in `.ruby-version`.
  - [rvm](https://rvm.io/)
  - [rbenv](https://github.com/rbenv/rbenv)
    - [ruby-build](https://github.com/rbenv/ruby-build)
    - [rbenv-gemset](https://github.com/jf/rbenv-gemset) (optional)


## Local Development

To run the site locally:

```
git clone https://github.com/geeksforsocialchange/mossleyheritage.git
cd mossleyheritage
bundle install
bundle exec jekyll serve --livereload
```

There is a small test suite to test outgoing links, well formed HTML etc. To run it:

```
bundle exec rake test
```

## Deployment

Deployment happens automatically from the `master` branch. GitHub Pages sets the site URL and base path from its publishing settings. The [Pages settings](https://github.com/changethetrack/mossleyheritage/settings/pages) show the current public address.
