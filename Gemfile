source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.4'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0.0'
# Use postgresql as the database for Active Record
gem 'pg', '>= 0.18', '< 2.0'
# Use Puma as the app server
gem 'puma', '~> 3.11'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 4.0'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7'
# Simple, efficient background processing for Ruby
gem 'sidekiq' , '< 6.0'
gem "sidekiq-cron"
# Emails Style
gem 'premailer-rails'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
gem 'bcrypt', '~> 3.1.7'
# Use Active Storage variant
gem 'image_processing', '~> 1.2'
# Flexible authentication solution for Rails with Warden.
gem 'devise'
# Awesome Print
gem 'awesome_print'
# JWT
# gem 'jwt'
# Rest Client
gem 'rest-client'
# i18n
gem 'rails-i18n'
# Read and Write Spreadsheets
gem "roo"
# The authorization Gem for Ruby on Rails.
gem 'cancancan'
# Gem HTTP para correios e gerencianet
# gem "http"
# Find Brazilian addresses by zipcode, directly from Correios database
# gem 'correios-cep'
# Gerencianet - Criacao de Assinaturas
gem 'gerencianet'
# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false
# PDF
gem 'wicked_pdf'
gem 'wkhtmltopdf-binary'
# Cloudinary
gem 'cloudinary'
# GeoCoder
# gem 'geocoder'
# Envio de emails com Errors
gem 'exception_notification'
# Sitemap
gem 'sitemap_generator'
# PDF.js
# gem 'pdfjs_viewer-rails'
# WickedPDF on Heroku
# gem 'wkhtmltopdf-heroku', '2.12.5.0'
# Meta tags
gem 'meta-tags'
# TinyMCE Editor
gem 'tinymce-rails'
gem 'tinymce-rails-langs'
# MiniMagick
gem 'mini_magick'
# PDF
gem 'prawn-rails'
# GCP e Google Meet
gem 'google-apis-calendar_v3'
# Serialization
gem 'active_model_serializers'


group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of web drivers to run system tests with browsers
  gem 'webdrivers'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

