source 'https://rubygems.org'
ruby '2.3.1'

gem 'rails', '4.2.6'

group :development, :test do
  gem 'rspec-rails', '3.5.0'
  gem 'guard-rspec', '~> 4.6', '>= 4.6.4'
end

group :test do
  gem 'selenium-webdriver', '2.35.1'
  gem 'capybara',           '2.2.0'
  gem 'libnotify', '~> 0.9.1'
  gem 'factory_girl_rails', '4.2.1'
end

group :development do
  gem 'spring', '~> 1.6', '>= 1.6.4'
  gem 'pry-rails', :group => :development
  gem 'better_errors', git: 'https://github.com/manafire/better_errors.git', branch: 'allow_domain'
end

gem 'pg',             '~> 0.15'
gem 'bootstrap-sass', '2.3.2.0'
gem 'bcrypt-ruby',    '3.1.2'
gem 'sass-rails',     '~> 5.0'
gem 'uglifier',       '~> 2.7'
gem 'coffee-rails',   '~> 4.1.0'
gem 'jquery-rails',   '3.0.4'
gem 'turbolinks',     '~>2.5.3'
gem 'jbuilder',       '~> 2.0'


group :doc do
  gem 'sdoc', '0.3.20', require: false
end

group :production do
  gem 'rails_12factor', '0.0.2'
end
