source 'https://rubygems.org'
ruby '2.2.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'pg'#, '0.15.1'
gem 'rails', '4.2.6'
gem 'bootstrap-sass','2.3.2.0'
# Use sqlite3 as the database for Active Record
group :development, :test do
    gem 'rspec-rails'
    gem 'guard-rspec'
end

group :test do
    gem 'selenium-webdriver', '2.35.1'
    gem 'capybara', '2.2.0'
    # Linux: раскомментируйте эти строки.
    gem 'libnotify'
end

gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'therubyracer', platforms: :ruby
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'

gem 'sdoc', '~> 0.4.0', group: :doc

  gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'spork-rails'
  gem 'guard-spork'
  gem 'childprocess'
  gem 'byebug'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
#  gem 'spring'
end

group :production do
  gem 'rails_12factor', '0.0.2'
  gem 'pg'# '0.15.1'
end
