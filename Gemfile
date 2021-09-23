# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.1'

gem 'bootsnap', '>= 1.4.4', require: false
gem 'devise_token_auth', '~> 1.1.5'
gem 'pg', '~> 1.1'
gem 'puma', '~> 5.0'
gem 'rails', '~> 6.1.4'

group :development, :test do
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'factory_bot_rails'
  gem 'faker', '2.19.0'
  gem 'rspec-rails', '~> 5.0.0'
  gem 'rubocop', '~> 1.21', require: false
  gem 'rubocop-rspec', '~> 2.5.0'
end

group :development do
  gem 'letter_opener', '~> 1.7.0'
  gem 'listen', '~> 3.3'
  gem 'spring'
end

group :test do
  gem 'shoulda-matchers', '~> 5.0.0'
  gem 'simplecov', '~> 0.21.2', require: false
end

# Uncomment the following line if you're running on a native Windows system
# gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
