# frozen_string_literal: true

DECIDIM_VERSION = "0.16.1"

source "https://rubygems.org"

ruby "2.5.1"

gem "decidim", DECIDIM_VERSION

gem "puma", "~> 3.0"
gem "uglifier", ">= 1.3.0"

gem "savon", "~> 2.12.0"

gem "fog-aws"
gem "sentry-raven"
gem "sidekiq"

gem "faker", "~> 1.8"

gem "letter_opener_web", "~> 1.3.0"

group :development, :test do
  gem "decidim-dev", DECIDIM_VERSION
  gem "dotenv-rails"
  gem "pry-byebug", platform: :mri

  gem "factory_bot_rails"
  gem "rspec-rails"
end

group :development do
  gem "webmock"
  gem "listen", "~> 3.1.0"
  gem "rubocop"
  gem "spring"
  gem "spring-commands-rspec"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "web-console"
end
