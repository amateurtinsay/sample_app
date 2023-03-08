# source "https://rubygems.org"
# git_source(:github) { |repo| "https://github.com/#{repo}.git" }

# ruby "3.0.2"

# # Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
# gem "rails", "~> 7.0.4", ">= 7.0.4.2"

# # The original asset pipeline for Rails [https://github.com/rails/sprockets-rails]
# gem "sprockets-rails"

# # Use postgresql as the database for Active Record
# gem "pg", "~> 1.1"

# # Use the Puma web server [https://github.com/puma/puma]
# gem "puma", "~> 5.0"

# # Use JavaScript with ESM import maps [https://github.com/rails/importmap-rails]
# gem "importmap-rails"

# # Hotwire's SPA-like page accelerator [https://turbo.hotwired.dev]
# gem "turbo-rails"

# # Hotwire's modest JavaScript framework [https://stimulus.hotwired.dev]
# gem "stimulus-rails"

# # Build JSON APIs with ease [https://github.com/rails/jbuilder]
# gem "jbuilder"

# # Use Redis adapter to run Action Cable in production
# # gem "redis", "~> 4.0"

# # Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# # gem "kredis"

# # Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# # gem "bcrypt", "~> 3.1.7"

# # Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

# # Reduces boot times through caching; required in config/boot.rb
# gem "bootsnap", require: false

# # Use Sass to process CSS
# # gem "sassc-rails"

# # Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# # gem "image_processing", "~> 1.2"

# group :development, :test do
#   # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
#   gem "debug", platforms: %i[ mri mingw x64_mingw ]
# end

# group :development do
#   # Use console on exceptions pages [https://github.com/rails/web-console]
#   gem "web-console"

#   # Add speed badges [https://github.com/MiniProfiler/rack-mini-profiler]
#   # gem "rack-mini-profiler"

#   # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
#   # gem "spring"
# end

# group :test do
#   # Use system testing [https://guides.rubyonrails.org/testing.html#system-testing]
#   gem "capybara"
#   gem "selenium-webdriver"
#   gem "webdrivers"
# end

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.2'

gem 'rails',                      '7.0.4.2'
gem 'image_processing',           '1.9.3'
gem 'mini_magick',                '4.9.5'
gem 'active_storage_validations', '0.8.9'
gem 'bcrypt',                     '3.1.13'
gem 'faker',                      '2.11.0'
gem 'will_paginate',              '3.3.0'
gem 'bootstrap-will_paginate',    '1.0.0'
gem 'bootstrap-sass',             '3.4.1'
gem 'puma',                       '5.3.1'
gem 'sass-rails',                 '6.0.0'
gem 'webpacker',                  '5.4.0'
gem 'turbolinks',                 '5.2.1'
gem 'jbuilder',                   '2.10.0'
gem 'bootsnap',                   '1.7.2', require: false

group :development, :test do
  gem 'sqlite3', '1.4.2'
  gem 'byebug',  '11.1.3', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console',        '4.1.0'
  gem 'rack-mini-profiler', '2.3.1'
  gem 'listen',             '3.4.1'
  gem 'spring',             '2.1.1'
end

group :test do
  gem 'capybara',                 '3.35.3'
  gem 'selenium-webdriver',       '3.142.7'
  gem 'webdrivers',               '4.6.0'
  gem 'rails-controller-testing', '1.0.5'
  gem 'minitest',                 '5.11.3'
  gem 'minitest-reporters',       '1.3.8'
  gem 'guard',                    '2.16.2'
  gem 'guard-minitest',           '2.4.6'
end

group :production do
  gem 'pg',         '1.2.3'
  gem 'aws-sdk-s3', '1.87.0', require: false
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# Uncomment the following line if you're running Rails
# on a native Windows system:
# gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]