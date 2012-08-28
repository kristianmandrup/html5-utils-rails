# encoding: utf-8

require 'rubygems'
require 'bundler'
begin
  Bundler.setup(:default, :development)
rescue Bundler::BundlerError => e
  $stderr.puts e.message
  $stderr.puts "Run `bundle install` to install missing gems"
  exit e.status_code
end
require 'rake'

require 'jeweler'
Jeweler::Tasks.new do |gem|
  # gem is a Gem::Specification... see http://docs.rubygems.org/read/chapter/20 for more options
  gem.name = "html5-utils-rails"
  gem.homepage = "http://github.com/kristianmandrup/html5-utils-rails"
  gem.license = "MIT"
  gem.summary = %Q{A package of gems containing polyfills for HTML 5 and CSS 3 functionality missing in older browsers}
  gem.description = %Q{Time to use HTML5 and CSS3 now!!!}
  gem.email = "kmandrup@gmail.com"
  gem.authors = ["Kristian Mandrup"]
  # dependencies defined in Gemfile
end
Jeweler::RubygemsDotOrgTasks.new


