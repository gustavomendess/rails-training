source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.0.2"

gem "rails", "~> 7.0.1"
gem "sprockets-rails"
gem "devise"
gem "pg", "~> 1.1"
gem "puma", "~> 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "redis", "~> 4.0"
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]
gem "bootsnap", require: false
gem "dotenv-rails", "~> 2.5"
gem "rubocop-rails"

group :development, :test do
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
  gem "factory_bot_rails"
  gem "rspec-rails"
  gem "rubycritic"
end

group :development do
  gem "web-console"
  gem "spring"
end

group :test do
  gem "database_cleaner"
  gem "shoulda-matchers"
  gem "simplecov"
end

