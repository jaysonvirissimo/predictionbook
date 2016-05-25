source 'http://rubygems.org'

gem 'rails'
gem 'rails-observers'
gem 'jquery-rails'
gem 'devise'
# Models
gem 'chronic'
gem 'uuidtools'

# Views
gem 'RedCloth'
gem 'formatize', git: 'https://github.com/januszm/formatize'
gem 'htmlentities'
gem 'sass-rails'

# Servers
gem 'mysql2'
gem 'thin'

# App housekeeping
gem 'exception_notification'
gem 'whenever'
gem 'typus', github: 'typus/typus'

# Misc
gem 'honeypot-captcha'
gem 'hashdiff'
gem 'sentry-raven'

group :development do
  gem 'capistrano', '~> 2.0'
  gem 'capistrano-ext'
end

group :test, :development do
  gem 'rspec-rails'
  gem 'rspec-activemodel-mocks'
  gem 'pry'
  gem 'pry-byebug'
  gem 'hirb'
  gem 'wirble'
  gem 'awesome_print'
  gem 'simplecov'
end

group :development, :test do
  gem 'capybara'
  gem 'database_cleaner'

end

group :metrics do
  gem 'trike-code-metrics', git: 'git@github.com:tricycle/trike-code-metrics'
end

group :test do
  gem 'launchy'
  gem 'factory_girl'
  gem 'ffaker'
  gem 'shoulda-matchers'
  gem 'guard-rspec'
  gem 'email_spec'
  gem 'terminal-notifier-guard', require: false
  gem 'terminal-notifier'
end

group :assets do
  gem 'uglifier'
end

group :linux, :production do
  # Does not build on Mountain Lion nor is it needed on OS X
  gem 'therubyracer'
end

group :darwin do
  gem 'rb-fsevent', require: false # OSX specific
end

# restful-authentication needs to be installed as a plugin or it doesn't work
# rspec-caching-test-plugin is quite old and is not available as a gem
