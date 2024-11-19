source "https://rubygems.org"

# Rails Framework
gem "rails", "~> 7.2.1", ">= 7.2.1.2"

# Autenticación de usuarios
gem "devise"

# Active Storage para el manejo de archivos e imágenes
# gem "image_processing", "~> 1.2" # Descomentar si necesitas variantes de imagen con Active Storage

# Motor de plantillas SCSS y Bootstrap para el frontend
gem "bootstrap-sass", "~> 3.3.5"
gem "sassc-rails"

# Manejo de JavaScript y frontend moderno
gem "webpacker"
gem "jquery-rails"

# Pipeline de activos
gem "sprockets-rails"

# Base de datos
gem "sqlite3", "~> 1.4"

# Servidor web para Rails
gem "puma", ">= 5.0"

# Soporte para módulos ESM en JavaScript
gem "importmap-rails"

# Framework Hotwire
gem "turbo-rails"    # Para navegación SPA-like
gem "stimulus-rails" # Framework de JavaScript

# Manejo de JSON API
gem "jbuilder"

# Manejo de archivos adjuntos (opcional)
gem "paperclip", "~> 5.0.0"
gem "aws-sdk-s3", "~> 1.0" # Para almacenamiento en S3 de Amazon

# Zona horaria para sistemas Windows
gem "tzinfo-data", platforms: %i[ mswin mswin64 mingw x64_mingw jruby ]

# Reducción de tiempos de arranque
gem "bootsnap", require: false

group :development, :test do
  # Depuración
  gem "debug", platforms: %i[ mri mswin mswin64 mingw x64_mingw ], require: "debug/prelude"

  # Análisis de seguridad
  gem "brakeman", require: false

  # Estilo de código Ruby para Rails
  gem "rubocop-rails-omakase", require: false
end

group :development do
  # Consola para manejo de errores en desarrollo
  gem "web-console"

  # Resaltar ubicación de errores
  gem "error_highlight", ">= 0.4.0", platforms: [ :ruby ]
end

group :test do
  # Pruebas de sistema
  gem "capybara"
  gem "selenium-webdriver"
end
