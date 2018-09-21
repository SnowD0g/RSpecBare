source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

group :development, :test do
  gem 'sqlite3'
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'factory_bot_rails'
  gem 'cucumber-rails', require: false
  gem 'database_cleaner', '~> 1.7'
  #javascript unite test
  gem 'jasmine-rails'
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'rspec-rails'
  gem 'capybara' #driver di default è chrome headless
  gem 'rails-controller-testing' # deprecato
  gem 'email_spec'
  gem 'vcr'
  gem 'webmock'
  gem 'poltergeist'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
