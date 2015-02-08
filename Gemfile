source 'https://rubygems.org'

ruby File.read(File.expand_path('../.ruby-version', __FILE__)).chomp

gem 'rails', '4.2.0'
gem 'pg'
gem 'puma'
gem 'rails_12factor', group: :production

# Asset Pipeline
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'bower-rails'
gem 'angular-rails-templates'

group :development, :test do
  gem 'byebug'
  gem 'web-console', '~> 2.0'
  gem 'spring'
  gem 'spring-commands-rspec'
  gem 'rspec-rails'
  gem 'capybara'
  gem 'poltergeist'
  gem 'database_cleaner'

  gem "codeclimate-test-reporter", require: false

  gem 'guard-rspec', require: false
  gem 'guard-bundler', require: false
  gem 'ruby_gntp', require: false
end
