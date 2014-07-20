source 'https://rubygems.org'

gemspec

group :development do
  gem 'cocoapods',    :git => "https://github.com/CocoaPods/CocoaPods.git", :branch => 'master'
  gem 'claide',       :git => "https://github.com/CocoaPods/CLAide.git", :branch => 'master'
  gem 'bacon'
  gem 'mocha-on-bacon'
  gem 'mocha'
  gem 'prettybacon'

  if RUBY_VERSION >= '1.9.3'
    gem 'rubocop'
    gem 'codeclimate-test-reporter', :require => nil
    gem 'simplecov'
  end
end
