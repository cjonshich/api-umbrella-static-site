source "https://rubygems.org"

# For faster file watcher updates on Windows:
gem "wdm", "~> 0.1.0", platforms: [:mswin, :mingw]

# Windows does not come with time zone data
gem "tzinfo-data", platforms: [:mswin, :mingw, :jruby]

# Middleman Gems
gem "middleman", "~> 4.2.1"
gem "middleman-livereload", "~> 3.4.6"

# Environment specific config with environment variables
gem "dotenv", "~> 2.5.0"

# Syntax highlighting
gem "middleman-syntax", "~> 3.0.0"

# Deploy to GitHub Pages
gem "middleman-gh-pages", "~> 0.3.1"

# Assets
gem "middleman-sprockets", "~> 4.1.0"

# Bootstrap
gem "bootstrap-sass", "~> 3.3.7"

# Icons
gem "font-awesome-sass", "~> 4.7.0"

source "https://rails-assets.org" do
  # jQuery
  gem "rails-assets-jquery", "~> 3.3.1"

  # Programmatic bootstrap modals
  gem "rails-assets-bootbox", "~> 4.4.0"

  # Form validation
  gem "rails-assets-parsleyjs", "~> 2.8.1"
end

group :development do
  # Deployment
  gem "capistrano", "~> 3.11.0"
  gem "capistrano-rsync-bladrak", "~> 1.4.2"
end
