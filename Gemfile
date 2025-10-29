# frozen_string_literal: true

source 'https://rubygems.org'

# Core gems
gem 'rails', '~> 8.1.1'
gem 'unicorn'

# Timezone support for Windows and JRuby
gem 'tzinfo-data', platforms: %i[windows jruby]

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', require: false

# Deploy this application anywhere as a Docker container [https://kamal-deploy.org]
gem 'kamal', require: false

# HTTP asset caching, compression, and X-Sendfile support for Puma
gem 'thruster', require: false

group :development, :test do
  # Debugging
  gem 'debug', platforms: %i[mri windows], require: 'debug/prelude'

  # Static analysis for security vulnerabilities
  gem 'brakeman', require: false

  # Ruby style enforcement
  gem 'rubocop-rails-omakase', require: false
end

group :development do
  # Rails console on error pages
  gem 'web-console'
end

group :test do
  # System testing framework
  gem 'capybara'
  gem 'selenium-webdriver'
end

