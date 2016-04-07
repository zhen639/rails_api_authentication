# source 'https://ruby.taobao.org/'
source 'https://rubygems.org/'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '>= 5.0.0.beta3', '< 5.1'

gem 'pg'
gem 'active_model_serializers', '~> 0.10.0.rc1'
gem 'devise_token_auth'
gem 'devise', '~> 4.0.0.rc1'

# Use Puma as the app server
gem 'puma'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder', '~> 2.0'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
# gem 'rack-cors'

gem 'activeadmin', '~> 1.0.0.pre2'
gem 'rspec-rails', '>= 3.5.0.beta1'
gem 'ransack',    github: 'activerecord-hackery/ransack'
gem 'kaminari',   github: 'amatsuda/kaminari', branch: '0-17-stable'
gem 'formtastic', github: 'justinfrench/formtastic'
gem 'draper',     github: 'audionerd/draper', branch: 'rails5', ref: 'e816e0e587'
# To fix a Draper deprecation error
gem 'activemodel-serializers-xml', github: 'rails/activemodel-serializers-xml'
# Optional -- only if you already include these gems
gem 'rack-mini-profiler',          github: 'MiniProfiler/rack-mini-profiler'
gem 'database_cleaner', '~> 1.5.0'
# Only for JRuby:
gem 'activerecord-jdbc-adapter',   github: 'jruby/activerecord-jdbc-adapter', platforms: :jruby

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
end

group :development do
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
