source 'https://rubygems.org'

ruby '2.2.2'
gem 'bundler'
gem 'jekyll'
gem 'rack-jekyll'

group :production do
  gem 'pg'

  gem 'rails_12factor'
end
group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  gem 'sqlite3'
  # Use SCSS for stylesheets
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end
