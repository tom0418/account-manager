source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.2'

# Server/Rack/Engine
gem 'rails', '~> 6.0.4', '>= 6.0.4.4'
gem 'puma', '~> 4.1'

# DB
gem 'mysql2', '>= 0.4.4'

# Optimization
gem 'bootsnap', '>= 1.4.2', require: false

# HTML/CSS
gem 'sass-rails', '>= 6'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'pry-byebug'
  gem 'pry-doc'
  gem 'pry-rails'
end

group :development do
  gem 'listen', '~> 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end
