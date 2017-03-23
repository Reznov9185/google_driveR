source 'https://rubygems.org'

gem 'daemons'
gem 'delayed_job_active_record'
# ~> change only minor (last) number
gem 'rack-cors', :require => 'rack/cors'
gem 'devise'
gem 'figaro'
gem 'actionmailer'
gem 'doorkeeper'
gem 'twilio-ruby'
#needed by devise for creatign pw
gem 'bcrypt-ruby'
gem 'whenever', :require => false
gem 'rails', '~> 4.2.3'
gem 'pg'
gem 'jbuilder', '~> 2.0'
gem 'rake'
gem 'mechanize'
gem 'rubyXL'
gem 'unicorn'
gem 'unicorn-rails'
gem 'sidekiq'
gem 'rufus-scheduler', '~> 3.2'


group :development, :test do
	gem 'faker'
	gem 'database_cleaner', '~> 1.5', '>= 1.5.1'
	gem 'rspec_api_documentation'
    gem 'pry'
    gem 'pry-nav'
  	gem 'spring'
    gem 'rspec-rails'
	gem 'factory_girl_rails'
	gem 'minitest', '~> 5.1'
	gem 'rack-test'
	gem 'webmock'
	gem 'json-schema'
end

group :production do
    # Multiple workers inside of one dyno for heroku
    gem 'foreman', '~> 0.82.0'
end
