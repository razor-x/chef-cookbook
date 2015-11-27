source 'https://rubygems.org'

gem 'chef', '~> 12.5.1'
gem 'berkshelf', '~> 4.0.1'

group :development do
  gem 'knife-cookbook-doc', '~> 0.16'

  gem 'yard', '~> 0.8'
  gem 'yard-redcarpet-ext', '~> 0.0.3'
  gem 'redcarpet', '~> 3.3'
  gem 'github-markup', '~> 1.4'

  gem 'rubocop', '~> 0.35'
  gem 'foodcritic', '~> 5.0'

  gem 'rake', '~> 10.4'

  gem 'thor', '~> 0.19'

  gem 'guard', '~> 2.13'
  gem 'guard-shell', '~> 0.7'
  gem 'guard-yard', '~> 2.1'
  gem 'guard-rubocop', '~> 1.2'
  gem 'guard-foodcritic', '~> 2.0'
end

group :unit do
  gem 'rspec', '~> 3.3'
  gem 'chefspec', '~> 4.4'
  gem 'simplecov', '~> 0.10'
  gem 'codecov', '~> 0.1'
  gem 'guard-rspec', '~> 4.6'
end

group :integration do
  gem 'test-kitchen', '~> 1.4'
  gem 'kitchen-sync', '~> 1.1'
  gem 'kitchen-vagrant', '~> 0.18'
  gem 'guard-kitchen', '~> 0.0.2'
end

gem 'fuubar', '~> 2.0', group: [:development, :unit]
