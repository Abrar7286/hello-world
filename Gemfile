source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '5.0.2'
# Use mysql as the database for Active Record
gem 'mysql2' ,'~>0.4.9 '
# Build JSON APIs with ease. Read more: ttps://github.com/rails/jbuilder
gem 'jbuilder', '~>2.7.0 '# *
# bundle exec rake doc:rails generates the API under doc/api.
# gem 'sdoc', '~> 0.4.0',      group: :doc
gem 'rdoc', '~>5.1.0'
gem 'paper_trail' ,'~>7.1.3'
gem 'devise' ,'~>4.3.0'# *

# gem "rails-erd"
# gem 'schemard', '~> 0.4.0'

gem 'turbolinks'
gem 'omniauth' , '~>1.7.1' # *
gem 'omniauth-facebook' ,'~>4.0.0' # *
gem 'omniauth-twitter', :github => 'arunagw/omniauth-twitter'  # *
gem 'instagram' ,'~>0.3.2' # *
gem "paperclip" ,'~>5.1.0'
gem 'geocoder' , '~>1.4.4'
# gem 'geokit-rails'
gem 'docsplit' , '~>0.7.6'
gem 'smarter_csv' , '~>1.1.4' # *

gem "dropbox-api" , '~>0.4.7'  # *
gem 'devise_invitable' , '~>1.7.2' # *
gem 'stripe', :git => 'https://github.com/stripe/stripe-ruby'
gem 'twilio-ruby' , '~>5.3.1'

gem 'devise-token_authenticatable', '~> 1.0'

gem "lograge" ,'~>0.7.1'

gem 'ruby-graphviz', '~> 1.2', '>= 1.2.2'

gem 'roo' , '~>2.7.1'
gem "iconv" , '~>1.0.4'
# gem 'roo-xls'

gem 'rails_admin' ,'~>1.2.0'
gem 'fb_graph2' , '~>1.0.1'
gem 'twitter' , '~>6.1.0'
gem 'mandrill_mailer' , '~>1.6.0'

gem 'newrelic_rpm' , '~>4.5.0.337'
gem 'rack-cors' , '~>1.0.1'
gem 'capistrano' , '~>3.9.1'
gem 'capistrano-rails' , '~>1.3.0'
gem 'capistrano-bundler' , '~>1.3.0'
gem 'capistrano-rbenv' , '~>2.1.2'
gem 'unicorn', group: :production
gem 'faker' ,'~>1.8.4'

# gem 'carrierwave'
gem 'capistrano-slackify', require: false

gem 'rails-controller-testing' ,'~>1.0.2'

# gem 'delayed-web'

gem 'delayed_job_active_record','~>4.1.2'
gem "delayed_job_web",'~>1.4'

# Bootstrap gem for rails app
gem 'bootstrap-sass','~>3.3.7'

# Use SCSS for stylesheets
gem 'sass-rails'
# Use jquery as the JavaScript library
gem 'jquery-rails','~>4.3.1'

gem 'whenever', :require => false

gem 'sidekiq','~>5.0.5'

gem 'redis-rails'

gem 'awesome_print','~>1.8.0'
#  This Gem to pagination the response
gem 'will_paginate','~>3.1.6'
# for active record in the svg table
# gem 'composite_primary_keys', '= 7.0.0'

# gem 'sinatra', '>= 1.3.0', :require => nil

# gem 'sinatra', require: false
# gem 'slim'

# gem 'sidekiq_monitor'

# gem 'prototype-rails'
# Use ActiveModel has_secure_password
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use debugger

# gem 'debugger', '~> 1.6', '>= 1.6.8', group: [:development, :test]
# gem 'debugger', group: [:development, :test]

group :development do
  gem 'pry-rails' ,'~>0.3.6'
  gem 'pry-remote' ,'~>0.1.8'
  gem 'better_errors' ,'~>2.3.0'
  gem 'binding_of_caller' ,'~>0.7.2'
  # gem 'capistrano-sidekiq'

end

group :development, :test do

  gem "rails-erd" ,'~>1.5.2'

  gem 'pry' ,'~>0.11.1'
  gem 'rspec-rails' ,'~>3.6.1'

  gem 'factory_girl_rails' ,'~>4.8.0'
  gem 'database_cleaner' ,'~>1.6.1'
  gem 'simplecov', :require => false, :group => :test
  gem 'simplecov-rcov', :require => false, :group => :test
  # gem 'pry-byebug'
  gem 'rspec_junit_formatter' ,'~>0.3.0'
  gem 'guard-rspec', require: false
  gem 'guard-zeus' ,'~>2.0.1'
  gem 'guard' ,'~>2.14.1'

  gem 'commands' ,'~>0.2.1'
  gem 'shoulda-matchers','~>3.1.2'
end
