# frozen_string_literal: true
source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?('/')
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 5.1.4'
gem 'devise'
gem 'slim-rails'
gem 'mysql2', '>= 0.3.18', '< 0.5'
gem 'puma', '~> 3.7'
gem 'dotenv-rails'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'

# javascript
gem 'uglifier', '>= 1.3.0'
gem 'webpacker'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  gem 'seedbank'
  gem 'factory_girl_rails'
  gem 'faker'
  gem 'rspec-rails', '~> 3.6'
  gem 'rspec_junit_formatter'
  gem 'rails-controller-testing'

  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
  gem 'rubocop', '~> 0.52.0', require: false
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end
