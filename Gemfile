# frozen_string_literal: true

source 'https://rubygems.org'

gem 'activerecord', '~> 4.2', '>= 4.2.6', require: 'active_record'
gem 'aws-record'
gem 'json'
gem 'puma'
gem 'rack'
gem 'rack-contrib'
gem 'rake'
gem 'require_all'
gem 'rubysl-base64'
gem 'sinatra'
gem 'sinatra-activerecord', require: 'sinatra/activerecord'
gem 'sinatra-contrib', require: false
gem 'sinatra-cross_origin', '~> 0.3.1'
gem 'sqlite3', '~> 1.3.6'

group :development do
  gem 'faker', git: 'https://github.com/stympy/faker.git', branch: 'master'
  gem 'shotgun'
end

group :test do
  gem 'capybara'
  gem 'capybara-screenshot'
  gem 'cucumber'
  gem 'database_cleaner'
  gem 'mocha'
  gem 'rack-test'
  gem 'rspec'
  gem 'rubocop', require: false
  gem 'selenium-webdriver'
  gem 'test-unit'
end
