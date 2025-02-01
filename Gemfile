source "https://rubygems.org"

gem 'csv'

# Ensure compatibility with dependencies
gem 'public_suffix', '4.0.7'

# Jekyll version compatible with Liquid 4.0.4
gem "jekyll", "~> 4.2.0"

# Jekyll plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.15"
  gem "jekyll-paginate", "~> 1.1"
  gem "jekyll-sitemap", "~> 1.4"
  gem "jekyll-seo-tag", "~> 2.8.0"
  gem "jekyll-archives", "~> 2.3"
  gem "jekyll-include-cache", "~> 0.2.1"
end

# Ensure the correct version of jemoji
gem "jemoji", "= 0.12.0"

# Optional plugins
gem "jekyll-commonmark", "~> 1.0"

# Compatibility for Windows
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

# Liquid version as required
gem "liquid", "4.0.4"

# Add webrick for compatibility with Jekyll
gem "webrick", "~> 1.7"
