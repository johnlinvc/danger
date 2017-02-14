source "https://rubygems.org"

gemspec
gem "danger-gitlab"

if RUBY_VERSION == "2.3.1"
  gem "chandler"
end

# This should get removed when > 3.7.0 comes out
gem "gitlab"

gem "danger-junit", "~> 0.5"
gem "rspec_junit_formatter", git: "https://github.com/JuanitoFatas/rspec_junit_formatter.git", branch: "dump-rspec_junit_formatter-failed-examples"
gem "rubocop"
