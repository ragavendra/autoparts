# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Setup
```
echo "gem 'solidus'" >> Gemfile
echo "gem 'solidus_auth_devise'" >> Gemfile
echo "gem 'therubyracer'" >> Gemfile
```

* To install
```
bundle
```

* To create migrations and configurations
```
bundle exec rails g spree:install
bundle exec rails g solidus:auth:install
bundle exec rake railties:install:migrations
```

* To install migrations models in the database
```
bundle exec rake db:migrate
```

* Starting the rails server
```
bundle exec rails s
```

The storefront will be accessible at [http://localhost:3000/](http://localhost:3000/)
and the admin can be found at [http://localhost:3000/admin/](http://localhost:3000/admin/).

### Default Username/Password

As part of running the above installation steps, you will be asked to set an admin email/password combination. The default values are `admin@example.com` and `test123`, respectively.

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
