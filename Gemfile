source 'https://rubygems.org'
ruby '2.1.1'
gem 'rails', '4.1.8'
gem 'spring',        group: :development
gem 'devise'
gem 'devise-i18n'
gem 'pg'
gem 'pundit'
gem "active_model_serializers"
gem "grape"
gem "grape-active_model_serializers"
gem "grape-swagger-rails"
gem "rack-cors", require: "rack/cors"


group :development do
  gem 'better_errors'
  gem 'binding_of_caller', :platforms=>[:mri_21]
  gem 'foreman'
  gem 'rails_layout'
  gem 'spring-commands-rspec'
end
group :development, :test do
  gem 'factory_girl_rails'
  gem 'faker'
  gem 'pry-rails'
  gem 'pry-rescue'
  gem 'rspec-rails'
  gem 'thin'
  gem 'annotate', '2.5.0'
end
group :production do
  gem 'puma'
  gem 'rails_12factor'
end
group :test do
  gem 'capybara'
  gem 'database_cleaner'
  gem 'launchy'
  gem 'selenium-webdriver'
  gem 'email_spec'
  gem 'shoulda-matchers'
end
