source 'https://rubygems.org'

git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.3'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.3'
# Use postgresql as the database for Active Record
gem 'pg', '~> 1.0'
# Use SCSS for stylesheets
gem 'sassc-rails'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'mini_racer', platforms: :ruby

# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder', '~> 2.5'
gem 'active_model_serializers'

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use ActiveStorage variant
# gem 'mini_magick', '~> 4.8'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false

gem 'webpacker', '>= 4'

gem 'slim-rails'
gem 'kaminari'
gem 'redis', '~> 4.1'
gem 'sidekiq'
gem 'sidekiq-cron'
gem 'searchkick'
gem 'puma', '~> 4.1'
gem 'rack'
gem 'clearance'
gem 'knock'
gem 'simple_form', '>= 3.5.1'
gem 'pundit'
gem 'skylight'
gem 'premailer-rails'
gem 'paper_trail'
gem 'blazer'
gem 'friendly_id'
gem 'stringex'
gem 'rollbar'
gem 'rack-cors', require: 'rack/cors'

# Image uploads
gem 'shrine'
gem 'image_processing'
gem 'mini_magick'
gem 'aws-sdk-s3'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]

  # Support #save_and_open_page in feature specs
  gem 'launchy'

  gem 'rspec-rails'
  gem 'factory_bot_rails'
  gem 'dotenv-rails'
  gem 'rubocop', require: false
  gem 'rubocop-rails', require: false
  gem 'rubocop-performance', require: false
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'spring-commands-rspec'
  gem 'letter_opener'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'webdrivers'

  gem 'simplecov', require: false
  gem 'email_spec'
  gem 'shrine-memory'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
