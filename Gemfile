source 'https://rubygems.org'

gem 'jekyll'
gem 'kramdown'
gem 'coderay'
gem 'rake'
gem 'thor'
gem 'activesupport'
gem 'stringex'


require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']