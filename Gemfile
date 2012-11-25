source 'https://rubygems.org'
gem 'rails', '3.2.9'
group :production, :staging do
  gem "pg"
end
group :development, :test do
  gem "sqlite3-ruby", :require => "sqlite3"
end
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
end
gem 'jquery-rails'
gem "thin", ">= 1.5.0", :group => :production
gem "compass-rails", ">= 1.0.3", :group => :assets
gem "zurb-foundation", ">= 3.2.0", :group => :assets
gem "quiet_assets", ">= 1.0.1", :group => :development
