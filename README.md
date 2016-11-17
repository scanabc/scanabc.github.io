# Scanabc Website

## Editing and testing your own machine

```shell
git clone https://github.com/nkapu/webkapu.git
cd webkapu
ruby --version # needs to be > 2.0.0
sudo gem install bundler
bundle install
bundle exec jekyll serve # --watch is default after jekyll 2.4.0
```

Page will be as default at localhost:4000

### Requirements

* Ruby >= 2.0.0

* [bundler](http://bundler.io/)
  * ```gem install bundler```

Agency Jekyll theme

 Agency theme based on [Agency bootstrap theme](http://startbootstrap.com/templates/agency/)

## How to use

### Portfolio

Portfolio projects are in '/_posts'

Images are in '/img/portfolio'

### About

Images are in '/img/about/'

### Team

Team members and info are in '_config.yml'

Images are in '/img/team/'

### Demo

View this jekyll theme in action [here](https://y7kim.github.io/agency-jekyll-theme)

=========
For more details, read [documentation](http://jekyllrb.com/)
