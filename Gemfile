source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 5.0.4'
gem 'pg', '~> 0.18'
gem 'puma', '~> 3.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'jquery-rails'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'dotenv-rails', '~> 2.2', '>= 2.2.1'

group :development, :test do
  gem 'byebug', platform: :mri
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

gem 'foundation-rails', '~> 6.3.1.0'
gem 'font-awesome-rails', '~> 4.7', '>= 4.7.0.2'
gem 'gritter', '~> 1.2'

gem 'momentjs-rails'
gem 'fullcalendar.io-rails'
gem 'jquery-ui-rails', '~> 6.0', '>= 6.0.1'

gem 'slim', '~> 3.0', '>= 3.0.9'

gem 'devise', '~> 4.4', '>= 4.4.1' 
gem 'omniauth-google-oauth2', '~> 0.5.3'