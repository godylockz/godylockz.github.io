source "https://rubygems.org"

# Minima is a one-size-fits-all Jekyll theme for writers.
# https://github.com/jekyll/minima
gem "minima"

# A Jekyll plugin to cache the rendering of Liquid includes
# https://github.com/benbalter/jekyll-include-cache
gem "jekyll-include-cache"

# A simple Ruby Gem to bootstrap dependencies for setting up and maintaining a local Jekyll environment in sync with GitHub Pages 
# https://github.com/github/pages-gem
gem "github-pages", group: :jekyll_plugins

# TZInfo::Data - Timezone Data for TZInfo
# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# https://github.com/tzinfo/tzinfo-data
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Windows Directory Monitor (WDM) is a threaded directories monitor for Windows. 
# Performance-booster for watching directories on Windows
# https://github.com/Maher4Ever/wdm/
gem "wdm" if Gem.win_platform?

# If you have any plugins, put them here!
group :jekyll_plugins do
  # A Jekyll plugin to generate an Atom (RSS-like) feed of your Jekyll posts 
  # https://github.com/jekyll/jekyll-feed
  gem "jekyll-feed"
end