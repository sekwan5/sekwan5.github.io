# frozen_string_literal: true

source "https://rubygems.org"

# GitHub Pages와 Jekyll 사용을 위한 gem 추가
gem "github-pages", group: :jekyll_plugins
gem "jekyll-remote-theme"

# Chirpy 테마 사용을 위한 gem 추가
gem "jekyll-theme-chirpy"

gemspec

gem "html-proofer", "~> 5.0", group: :test

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem 'wdm', '>= 0.2.0' if Gem.win_platform?

# 추가 Jekyll 플러그인
group :jekyll_plugins do
  gem "jekyll-paginate"
  gem "jekyll-sitemap"
  gem "jekyll-gist"
  gem "jekyll-feed"
  gem "jemoji"
  gem "jekyll-include-cache"
  gem "jekyll-algolia"
end
