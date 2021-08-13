source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.3'


#gems project

#cancan for to manage the  access
gem 'cancancan', '~> 3.1'
#dropzone for the files
gem 'dropzonejs-rails', '~> 0.8.5'
#for sending sms
gem 'twilio-ruby', '~> 5.47'
#haml
gem 'haml', '~> 5.1', '>= 5.1.2'
#devise for auth
gem 'devise', '~> 4.7', '>= 4.7.1'
#export excel
gem 'caxlsx_rails', '~> 0.6.2'
#booststrap
gem 'bootstrap-sass'
#font-awesome
gem "font-awesome-rails"
#calendar
gem 'fullcalendar-rails'
gem 'momentjs-rails'
#tables functionality
gem 'jquery-datatables', '~> 1.10', '>= 1.10.20'
gem 'ajax-datatables-rails', '~> 1.2'
#transaltion
gem 'i18n', '~> 1.8', '>= 1.8.2'

#To manage uploaded files
gem 'carrierwave', '~> 2.1.0'
gem 'mini_magick', '~>4.11.0'

#Editor html w
gem 'ckeditor', '~> 5.1.0'
#jquery
gem 'jquery-rails', '~> 4.3', '>= 4.3.5'
# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.4'
# Use postgresql as the database for Active Record
gem 'pg'
# Use Puma as the app server
gem 'puma', '~> 3.12'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'mini_racer', platforms: :ruby

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use ActiveStorage variant
# gem 'mini_magick', '~> 4.8'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Reduces boot times through caching; required in config/boot.rb
#gem 'bootsnap', '>= 1.1.0', require: false

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'rspec-rails', '~> 4.1'
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :production  do
  #haml
  gem 'haml', '~> 5.1', '>= 5.1.2'
  #devise
  gem 'devise', '~> 4.7', '>= 4.7.1'
  #booststrap
  gem 'bootstrap-sass'
  #font-awesome
  gem "font-awesome-rails"
  #jquery
  gem 'jquery-rails', '~> 4.3', '>= 4.3.5'
  gem 'pg'
  #calendar
  gem 'fullcalendar-rails'
  gem 'momentjs-rails'
end



group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of chromedriver to run system tests with Chrome
  gem 'chromedriver-helper'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
