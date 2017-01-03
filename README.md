# docker-rails5

* Ruby on Rails 5 Sample Application on Docker
* This is effective when making a new rails app.

## Requirement
* Docker >= 1.12

## Usage
* Build
```
$ cd /path/to/docker-rails5
$ docker-compose build
```

* Database creation
```
$ docker-compose run rails rails db:create
```

* Up
```
$ docker-compose up -d
```

* http://127.0.0.1

* Run tests(For Mac)
```
$ bundle exec rspec
```
