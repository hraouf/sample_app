
source 'https://rubygems.org'

 require 'rbconfig'
if RbConfig::CONFIG['target_os'] =~ /mswin|mingw|cygwin/i
  gem 'wdm', '>= 0.1.0'
end

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.0'

gem 'bootstrap-sass', '2.0.0'

# Use sqlite3 as the database for Active Record
#gem 'sqlite3'

group :development do 
	gem 'sqlite3'
	gem 'rspec-rails', '2.9.0'
	gem 'guard-rspec', '0.5.5'
end

group :production do 
	gem 'pg'
end

# Use SCSS for stylesheets
#gem 'sass-rails', '~> 4.0.0'

# Use Uglifier as compressor for JavaScript assets
#em 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
#gem 'coffee-rails', '~> 4.0.0'

group :assets do
	gem 'sass-rails', '4.0.2'
	gem 'uglifier', '1.3.0'
	gem	'coffee-rails', '4.0.1'
end

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'

group :test do
	gem 'rspec-rails', '2.9.0'
	gem 'capybara', '1.1.2'

 	gem 'rb-fchange', '0.0.5'
	gem 'rb-notifu', '0.0.4'
	#gem 'win32console'
	gem 'guard-spork', '0.3.2'
	gem 'spork', '0.9.0'


end

#Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
