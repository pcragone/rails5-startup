source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'active_type'
gem 'autoprefixer-rails'
gem 'bootsnap', require: false
gem 'bootstrap'
gem 'cancancan'
gem 'coffee-rails'
gem 'devise'
gem 'dotenv-rails'
gem 'haml-rails'
gem 'jquery-rails'
gem 'marco-polo'
gem 'normalize-rails'
gem 'pg'
gem 'pgcli-rails'
gem 'puma'
gem 'rails'
gem 'sass-rails'
gem 'secure_headers'
gem 'sidekiq'
gem 'turbolinks'
gem 'uglifier'
# gem 'jbuilder'
# gem 'bcrypt'
# gem 'friendly_id'

group :development, :test do
  gem 'byebug', platform: :mri
  gem 'letter_opener'
  gem 'pry'
  gem 'guard-livereload', require: false
  gem 'psych'
  gem 'faker'
end

group :development do
  gem 'annotate'
  gem 'awesome_print'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'brakeman', require: false
  gem 'bundler-audit'
  gem 'letter_opener'
  gem 'listen'
  gem 'guard'
  gem 'guard-livereload'
  gem 'guard-rails', require: false
  gem 'guard-rspec', require: false
  gem 'guard-zeus'
  gem 'overcommit'
  gem 'rack-livereload'
  gem 'rubocop'
  gem 'simplecov'
  gem 'xray-rails'
end

group :test do
  gem 'shoulda-matchers', git: 'https://github.com/thoughtbot/shoulda-matchers.git', branch: 'rails-5'
  gem 'capybara'
  gem 'poltergeist'
  gem 'factory_girl_rails'
  gem 'database_cleaner'
  gem 'rails-controller-testing'
  gem 'selenium-webdriver'
  gem 'rspec-rails'
end
