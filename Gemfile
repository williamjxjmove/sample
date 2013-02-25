source 'https://rubygems.org'

require 'mongo'

gem 'rails', '3.2.12'
gem 'bootstrap-sass', '2.1'
gem 'bcrypt-ruby', '3.0.1'
gem 'faker', '1.0.1'
gem 'will_paginate', '3.0.3'
gem 'bootstrap-will_paginate', '0.0.6'
gem 'jquery-rails', '2.0.2'

group :development, :test do
  gem 'sqlite3', '1.3.5'
  gem 'mongo_mapper', '~> 0.12.0'
  gem 'bson_ext', '~> 1.8.2'
  gem 'bson', '~> 1.8.2'
  gem 'mongo', '~> 1.8.2'

  gem 'rspec-rails', '2.11.0'
  gem 'guard-rspec', '1.2.1'

  gem 'cucumber-rails', '1.2.1', :require => false
  gem 'database_cleaner', '0.7.0'
end

group :development do
  gem 'annotate', '2.5.0'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '3.2.5'
  gem 'coffee-rails', '3.2.2'
  gem 'uglifier', '1.2.3'
end

group :test do
  gem 'capybara', '1.1.2'
  gem 'rb-inotify', '0.8.8'
  gem 'libnotify', '0.5.9'
end

group :production do
  gem 'pg', '0.12.2'
end
