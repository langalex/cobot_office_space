source 'http://rubygems.org'

ruby '2.1.2'

gem 'rails', '~>3.1.10'
gem 'pg'
gem 'omniauth', git: 'git://github.com/intridea/omniauth.git'
gem 'simple_form'
gem 'inherited_resources'
gem 'cobot_client'
gem 'virtus'
gem 'sentry-raven'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', "~> 3.1.0"
  gem 'uglifier'
end

group :production do
  gem 'rails_12factor'
  gem 'puma'
end

gem 'jquery-rails'

# Use unicorn as the web server
# gem 'unicorn'

group :development do
  gem 'rspec-rails'
  gem 'dotenv-rails'
end

group :test do
  gem 'database_cleaner'
  gem 'turn', require: false
  gem 'cucumber-rails', require: false
  gem 'capybara'
  gem 'webmock'
  gem 'launchy'
end
