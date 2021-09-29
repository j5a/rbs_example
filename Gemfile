source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.2'

gem 'rails', '~> 6.1.4', '>= 6.1.4.1'
gem 'sqlite3', '~> 1.4'
gem 'puma', '~> 5.0'
gem 'sass-rails', '>= 6'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'rbs', '1.7.0.beta.4'
  gem 'rbs_rails', require: false
  gem 'steep', github: 'soutaro/steep'
end

group :development do
  gem 'listen', '~> 3.3'
end
