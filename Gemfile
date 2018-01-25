source "https://rubygems.org"

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem "bootstrap-sass", "3.3.7"
gem "carrierwave", "~> 1.1.0"
gem "coffee-rails", "~> 4.2"
gem "devise"
gem "font-awesome-rails"
gem "jbuilder", "~> 2.5"
gem "jquery-rails", "~> 4.3"
gem "kaminari"
gem "puma", "~> 3.0"
gem "pygments.rb", "~> 0.6.3"
gem "rails", "~> 5.0.6"
gem "redcarpet", "~> 3.3", ">= 3.3.4"
gem "sass-rails", "~> 5.0"
gem "simplemde-rails"
gem "turbolinks", "~> 5"
gem "uglifier", ">= 1.3.0"

group :development, :test do
  gem "byebug", platform: :mri
  gem "sqlite3", "1.3.13"
end

group :development do
  gem "listen", "~> 3.0.5"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "web-console", ">= 3.3.0"
end

group :production do
  gem "pg", "0.20"
end

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
