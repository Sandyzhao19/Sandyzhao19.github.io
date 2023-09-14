source "https://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
gem "jekyll", "~> 3.8"

gem "jekyll-theme-hydejack"

# A JavaScript runtime for ruby that helps with running the katex gem above.
gem "duktape"

# Fixes `jekyll serve` in ruby 3
gem "webrick"

group :jekyll_plugins do
  gem "jekyll-default-layout"
  gem "jekyll-feed"
  gem "jekyll-optional-front-matter"
  gem "jekyll-paginate"
  gem "jekyll-readme-index"
  gem "jekyll-redirect-from"
  gem "jekyll-relative-links"
  gem "jekyll-seo-tag"
  gem "jekyll-sitemap"
  gem "jekyll-titles-from-headings"
  gem "jekyll-include-cache"

  # Non-Github Pages plugins:
  gem "jekyll-last-modified-at"
  gem "jekyll-compose"
end

gem "kramdown-parser-gfm"

gem 'wdm' if Gem.win_platform?
gem "tzinfo-data" if Gem.win_platform?

gem "github-pages", group: :jekyll_plugins
gem "jekyll-include-cache", group: :jekyll_plugins