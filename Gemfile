# frozen_string_literal: true

source 'https://rubygems.org'

gemspec

gem "jekyll", '~> 4.1.1'
gem 'minima'

group :jekyll_plugins do
  gem 'jekyll-avatar'
  gem 'jekyll-mentions'
  gem 'jekyll-sitemap'
  gem 'jemoji'
  gem 'jekyll-feed'
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end