source "http://rubygems.org/"

gemspec

group :development do
  gem "jruby-openssl", :platform => :jruby
  gem "rcov", ">= 0.9.8", :platform => :mri_18
  gem "childprocess", :platform => :mri
end

if RUBY_VERSION < "1.9"
  gem 'rubyzip', '~> 0.9'
end
