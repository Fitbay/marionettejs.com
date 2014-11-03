marionettejs.com
================

##### [Experimental](http://marionettejs.github.io/marionettejs.com/)

### Deving

> The Setup

    git clone git@github.com:thejameskyle/marionettejs.com.git
    cd marionettejs.com
    bower install
    npm install
    gem install compass
    git clone git@github.com:marionettejs/backbone.marionette.git

#### Deving the main WWW

    npm run dev

> Then open dist/index.html

#### Deploying the main WWW

    npm run deploy --version v2.X.X

#### Building the annotated source

    npm run compile-docco

#### Building the downloads

    npm run compile-downloads

#### Building the docs

  > Then we need to get the Marionette Repo to generate the build from:

      git clone git@github.com:marionettejs/backbone.marionette.git

  > Then we just have to compile:

      npm run build-docs

  > Start up a static server

      python -m SimpleHTTPServer

  > Checkout some sweet docs

      http://localhost:8000/dist/docs/v2.2.0-pre/marionette.collectionview.html
