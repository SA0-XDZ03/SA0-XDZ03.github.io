source "https://rubygems.org"

# Specify the version of Jekyll to use
gem "jekyll", "~> 3.9"

# Specify the theme to use (minima is the default theme for GitHub Pages)
gem "minima", "~> 2.5"

# Use GitHub Pages gem to manage Jekyll and dependencies
gem "github-pages", group: :jekyll_plugins

# Other Jekyll plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Windows and JRuby do not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance booster for watching directories on Windows
#gem "wdm", "~> 0.1.1", platforms: [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]

# Required for running Jekyll
gem "webrick", "~> 1.8"

# Specify the hitchens-theme (if available on rubygems.org)
gem "hitchens-theme"
