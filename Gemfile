source 'https://rubygems.org'

gem 'rails', '3.2.2'
gem 'gravatar_image_tag'

# The gem below was originally gem 'will_paginate', '3.0.pre2' but there was a bug or 
# something but there was a patch I found here:
# http://stackoverflow.com/questions/6382966/will-paginate-conflict-rails-3-1-0-rc4
gem "will_paginate", :git => "https://github.com/p7r/will_paginate.git", :branch => "rails3"

group :production do
  gem 'pg'
end

group :development, :test do
	gem 'sqlite3'
	gem 'rspec-rails'
	gem 'annotate'
	gem 'faker'
end

group :test do
  gem 'rspec-rails'
  gem 'webrat'
  gem 'spork'
  gem 'factory_girl_rails'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer'

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'
