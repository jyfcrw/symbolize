source "https://rubygems.org"
gemspec

gem "rake"

group :test do
  gem 'rspec'
  gem 'mongoid'

  gem 'bson_ext', platform: :ruby
  gem 'sqlite3',  platform: :ruby
  gem 'pg',       platform: :ruby

  gem 'activerecord-jdbcmysql-adapter',   platform: :jruby
  gem 'activerecord-jdbcsqlite3-adapter', platform: :jruby

  gem 'i18n' #, '0.6.1'

  if ENV["CI"]
    gem "coveralls", require: false
  end

end
