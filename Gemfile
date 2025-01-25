source 'https://rubygems.org'

gem 'rails', '~> 7.0.0'
gem 'pg', '~> 1.2'
gem 'puma', '~> 5.0'
gem 'jbuilder', '~> 2.7'
gem 'bcrypt', '~> 3.1.7'
gem 'jwt', '~> 2.5'
gem 'devise', '~> 4.8'
gem 'rspec-rails', '~> 5.1', group: [:development, :test]
gem 'factory_bot_rails', group: [:development, :test]
gem 'dotenv-rails', groups: [:development, :test]

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'rubocop', require: false
end

group :test do
  gem 'faker'
  gem 'capybara'
  gem 'selenium-webdriver'
end