#!/usr/bin/ruby
source 'https://rubygems.org'
gem 'json'
gem 'cuba'
gem 'roda'
gem 'syro'
gem 'unicorn'

gem 'scrypt'

gem 'redcarpet'
gem 'pygments.rb'

gem 'git'
gem 'fpm', :git => "https://github.com/slact/fpm.git"

#rack stuff
gem 'warden'
gem 'rack-contrib'
gem 'rack-abstract-format'
gem 'rack-respond_to'
gem 'rack-referrals'
gem 'muster'
gem 'rack-attack'
gem 'chrome_logger'
gem 'rack-detect-tor'
gem 'haml'
gem 'racksh'
gem 'redis-rack'

#rack reloader
gem "mr-sparkle"

gem "redd"

gem 'hiredis'
gem 'redis', :require => ["redis/connection/hiredis", "redis"]

gem 'queris', git: "https://github.com/slact/queris.git"

gem 'hobbit', git: 'https://github.com/slact/hobbit.git'
#if File.directory?(queris_path= File.expand_path("../hobbit"))
#  gem 'hobbit', :path => queris_path
#else
#  gem 'hobbit', github: 'slact/hobbit'
#end

gem 'hobbit-contrib', git: 'https://github.com/slact/hobbit-contrib.git', require: 'hobbit/contrib'
gem 'i18n'
gem 'rack-protection'
# Uncomment this if you want to use Sass
#gem 'sass'
gem 'sprockets'
gem 'tilt'
gem 'thin'

group :development do
  gem "pry"
  gem "pry-coolline"
  gem "pry-doc"
  gem "pry-remote"
  #gem "pry-rescue"
  gem "pry-git"
  gem "pry-theme"
  gem 'pry-debundle'
  gem "pry-byebug", "~> 1.3.3"
  
  #gem 'awesome_print'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'rake'
end

group :test do
  gem 'minitest', require: 'minitest/autorun'
  gem 'minitest-reporters'
  gem 'rack-test', require: 'rack/test'
end
