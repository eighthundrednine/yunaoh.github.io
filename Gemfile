source "https://rubygems.org"

# Ruby Requirement
ruby '2.0.0'

# Gem Requirements
gem 'sass',  '>=3.4.3'
gem 'jekyll',  '2.4.0'

# Github Pages Requirements
require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)
gem 'github-pages', versions['github-pages']

# Custom Gems (by Kevin Oh)

# For Font-Awesome Icon Library
gem 'font-awesome-sass' 
