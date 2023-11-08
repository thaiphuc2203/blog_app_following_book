source 'https://rubygems.org'
git_source(:github) { |_repo| "https://github.com/#{repo}.git" }

ruby '3.1.2'

gem 'bootstrap'
gem 'rails', '7.0.4'
gem 'sassc-rails'
gem 'sprockets-rails', '3.4.2'

gem 'bcrypt'
gem 'bootsnap',        '1.12.0', require: false
gem 'importmap-rails', '1.1.0'
gem 'jbuilder',        '2.11.5'
gem 'puma',            '5.6.4'
gem 'stimulus-rails',  '1.0.4'
gem 'turbo-rails',     '1.1.1'

group :development, :test do
  gem 'debug', '1.5.0', platforms: %i[mri mingw x64_mingw]
  gem 'rubocop'
  gem 'sqlite3', '1.4.2'
end

group :development do
  gem 'web-console', '4.2.0'
end

group :test do
  gem 'capybara',                 '3.37.1'
  gem 'guard',                    '2.18.0'
  gem 'guard-minitest',           '2.4.6'
  gem 'minitest',                 '5.15.0'
  gem 'minitest-reporters',       '1.5.0'
  gem 'rails-controller-testing', '1.0.5'
  gem 'selenium-webdriver',       '4.2.0'
  gem 'webdrivers',               '5.0.0'
end

group :production do
  gem 'pg', '1.3.5'
end
