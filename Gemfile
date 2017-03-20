source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.1'
# Use postgresql as the database for Active Record
gem 'pg', '~> 0.18'
# Use Puma as the app server
gem 'puma', '~> 3.0'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'
# gem Devise - Used for Athentication
gem 'devise'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
gem 'friendly_id', '~> 5.1.0'
gem 'bootstrap', '~> 4.0.0.alpha6'

gem 'pinion_view_tool', '~> 0.1.0'
# Petergate is used for Authorization
gem 'petergate', '~> 1.7'
# Font-awesome-rails for images in blogs
gem 'font-awesome-rails', '~> 4.7', '>= 4.7.0.1'
# Kaminari Gem installed for blog pagination
gem 'kaminari', '~> 1.0', '>= 1.0.1'
# Use in portfolio drag and drop
gem 'jquery-ui-rails', '~> 6.0', '>= 6.0.1'

# gems for image uploader
gem 'carrierwave', '~> 1.0'
gem 'mini_magick', '~> 4.6', '>= 4.6.1'
gem 'carrierwave-aws', '~> 1.1'
gem 'dotenv-rails', '~> 2.2'

# Used for creating a dynamic javascript form on portfolios new and edit for technologies
gem 'cocoon', '~> 1.2', '>= 1.2.9'

# for bootstrap 4
gem 'tether-rails'

# messaging for forms
gem 'gritter', '~> 1.2'
# Gem used for twiller api implimentation
gem 'twitter', '~> 6.1'
# Gem used for actioncable comments
gem 'redis', '~> 3.3', '>= 3.3.3'
# Gems for Markdown
gem 'redcarpet', '~> 3.4'
gem 'coderay', '~> 1.1', '>= 1.1.1'
