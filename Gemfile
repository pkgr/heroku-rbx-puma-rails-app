source "http://rubygems.org"

# use Rubinius
ruby "2.1.0", :engine => "rbx", :engine_version => "2.2.1"

# add the Puma gem
gem "puma", "~> 2.2.2"

# not a part of the heroku/rbx/puma demo
# just here to quiet the other noise
gem "rails", "~> 3.2.12"

group :development do
  gem "sqlite3"
end

group :assets do
  gem "uglifier"
end

group :production do
  gem "pg"
end
