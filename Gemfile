source "https://rubygems.org"

# Build with the same gems and versions GitHub Pages uses, so a local
# `bundle exec jekyll serve` matches the live site.
# To upgrade, run `bundle update github-pages`.
gem "github-pages", group: :jekyll_plugins

# Plugins used by this site (all are part of the GitHub Pages gem set)
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-seo-tag"
end

# Needed to run `jekyll serve` on Ruby 3.0 and later
gem "webrick", "~> 1.8"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0" if Gem.win_platform?
