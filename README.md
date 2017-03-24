Origin story:

    nvm install node
    Downloading and installing node v7.7.4...
    brew update
    brew install yarn

    bundle exec rails new . --webpack=react --database=postgresql

Versions:

    Rails version: 5.1.0.rc1
    Ruby version: 2.3.1 (x86_64-darwin15) # at least

Deployment (heroku, e.g.):

    heroku create
    git push heroku master

Installation

    git clone git@github.com:rthbound/fluffy-octo-spoon.git # or whatever

    cd fluffy-octo-spoon # or whatever

    ./bin/setup

    bundle exec rake test
    bundle exec rails s # visit localhost:3000 in browser

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


