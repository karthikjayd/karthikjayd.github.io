# frozen_string_literal: true

source "https://rubygems.org"

# Use GitHub Pages—includes Jekyll and its default plugins
gem "github-pages", group: :jekyll_plugins

# Allow remote_theme in Pages
gem "jekyll-remote-theme"

# Optional: HTML Proofer for link testing in CI
gem "html-proofer", "~> 5.0", group: :test

# Windows platform support
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
  gem "wdm", "~> 0.2.0"
end
