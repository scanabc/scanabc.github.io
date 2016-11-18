# Scanabc Website

## Editing and testing your own machine

```shell
git clone https://github.com/nkapu/webkapu.git
cd webkapu
ruby --version # needs to be > 2.0.0
sudo apt-get install ruby-dev zlib1g-dev liblzma-dev
sudo gem install bundler
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
