source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.5'
gem 'active_model_serializers', '~> 0.10.0'
gem 'foreman', '~> 0.86.0'
gem 'rails', '~> 6.0.0'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '>= 3.11'
gem 'will_paginate'
gem 'bcrypt', '~> 3.1', '>= 3.1.13'
gem 'redis', '~> 4.1', '>= 4.1.3'

gem 'bootsnap', '>= 1.1.0', require: false



group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'faker'
  gem 'pry'
  gem 'pry-rails'
  gem 'rspec-rails', '~> 3.8'
  gem 'rubocop', '~> 0.70.0', require: false
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem "better_errors"
  gem "binding_of_caller"
end

group :test do
  gem 'database_cleaner'
  gem 'factory_bot_rails'
  gem 'guard-rspec', require: false
  gem 'shoulda-matchers'
  gem 'simplecov', require: false
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
