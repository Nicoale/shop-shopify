source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "2.7.0"

gem "rails", "~> 6.0.3", ">= 6.0.3.3"

gem "puma", "~> 4.1" # Use SCSS for styleets
gem "sass-rails", ">= 6"

gem "bootstrap-sass", "~> 3.4", ">= 3.4.1"
gem "execjs", "~> 2.7"
gem "jbuilder", "~> 2.7"
gem "jquery-rails", "~> 4.4"
gem "turbolinks", "~> 5"
gem "twitter-bootstrap-rails", "~> 3.2.0"
gem "webpacker", "~> 4.0"
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

gem "bootsnap", ">= 1.4.2", require: false

group :development, :test do
  gem "byebug", platforms: [:mri, :mingw, :x64_mingw]
  gem "sqlite3", "~> 1.4"
  # Helpful gems
  gem "better_errors", "~> 2.8", ">= 2.8.3"
  gem 'binding_of_caller', '~> 0.8.0'
  # Testing frameworks
  gem 'rspec-rails', '~> 4.0', '>= 4.0.1'
 gem 'factory_bot', '~> 6.1'
  gem 'capybara', '~> 3.33'
  gem 'fakeweb', '~> 1.3'
  # Automated testing
  gem 'guard', '~> 2.16', '>= 2.16.2'
  gem 'guard-rspec', '~> 4.7', '>= 4.7.3'
  # Only install the rb-fsevent geM on Max OSX
  gem 'rb-fsevent', '~> 0.10.4'
end

group :development do
  gem "listen", "~> 3.2"
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "web-console", ">= 3.3.0"
end

group :test do
  gem "selenium-webdriver"
  # Easy installation and use of web drivers to run system tests with browsers
  gem "webdrivers"
end
group :production do
  gem "pg", "0.18.0"
  gem "rails_12factor", "0.0.2"
end
# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
