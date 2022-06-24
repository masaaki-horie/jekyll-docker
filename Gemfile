source "https://rubygems.org"

gem "docker-template"

group :development do
  gem 'envygeeks-rubocop'
  gem 'jekyll-watch'
  gem 'webrick'
  unless ENV["CI"] == "true"
    gem "travis"
    gem "pry"
  end
end
