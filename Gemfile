source "https://rubygems.org"

# Remove specific Jekyll version to let github-pages gem manage it
# gem "jekyll", "~> 4.3.4"

# GitHub Pages
gem "github-pages", group: :jekyll_plugins
gem "jekyll-remote-theme"

# Basic dependencies
gem "webrick"

# Other plugins
group :jekyll_plugins do
  gem "jekyll-feed"
end

# Windows and JRuby does not include zoneinfo files
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Windows specific
gem "wdm", "~> 0.1", platforms: [:mingw, :x64_mingw, :mswin]

# JRuby specific
gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]