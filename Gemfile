# frozen_string_literal: true

source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.0.2"

gem "rails", "~> 7.0.2", ">= 7.0.2.4"
gem "sprockets-rails"
gem "pg", "~> 1.1"
gem "puma", "~> 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "tzinfo-data", platforms: %i[mingw mswin x64_mingw jruby]
gem "bootsnap", require: false

group :development, :test do
  gem "debug", platforms: %i[mri mingw x64_mingw]
  gem "dotenv-rails", require: "dotenv/rails-now"
  gem "rubocop"
  gem "rubocop-faker", require: false
  gem "rubocop-performance", require: false
  gem "rubocop-rails", require: false
  gem "rubocop-rake", require: false
  gem "rubocop-rspec", require: false
  gem "rubocop-thread_safety", require: false
  gem 'rspec-rails', '~> 6.0.0.rc1'
end

group :development do
  gem "web-console"
end
