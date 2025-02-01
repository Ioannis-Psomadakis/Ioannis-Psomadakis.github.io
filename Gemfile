source "https://rubygems.org"

# Use GitHub Pages Jekyll version instead of default Jekyll
gem "github-pages", group: :jekyll_plugins

# gem "minimal-mistakes-jekyll"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-paginate", "~> 1.1"
  gem "jekyll-include-cache", "~> 0.2.1"
  gem "jekyll-sitemap", "~> 1.4"
  gem "jekyll-archives", "~> 2.3"
  gem "jekyll-seo-tag", "~> 2.8"
end

# Windows and JRuby fixes
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
