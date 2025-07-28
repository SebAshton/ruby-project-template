# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.2.2'

# Use postgresql as the database for Active Record
gem 'pg', '~> 1.6'

group :development, :test do
  gem 'byebug'
  gem 'dotenv'
  gem 'factory_bot'
  gem 'ffaker'
  gem 'pry-byebug'
  # gem 'pry-rails'
  gem 'rspec-collection_matchers'
  gem 'rspec-its'
  gem 'rspec-json_expectations'
  # gem 'rspec-rails'
  gem 'rspec'
  gem 'rubocop', require: false
  gem 'rubocop-performance', require: false
  # gem 'rubocop-rails', require: false
  gem 'rubocop-rspec'
end

group :test do
  gem 'capybara'
  gem 'selenium-webdriver'
  gem 'webdrivers'
end
