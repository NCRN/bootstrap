<p align="center">
  <img src="https://raw.githubusercontent.com/nationalparkservice/bootstrap/master/img/apple-touch-icon-144x144-precomposed.png" alt="NPS Arrowhead">
</p>

# NPS Bootstrap

[![Circle CI](https://circleci.com/gh/nationalparkservice/bootstrap.svg?style=svg)](https://circleci.com/gh/nationalparkservice/bootstrap)

Bootstrap is a sleek, intuitive, and powerful front-end framework that makes web development faster and easier. It is created and maintained by [Mark Otto](http://twitter.com/mdo) and [Jacob Thornton](http://twitter.com/fat). This version is customized by the [National Park Service](http://www.nps.gov) to fit into the agency's graphic identity, and it is used on [http://www.nps.gov](http://www.nps.gov) and other agency websites.

To get started, check out [http://www.nps.gov/npmap/bootstrap/](http://www.nps.gov/npmap/bootstrap/)!

**Note:** All National Park Service customizations reside in files that end with `-nps`.

## Build

1. Install [Node.js](http://nodejs.org/download)
1. Clone repository: `git clone https://github.com/nationalparkservice/bootstrap`
1. `cd bootstrap`
1. `npm install`
1. Install Grunt CLI globally: `npm install -g grunt-cli`
1. Run `grunt dist docs` to build the CSS, JavaScript, and docs
1. Install [Jekyll](http://jekyllrb.com/)
1. `gem install rouge`
1. Run `jekyll serve`
1. Browse to `http://localhost:9001/npmap/tools/bootstrap/

## CDN

You can also load Bootstrap directly from the National Park Service's CDN:

    http://www.nps.gov/lib/bootstrap/3.3.2/css/nps-bootstrap.min.css
    http://www.nps.gov/lib/bootstrap/3.3.2/js/nps-bootstrap.min.js
