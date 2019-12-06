source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.3'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0.0.rc1'
# Use postgresql as the database for Active Record
gem 'pg', '>= 0.18', '< 2.0'
# Use Puma as the app server
gem 'puma', '~> 3.12'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 4.0'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'
gem 'haml'
gem 'haml-rails'

gem 'foundation-rails'
gem 'autoprefixer-rails'

# Authentication
gem 'devise'
gem 'devise-i18n'
gem 'devise-security'
gem 'rolify'
gem 'cancancan'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]

  gem 'rspec-rails'
  gem 'rubocop', require: false

  # Exception page with console
  gem 'better_errors'

  # Required for better_errors
  gem 'binding_of_caller'

  gem 'factory_bot_rails'

  # nicer matchers for rspec, 'should include' etc.
  gem 'shoulda-matchers'

  gem 'ffaker'
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  # A library for setting up Ruby objects as test data.
  gem "rspec_junit_formatter"

  # Clean the test database after tests
  gem 'database_cleaner'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

group :profilers, optional: true do
  # profiler showing render times and db time
  gem 'rack-mini-profiler'

  # Watch db queries for improvements (including n+1 queries detection)
  gem 'bullet'

  # A series of things you can use to benchmark a Rails app.
  # See https://github.com/schneems/derailed_benchmarks for install and tasks
  gem 'derailed_benchmarks'

  # Rails security scanner
  gem 'brakeman', require: false
end
