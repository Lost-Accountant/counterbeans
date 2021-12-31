source "https://rubygems.org"
gemspec
gem 'wdm', '>= 0.1.0' if Gem.win_platform?
gem "webrick", "~> 1.7"

group :jekyll_plugins do
    #gem 'just-the-docs', '>=0.3.0' # XXX Our Jekyll theme - See https://pmarsceill.github.io/just-the-docs/
    gem "github-pages" # XXX Necessary to reproduce the behaviour of GitHub Pages - When this is loaded, "jekyll" must not be bundled because it's included within
end
