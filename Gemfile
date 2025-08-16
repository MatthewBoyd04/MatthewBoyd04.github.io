source "http://rubygems.org"

gem "jekyll", "~> 3.8"
gem "rack", "~> 1.6"
gem "webrick"
gem "kramdown-parser-gfm"

group :jekyll_plugins do
  gem "jekyll-feed"
  gem 'jekyll-admin', "0.9.0"
end

install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

gem "wdm", :install_if => Gem.win_platform?