source 'https://rubygems.org'

ruby "2.3.1"
# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.0', '>= 5.0.0.1'
# Use Puma as the app server
gem 'puma', '~> 3.0'

gem 'bcrypt', '~> 3.1', '>= 3.1.11'

gem 'pry-rails', '~> 0.3.4'

gem 'jwt', '~> 1.5', '>= 1.5.6'

gem 'active_model_serializers', '~> 0.10.2'


# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
# gem 'rack-cors'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'pry', '~> 0.10.4'

  gem 'pry-nav', '~> 0.2.4'

  gem 'sqlite3', '~> 1.3', '>= 1.3.12'

  gem 'byebug', platform: :mri

  gem 'factory_girl_rails', '~> 4.7'

  gem 'rspec-rails', '~> 3.5', '>= 3.5.2'

  gem 'shoulda-matchers', '~> 3.1', '>= 3.1.1'

  gem 'faker', '~> 1.6', '>= 1.6.6'

  gem 'codeclimate-test-reporter', '~> 0.6.0', require: nil

  gem "simplecov", "~> 0.12.0", require: false
end

group :development do
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring', '~> 2.0'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :production do
  gem 'pg', '~> 0.19.0'
  gem 'rails_12factor', '~> 0.0.3'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
