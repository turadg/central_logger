source "http://rubygems.org"

gem "rake"
gem "bundler"
gem "mongo", '~> 1.4'
gem "bson_ext"

group :development do
  # adds Bundler support for gemspec generation
  gem "jeweler", "~> 1.5"
  gem "shoulda"
  gem "i18n"
  gem "activesupport"
  gem "mocha"
  gem (RUBY_VERSION =~ /^1\.9/ ? "ruby-debug19" : "ruby-debug")
end
