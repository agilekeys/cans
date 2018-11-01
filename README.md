# cans

[![Build Status](https://travis-ci.com/agilekeys/cans.svg?branch=master)](https://travis-ci.com/agilekeys/cans)

## Requestment
* PHP
* composer
* docker
* docker-compose


## Install
```
composer global require "agilekeys/cans" -v
```

## Usage

Argument | Description
------------ | -------------
down | To shutdown local server.
help | To display help infomation.
init | To create config file and initial `docker-compose.yml` file
run | To run single container, name will be listed on `docker-compose.yml` file
up | Run all containers as server (with `-d`, will run on background)



