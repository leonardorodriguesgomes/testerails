source "https://rubygems.org"

#ruby "3.2.3"
ruby "2.7.2"
#gem "rails", "~> 7.1.3", ">= 7.1.3.2"
gem "rails", "~> 6.1.0"

gem "sprockets-rails"
gem "puma", ">= 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "tzinfo-data", platforms: %i[ windows jruby ]
gem "bootsnap", require: false

group :development, :test do
  gem "sqlite3", "~> 1.3.6"
  gem "debug", platforms: %i[ mri windows ]
end

group :development do
  gem "web-console"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
end

gem "pg", "~> 1.5", :group => :production
