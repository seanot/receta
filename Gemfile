source 'https://rubygems.org'

gem 'rails', '4.1.5'
gem 'pg'
gem 'sass', '3.2.19'
gem 'sass-rails', '~> 4.0.3'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'jbuilder', '~> 2.0'
gem 'bower-rails'
gem 'angular-rails-templates'
gem 'foreman'
# gem 'bcrypt', '~> 3.1.7'

group :production, :staging do
  gem 'rails_12factor'
  gem 'rails_stdout_logging'
  gem 'rails_serve_static_assets'
end

group :development do
  gem 'spring'
end

group :test, :development do
  gem 'rspec'
  gem 'rspec-rails', '~> 2.0'
  gem 'factory_girl_rails', '~> 4.0'
  gem 'capybara'
  gem 'database_cleaner'
  gem 'selenium-webdriver'
  gem 'teaspoon'
  gem 'phantomjs'
end

group :doc do
  gem 'sdoc', require: false
end