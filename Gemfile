
source 'https://rubygems.org'

ruby '3.3.5'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 7.1.0'
# Use sqlite3 as the database for Active Record
gem 'sqlite3', '~> 1.4'
gem 'nokogiri', '~> 1.15'
# Removed deprecated asset pipeline gems for Rails 7+
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library

# Modern Rails 7+ JS handled by importmap or jsbundling-rails if needed
gem 'jbuilder', '~> 2.0'
gem 'puma', '~> 6.0'
gem 'webrick', '~> 1.8'
gem 'ostruct', '~> 0.6.3'

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Access an IRB console on exception pages or by using <%= console %> in views

group :development do
  gem 'web-console', '~> 4.2'
end

group :development, :test do
  gem 'byebug'
  gem 'spring'
  gem 'rspec-rails', '~> 6.0'
  gem 'database_cleaner-active_record', '~> 2.0'
  gem 'rubocop', require: false
  gem 'pry'
end
