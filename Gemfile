source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.2'

gem 'rails-assets-bootstrap.growl', source: 'https://rails-assets.org'
gem 'rails-assets-animate-css', source: 'https://rails-assets.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.4', '>= 5.2.4.5'

# Repository for collecting Locale data for Ruby on Rails I18n as well as other interesting, Rails related I18n stuff
gem 'rails-i18n'
# Manage Procfile-based applications
gem 'foreman'
# Flexible authentication solution for Rails with Warden
gem 'devise'
# Translations for the devise gem
gem 'devise-i18n'
# Rails gem of the Bootstrap based admin theme SB Admin 2.
gem 'bootstrap_sb_admin_base_v2'
gem "font-awesome-rails"
gem 'faker'
gem 'rails-assets-bootbox', source: 'https://rails-assets.org'
gem 'enum_help'
gem 'pundit'
gem 'money-rails'
gem 'paperclip', '~> 6.0.0'
gem 'jquery-ui-rails'
gem 'redcarpet'
gem 'doctor_ipsum'
gem 'friendly_id'
gem 'wiselinks'
gem 'kaminari'
gem 'kaminari-i18n'
gem 'ratyrate'
gem 'rubocop-faker'
gem 'prawn-rails'
gem 'wicked_pdf'
gem 'wkhtmltopdf-binary'

gem 'rails-assets-bootstrap-markdown', source: 'https://rails-assets.org'
gem 'rails-assets-marked', source: 'https://rails-assets.org'

gem 'bower-rails'

gem 'bootstrap', '4.5.3'

# Use sqlite3 as the database for Active Record
gem 'sqlite3'
# Use Puma as the app server
gem 'puma', '~> 3.11'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'mini_racer', platforms: :ruby

# The 'ruby-debug-ide' gem provides the protocol to establish communication between the debugger engine
gem 'ruby-debug-ide'
# Debase is a fast implementation of the standard debugger debug.rb
gem 'debase'

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'

gem 'jquery-rails'
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
gem 'bootsnap', '>= 1.1.0', require: false

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'better_errors'
  gem 'rails-erd'
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'rubocop', require: false

    # Remote multi-server automation tool
  gem 'capistrano', '~> 3.16'
  # Official Ruby on Rails specific tasks for Capistrano
  gem 'capistrano-bundler', '~> 2.0'
  # Bundler support for Capistrano 3.x
  gem 'capistrano-rails', '~> 1.6'
  # RVM support for Capistrano v3
  gem 'capistrano-rvm'
  # Unicorn for Capistrano v3
  gem 'capistrano3-unicorn'
end

group :production do
  # MySQL Adapter
  #gem 'mysql2', '~> 0.4.4'
    # Use Unicorn as the app server
  gem 'unicorn'
    # Mailgun's Official Ruby Library
  gem 'mailgun-ruby', '~>1.2.3'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
