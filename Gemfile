source 'https://rubygems.org'
ruby '2.1.1'

# Framework & Bundler
gem 'rails', '4.1.0'
gem 'bundler', '1.6.2'

# Authentication, Authorization, & User Management
gem 'devise', '~> 3.2.4'
# gem 'pundit', '~> 0.2.3'

# Stylesheets, Views, & Templates
gem 'bootstrap-sass', '~> 3.1.1.1'
gem 'coffee-rails', '~> 4.0.0'
gem 'haml-rails', '~> 0.5.3'
gem 'sass-rails', '~> 4.0.3'
gem 'rails_layout', '~> 1.0.14'
# gem 'simple_form', '~> 3.0.2'
# gem 'will_paginate-bootstrap', '~> 1.0.0'

# JavaScript & Links
gem 'jbuilder', '~> 2.0.6'
gem 'jquery-rails', '~> 3.1.0'
# gem 'therubyracer',  platforms: :ruby
gem 'turbolinks', '~> 2.2.2'
gem 'uglifier', '>= 2.5.0'

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Deployment
group :deployment do
  # gem 'capistrano', '~> 3.1.0'
  # gem 'capistrano-bundler', '~> 1.1.2'
  # gem 'capistrano-rails', '~> 1.1.1'
  # gem 'capistrano-rvm'
end

# Development
group :development do
  # RailsApps Testing Framework to set up and configure testing
  gem 'rails_apps_testing'
  gem 'spring', '~> 1.1.2'
end

# Documentation
group :doc do
  gem 'sdoc', '~> 0.4.0'
end

# Production
group :production do
  # gem 'unicorn'
end

# Testing
group :test do
  gem 'capybara', '~> 2.2.1'
  # gem 'capybara-screenshot', '~> 0.3.19'
  # gem 'cucumber-rails', '~> 1.4.0', :require => false # https://github.com/cucumber/cucumber-rails
  gem 'database_cleaner', '~> 1.2.0' # https://github.com/bmabet/database_cleaner
  # gem 'email_spec', '~> 1.5.0'
  # gem 'faker', '~> 1.3.0' # http://rubydoc.info/github/stympy/faker/master/frames
  gem 'launchy', '~> 2.4.2'
  gem 'selenium-webdriver', '~> 2.41.0'
  # gem 'shoulda-matchers', '~> 2.6.0' # https://github.com/thoughtbot/shoulda-matchers
end

# Development & Testing
group :development, :test do
  gem 'better_errors', '~> 1.1.0'
  gem 'binding_of_caller', '~> 0.7.2', :platforms => [ :mri_19, :mri_20, :mri_21, :rbx ]
  # gem 'debugger'
  gem 'factory_girl_rails', '~> 4.4.1'
  gem 'mailcatcher', '~> 0.2.4'
  gem 'quiet_assets', '~> 1.0.2'
  gem 'pry-rails', '~> 0.3.2'
  gem 'rspec-rails', '~> 2.14.2'
  gem 'sqlite3', '~> 1.3.9'
end
