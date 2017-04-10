source "https://rubygems.org"

gem "hashie"
# trying to include hashie makes final test fail, ignoring hashie
# lets me pass the hasie related test.

gem "sinatra", '1.4.4'
gem "octokit", '~> 2.0'
gem "awesome_print", :git => "git://github.com/awesome-print/awesome_print.git"

# very confused.
#commenting out line 5 gets the
#bundler_spec.rb test on line 42 to PASS ?!
#uncommenting line 5 makes both "groups" tests fail.




# group :development do
#   gem "pry"
# end

gem "pry", :group => "development"

group :test do
  gem "rspec"
end
