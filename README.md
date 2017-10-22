[![Build Status](https://travis-ci.org/frocher/sofreakingboring.svg?branch=master)](https://travis-ci.org/frocher/sofreakingboring)
[![Code Climate](https://codeclimate.com/github/frocher/sofreakingboring/badges/gpa.svg)](https://codeclimate.com/github/frocher/sofreakingboring)

## SoFreakingBoring

![Project Dashboard](https://cloud.githubusercontent.com/assets/7987747/4908740/147eacae-646d-11e4-9971-9ebe095588fe.png)

You can use it online here: [www.sofreakingboring.com](https://www.sofreakingboring.com/).

### Requirements

* Ruby 2.0+
* MySQL for production

### Installation

Before starting SoFreakingBoring you need to follow these steps:

* copy database.yml.example to database.yml.
* copy olb.yml.example to olb.yml.
* copy puma.rb.example to puma.rb
* adapt the three files to your environment
* migrate database with 'rake db:migrate'
* start in development mode with 'rails s'

The Whenever gem is used for cron jobs. To make it work:
* Enter 'whenever' to see what would be added to your cron tab
* Enter 'whenever -w' to add jobs to your crontab.
