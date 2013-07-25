source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.0'

# Use sqlite3 in development, but postgresql for production.
# This is not a great practice, only good if you want to avoid
# the overhead of installing PostgreSQL on your dev. machine.
gem 'sqlite3'

# Use thin for the development server.  Choose a production
# server here.
gem "thin", "~> 1.5.1", group: :development
# gem "unicorn", "~> 4.6.3"  # Recommended for Heroku

# Use LESS for stylesheets
gem "less-rails", "~> 2.3.3"

# Use Slim for templates
gem "slim-rails", "~> 2.0.1"

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

group :test do
	# Use rspec for testing
	gem "rspec-rails", "~> 2.14.0"

	# Spork support for Rails 4 is not yet released.
	# Please see https://github.com/sporkrb/spork/issues/223
	gem "spork-rails", github: "sporkrb/spork-rails", ref: "3224f84d8c31fcb0894e9a43f6c3ac67e3aa0d71"
	gem "spork", github: "sporkrb/spork", ref: "38ab44f0968c23509912680a04f903fe4ad5c068"

	# Use guards to automate testing
	gem "guard-rails", "~> 0.4.7"
	gem "guard-rspec", "~> 3.0.2"
	gem "guard-spork", "~> 1.5.1"
	gem "guard-bundler", "~> 1.0.0"

	# Use Fabrication as a fixture replacement
	gem "fabrication", "~> 2.7.2"
end