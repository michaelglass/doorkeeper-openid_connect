source 'https://rubygems.org'

# use Rails version specified by environment
ENV['rails'] ||= '5.2.0'
gem 'rails', "~> #{ENV['rails']}"

if ENV['rails'] =~ /^5./
  gem 'rails-controller-testing'
end

gemspec
