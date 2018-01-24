source "https://rubygems.org"

gemspec

gem 'dry-events', git: 'https://github.com/dry-rb/dry-events.git', branch: 'master'
gem "dry-monads", git: "https://github.com/dry-rb/dry-monads.git"
gem "dry-matcher", git: "https://github.com/dry-rb/dry-matcher.git"

group :test do
  gem "simplecov"
  gem "codeclimate-test-reporter"
  gem "pry-byebug", platform: :mri
  gem "dry-container"
end

group :tools do
  gem "pry"
  gem "rubocop"
end
