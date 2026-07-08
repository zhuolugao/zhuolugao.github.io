source "https://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!

# Use native Jekyll for local development. The github-pages meta-gem pulls in
# extra themes that can interfere with this site's local Sass imports.
# gem "github-pages", group: :jekyll_plugins

# If you want to use Jekyll native, uncomment the line below.
# To upgrade, run `bundle update`.

gem "jekyll", "3.9.5"
gem "kramdown-parser-gfm"

# Optional Windows file watcher. Disabled because wdm 0.1.1 no longer builds
# reliably with current RubyInstaller/DevKit toolchains.
# gem "wdm", "~> 0.1.0" if Gem.win_platform?

# adding this fixes the issue
gem 'tzinfo'
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw]

# If you have any plugins, put them here!
group :jekyll_plugins do
  # gem "jekyll-archives"
  gem "jekyll-paginate"
  gem "jekyll-feed"
  gem "jekyll-gist"
  gem "jekyll-redirect-from"
  gem 'jekyll-sitemap'
  gem "jemoji"
  gem 'hawkins'
  gem "webrick", "~> 1.8"
end
