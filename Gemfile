source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.3'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0.1'
# Use sqlite3 as the database for Active Record
#gem 'sqlite3', '~> 1.4'

gem 'mysql2'
gem "pg"
gem 'thin'
gem 'unicorn'
gem 'cowsay'
gem 'capistrano'
gem 'capistrano-rails'

# Use Puma as the app server
gem 'puma', '~> 4.1'
# Use SCSS for stylesheets
gem 'sass-rails', '>= 6'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 4.0'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false
gem 'vueonrails'

gem 'whenever', :require => false
gem 'activerecord-import'
gem 'parallel'

gem 'haml'
gem 'devise'
gem 'cancan'
gem 'doorkeeper'
gem 'versionist'
gem 'kaminari'
gem 'activeadmin'
gem 'formtastic'
gem 'thor'
gem 'oauth2'
gem "omniauth-facebook"
gem "koala"
gem "nokogiri"
gem "bcrypt"
gem "rails-i18n"

gem 'ed25519'
gem 'bcrypt_pbkdf'

# File uploader
gem 'carrierwave'
gem 'rmagick'

group :assets do
  gem 'sprockets-rails'
  gem 'sprockets'
  gem 'autoprefixer-rails'
  gem 'compass-rails'
  gem 'coffee-rails'
  gem 'uglifier'
  #gem 'less-rails'
end

gem 'jquery-rails'
gem 'jquery-ui-rails'
gem 'jquery-turbolinks'
gem 'rails3-jquery-autocomplete'
gem 'compass'

gem 'twitter-bootstrap-rails'
gem 'devise-bootstrap-views'

source 'https://rails-assets.org' do
  gem 'rails-assets-bootstrap-fileinput'
end

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of web drivers to run system tests with browsers
  gem 'webdrivers'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
