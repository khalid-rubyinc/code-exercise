# RFA Code Exercise
This exercise involves improving a fictional subset of a Ruby on Rails 5.x application.  It only contains a model, controller, and two views.

You should assume the technology stack used for this code includes:
* Ruby on Rails 5.x
* Ruby 2.3.x (MRI)
* PostgreSQL Database
* ERB
* jQuery
* Moment.js

## Instructions

Refactor and improve the code.  Add directories/files as needed.

You are not expected to run the code or make this work as a real Rails application.

## Installing RVM
Ruby Environment Manager
```
curl -sSL https://get.rvm.io | bash
```

## Install Ruby 2.3.3
MRI Ruby 2.3.3
```
rvm install ruby-2.3.3
```

## Install PostgreSQL
Our relational database
```
brew install postgresql
```

Start PostgreSQL service
```
brew services start postgresql
```

## Run database migration

```
bundle exec rake db:reset db:create db:migrate
```

## Install bower
Javascript package manager

```
npm -g install bower
```

## Installing Moment & Jquery
Installing dependent javascript libraries.
```
bundle exec rake bower:install
```