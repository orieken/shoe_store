source :rubygems

gem 'sinatra'
gem 'haml'
gem 'sass'
#gem 'activerecord'
gem 'sinatra-activerecord', :require => 'sinatra/activerecord'
gem 'cv-user-agent'
gem 'shotgun'
gem 'lorem'
gem 'sinatra-flash'
gem 'pry'
gem 'pry-nav'
gem 'racksh'
gem 'feedzirra'
gem 'nokogiri'
gem 'chronic'
gem 'thin'
gem 'heroku'

group :development, :test do
	gem 'sqlite3'
end

group :development do
	gem 'git'
end

group :test do
	gem 'cucumber'
	gem 'rspec'
	gem 'watir-webdriver'
	gem 'taza'
	gem 'rack-test', :require => 'rack/test'
	gem 'webrat'
	gem 'ZenTest'
	gem 'autotest-fsevent'
	gem 'autotest-growl'
	gem 'cuke_puke'
	gem 'factory_girl'
	gem 'capybara'
end

group :production do
	gem 'pg'
end

# price: doc.xpath('//item').first.children[3].to_s.split('Price: ').last.split('.00').first
# doc.xpath('.//img/@src').first.value
