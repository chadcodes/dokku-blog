source 'https://rubygems.org'

# set the ruby version for dokku deployment
ruby '2.1.2'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.5'
# Use postgresql as the database for Active Record
gem 'pg'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.3'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'
# Use jquery as the JavaScript library
gem 'jquery-rails'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

gem 'faker'
gem 'clearance'

group :development, :test do
  gem 'rspec-rails', '~> 3.0.0'
  gem "factory_girl_rails", "~> 4.0"
  gem 'capybara'
  gem 'database_cleaner'
  gem 'pry-rails'
  gem 'spring'
end

group :development do
  gem "better_errors"
  gem "binding_of_caller"
end