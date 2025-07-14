# NOTE: These are development-only dependencies
source 'https://rubygems.org'

gemspec

group :development, :test do
  gem 'rubocop'
  gem 'rubocop-shopify', '>= 2.2.0'
  gem 'byebug', platforms: [:mri]
  gem 'method_source'
end

group :test do
  gem 'mocha', require: false
  gem 'minitest', '>= 5.0.0', require: false
  gem 'minitest-reporters', require: false
end
