source 'http://rubygems.org'

gem 'rails', '3.2.0'

gem "bson_ext", "~> 1.3"
gem 'aws-s3'
gem 'profanity_filter'
gem 'activeadmin'
gem 'meta_search',    '>= 1.1.0.pre'
gem 'annotate', "~> 2.4.1.beta1"
gem 'uuidtools'


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', "  ~> 3.2.3"
  gem 'coffee-rails', "~> 3.2.1"
  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'
gem 'modernizr-rails'

group :production do
  gem 'pg'
  gem 'thin'
  gem 'therubyracer'
end

group :development do
  gem 'sqlite3'
end

group :test do
  # Pretty printed test output
  gem 'turn', :require => false
end