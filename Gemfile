source "https://rubygems.org"

ruby ">= 2.5"

gem "github-pages", ">= 201", :group => :jekyll_plugins
gem "netrc", "~> 0.11.0"
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?

#group :jekyll_plugins do
#end

install_if -> { RUBY_PLATFORM =~ %r!java|mingw|mswin! } do
  gem "tzinfo"
  gem "tzinfo-data"
end
