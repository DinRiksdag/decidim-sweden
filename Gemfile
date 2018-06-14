# frozen_string_literal: true

source "https://rubygems.org"

ruby RUBY_VERSION

gem "decidim", git: "https://github.com/decidim/decidim.git"

#gem 'decidim-generators', git: "https://github.com/decidim/decidim-generators.git"
#gem 'decidim-consultations', git: "https://github.com/decidim/decidim-module-consultations.git"
#gem 'decidim-initiatives', git: "https://github.com/decidim/decidim-initiatives.git"

# gem "decidim-riksdagen", git: "https://github.com/DinRiksdag/decidim-module-riksdagen.git"
# gem "decidim-export", git: "https://github.com/PierreMesure/decidim-user-export.git"

gem "puma", "~> 3.0"
gem "uglifier", "~> 4.1"

gem "faker", "~> 1.8"

#gem 'iconv'

group :development, :test do
  gem "byebug", "~> 10.0", platform: :mri

  gem "decidim-dev", git: "https://github.com/decidim/decidim.git"
end

group :development do
  gem "letter_opener_web", "~> 1.3"
  gem "listen", "~> 3.1"
  gem "spring", "~> 2.0"
  gem "spring-watcher-listen", "~> 2.0"
  gem "web-console", "~> 3.5"
end

group :production do
  gem 'passenger'
  gem 'fog-aws'
  gem 'dalli'
  gem 'sendgrid-ruby'
  gem 'newrelic_rpm'
  gem 'lograge'
  gem 'sentry-raven'
  gem 'sidekiq'
end
