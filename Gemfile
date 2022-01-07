source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.0.2"

gem "bootsnap", require: false
gem "devise"
gem "dotenv-rails", "~> 2.5"
gem "importmap-rails"
gem "jbuilder"
gem "pg", "~> 1.1"
gem "puma", "~> 5.0"
gem "rails", "~> 7.0.1"
gem "redis", "~> 4.0"
gem "rubocop-rails"
gem "sprockets-rails"
gem "stimulus-rails"
gem "turbo-rails"
gem "tzinfo-data", platforms: %i[mingw mswin x64_mingw jruby]

group :development, :test do
  gem "debug", platforms: %i[mri mingw x64_mingw]
  gem "factory_bot_rails"
  gem "rspec-rails"
  gem "rubycritic"
end

group :development do
  gem "spring"
  gem "web-console"
end

group :test do
  gem "database_cleaner"
  gem "shoulda-matchers"
  gem "simplecov"
end
