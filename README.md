# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* Run it Locally

Run `$ rails s`

* How to run the test suite

Run `$ bundle exec rspec`

* Services (job queues, cache servers, search engines, etc.)

* Dockerization

 Build `$ docker build -t [docker_hub_username]/todos-api .`

 Run `$ docker run --rm -it -p 3000:3000 -e "PORT=3000" [docker_hub_username]/todos-api`

 Push to ducker hub `$ docker push YOUR_USERNAME/todos-api`

 Then go ask a friend to try your app by running this command :) ^^

 Run `$ docker run --rm -it -p 3000:3000 -e "PORT=3000" YOUR_USERNAME/todos-app`

* Deployment instructions

* ...
