# frozen_string_literal: true

source "https://rubygems.org"

# This site is built and deployed by our own GitHub Actions workflow
# (configure-pages -> jekyll build -> upload-pages-artifact -> deploy-pages),
# so we use standalone Jekyll instead of the legacy `github-pages` gem.
# Using `github-pages` here pulled in jekyll-github-metadata, which crashed
# the build via jekyll-remote-theme (undefined method `global_munger`).
gem "jekyll", "~> 4.3"

# Stdlib gems that newer Rubies no longer bundle by default (harmless on older).
gem "csv"
gem "rexml", ">= 3.2.7"

group :jekyll_plugins do
  gem "jekyll-remote-theme"
  gem "jekyll-seo-tag"
end
