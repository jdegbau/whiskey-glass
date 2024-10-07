source "https://rubygems.org"

# Uncomment the github-pages gem and remove the jekyll gem
gem "github-pages", group: :jekyll_plugins

# This is the default theme for new Jekyll sites. You can keep using minima or choose another theme.
gem "minima", "~> 2.5"

# Add any plugins here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", platforms: [:mingw, :x64_mingw, :mswin]
