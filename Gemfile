source "http://rubygems.org"

gem   'multi_json',  "~> 1.1"
gem   'yajl-ruby',   "~> 1.1", :platform => :mri
gem   'json',                  :platform => :jruby

# Only necessary if you want to use Configliere::Prompt
gem   'highline',    ">= 1.5.2"


group :development do
  gem 'bundler',     "~> 1"
  gem 'jeweler',     "~> 1.6"
  gem 'pry'
end

group :docs do
  gem 'yard',        ">= 0.7"
  gem 'RedCloth',    "~> 4.2"
  gem 'redcarpet',   "~> 2.1"
end

group :test do
  gem 'spork',       "~> 0.9.0.rc5"
  gem 'rspec',       "~> 2.8"
  gem 'guard',       ">= 1.0"
  gem 'guard-rspec', ">= 0.6"
  gem 'guard-yard'
  gem 'guard-process'

  if RUBY_PLATFORM.include?('darwin')
    gem 'growl',      ">= 1"
    gem 'rb-fsevent', ">= 0.9"
    # gem 'ruby_gntp'
  end
  gem 'simplecov',   ">= 0.5", :platform => :ruby_19
end
