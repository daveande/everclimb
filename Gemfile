source 'https://rubygems.org'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'jekyll', '~> 2.4.0'
gem 'github-pages', versions['github-pages']

gem "jekyll-assets"
gem "coffee-script" # We want to write our javascripts in CoffeeScript
gem "uglifier"      # And we want our javascripts to be minified with UglifyJS
gem "sass"          # And we want to write our stylesheets using SCSS/SASS

