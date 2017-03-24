# Origin story:

    nvm install node
    Downloading and installing node v7.7.4...
    brew update
    brew install yarn

    bundle exec rails new . --webpack=react --database=postgresql

# Versions:

    Rails version: 5.1.0.rc1
    Ruby version: 2.3.1 (x86_64-darwin15) # at least

# Deployment (heroku, e.g.):

    heroku create
    git push heroku master

# Installation

    git clone git@github.com:rthbound/fluffy-octo-spoon.git # or whatever

    cd fluffy-octo-spoon # or whatever

    ./bin/setup

    bundle exec rake test

# Development Server:


In one shell run the web server:

    bundle exec puma -C config/puma.rb -p 3000

In another run webpack dev server:

    ./bin/webpack-dev-server

### Or use foreman

Foreman can start both the webpack server and rails server for you:

    foreman start -f Procfile.dev

Using Procfile.dev since we want to deploy to Heroku and we don't want it running this Procfile.

# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


