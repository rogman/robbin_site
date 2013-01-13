source :rubygems

# Server requirements
gem 'unicorn'
gem 'rainbows'

# Project requirements
gem 'rake'
gem 'padrino', :git => 'git://github.com/padrino/padrino-framework.git'

# Component requirements
gem 'bcrypt-ruby', :require => 'bcrypt'
gem 'erubis', '~> 2.7.0'
gem 'activerecord', :require => 'active_record'
gem 'mysql2'
gem 'dalli'
gem 'kgio'
gem "second_level_cache", :git => "git://github.com/csdn-dev/second_level_cache.git"
gem 'acts-as-taggable-on', :git => "git://github.com/robbin/acts-as-taggable-on.git"

# Development requirements
group :development do
  gem 'thin'
  gem 'pry'
end

# Test requirements
group :test do
  gem 'minitest', "~>2.6.0", :require => "minitest/autorun"
  gem 'rack-test', :require => "rack/test"
  gem 'factory_girl'
end