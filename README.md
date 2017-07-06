# Basic Water Marketing Site

## About

Our static marketing site powered by [Middleman](https://middlemanapp.com/)
located at [http://www.basicwater.nyc/](http://www.basicwater.nyc/).

## About Middleman

Middleman is a static site generator built in Ruby. This makes it a great fit
for projects that may end up as a Ruby on Rails app. Its minimalistic structure
makes it very easy to work with, and includes support for deploying to Github
Pages.

## Includes

* [Slim](http://slim-lang.com/):
  Simple template markup
* [Coffeescript](http://coffeescript.org):
  Write javascript with simpler syntax
* [Sass (LibSass)](http://sass-lang.com):
  CSS with superpowers
* [Bourbon](http://bourbon.io):
  Sass mixin library
* [Neat](http://neat.bourbon.io):
  Semantic grid for Sass and Bourbon
* [Bitters](http://bitters.bourbon.io):
  Scaffold styles, variables and structure for Bourbon projects.
* [Middleman Live Reload](https://github.com/middleman/middleman-livereload):
  Reloads the page when files change
* [Middleman Deploy](https://github.com/karlfreeman/middleman-deploy):
  Deploy your Middleman build via rsync, ftp, sftp, or git (deploys to Github Pages by default)
* [Proteus](http://thoughtbot.github.io/proteus/):
  Convenient Middleman shortcuts

## Getting Started

Clone this repo
```
git clone git@github.com:basic-water/basicwater.nyc.git
cd basicwater.nyc
```

Install dependencies:
```
./bin/setup
```

Run the server:
```
proteus server
```

## Deploying

Deploy to Github Pages:
```
proteus deploy
```

## Directories

Stylesheets, fonts, images, and JavaScript files go in the `/source/assets/` directory.
Vendor stylesheets and JavaScripts should go in each of their `/vendor/` directories.
