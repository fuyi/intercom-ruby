source "http://rubygems.org"

gemspec

group :development, :test do
  gem 'fakeweb', "~> 1.3"
#  gem 'm'
#  gem 'pry-byebug'
  platforms :jruby do
    gem 'json-jruby'
    gem 'jruby-openssl'
  end
  platforms :ruby_18 do
    gem 'json_pure'
  end
end
