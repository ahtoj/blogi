~~~
brew install rbenv ruby-build
rbenv install 3.2.2
rbenv local 3.2.2
eval "$(rbenv init - bash)"
gem update
gem install jekyll bundler

bundle install
bundle exec jekyll serve --livereload
bundle exec jekyll build --watch

JEKYLL_ENV=production bundle exec jekyll build
~~~
