source "https://rubygems.org"

gem "rspec"
gem 'guard'
gem 'guard-rspec'
gem 'guard-bundler'

if RUBY_PLATFORM.downcase.include?("darwin")
  # These are Mac OS-specific tools
  gem 'rb-fsevent'
  gem 'growl' # install GrowlNotify from http://growl.info/downloads.php
end
