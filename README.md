# Overview

Site built with jekyll and hosted on GitHub Pages.

# Local Setup

```
brew install ruby
echo 'export PATH="$(ruby -e "puts Gem.user_dir")/bin:$PATH"' >> ~/.zshrc
gem install --user-install bundler jekyll
bundle install
bundle exec jekyll serve
```
