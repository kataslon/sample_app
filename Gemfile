source 'https://rubygems.org'
ruby '2.3.1'

gem 'rails', '4.2.6'

group :development, :test do
  # gem 'sqlite3',     '~> 1.3.8'
  gem 'rspec-rails', '3.5.0'
  gem 'guard-rspec', '~> 4.6', '>= 4.6.4'
  # gem 'spork-rails', '4.0.0'
  # gem 'guard-spork', '>= 1.5.0'
  # gem 'childprocess', '>= 0.3.6'
end

group :test do
  gem 'selenium-webdriver', '2.35.1'
  gem 'capybara',           '2.2.0'
  gem 'libnotify', '~> 0.9.1'
end

group :development do
  gem 'spring', '~> 1.6', '>= 1.6.4'
  gem 'pry-rails', :group => :development
  gem 'better_errors', git: 'https://github.com/manafire/better_errors.git', branch: 'allow_domain'
end

gem 'pg',           '0.15.1'
gem 'sass-rails',   '4.0.1'
gem 'uglifier',     '2.1.1'
gem 'coffee-rails', '4.0.1'
gem 'jquery-rails', '3.0.4'
gem 'turbolinks',   '1.1.1'
gem 'jbuilder',     '1.0.2'

group :doc do
  gem 'sdoc', '0.3.20', require: false
end

group :production do
  # gem 'pg',             '0.15.1'
  gem 'rails_12factor', '0.0.2'
end
