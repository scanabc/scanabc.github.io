# Scanabc Website

## Editing and testing your own machine

```shell
git clone https://github.com/scanabc/scanabc.github.io.git
cd scanabc.github.io

# On linux
ruby --version # needs to be > 2.0.0
sudo apt-get install ruby-dev zlib1g-dev liblzma-dev

# On Mac
brew install chruby ruby-install xz
## https://www.rubyonmac.dev/how-to-install-ruby-on-macos-12-6-apple-silicon
ruby-install ruby -- --enable-shared
## for this terminal only
source $(brew --prefix)/opt/chruby/share/chruby/chruby.sh
source $(brew --prefix)/opt/chruby/share/chruby/auto.sh
chruby ruby-3.1.2
ruby --version

# On all platforms
gem install bundler
bundle install
bundle exec jekyll serve # --watch is default after jekyll 2.4.0
```

Page will be as default at localhost:4000

### Requirements

* Ruby >= 2.0.0

* [bundler](http://bundler.io/)
  * ```gem install bundler```

## This website is based on Agency Jekyll theme

* <https://github.com/y7kim/agency-jekyll-theme>

* <https://startbootstrap.com/template-overviews/agency/>
