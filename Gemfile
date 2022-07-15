source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"

gem "rails", "~> 7.0.3", ">= 7.0.3.1"

gem "sprockets-rails"
gem 'pg', '>= 0.18', '< 2.0'
gem "puma", "~> 5.0"
gem "importmap-rails"

gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "redis", "~> 4.0"
gem 'devise'
gem 'devise-jwt'
gem 'fast_jsonapi'
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]
gem "bootsnap", require: false

group :development, :test do
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end

group :development do
  gem "web-console"
end

group :test do
  # Use system testing [https://guides.rubyonrails.org/testing.html#system-testing]
  gem 'faker'
  gem 'factory_girl_rails'
  gem 'rspec-rails', '~> 5.0.0'

  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end
