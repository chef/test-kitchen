source "https://rubygems.org"

gemspec
gem "appbundler"
gem "pry"
group :test do
  gem "rake"
  gem "rb-readline"
  gem "aruba",     ">= 0.11", "< 3.0"
  gem "countloc",  "~> 0.4"
  gem "cucumber",  ">= 9.2", "< 10"
  gem "fakefs",    "~> 2.0"
  gem "maruku",    "~> 0.6"
  gem "minitest",  "~> 5.3", "< 6.0"
  gem "mocha",     "~> 2.0"
end

group :integration do
  gem "chef-cli"
  gem "kitchen-dokken"
  gem "kitchen-inspec"
  gem "kitchen-vagrant"
end

group :chefstyle do
  gem "chefstyle", "2.2.3"
end
