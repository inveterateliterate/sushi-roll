# Sushi Roll

Registration for Sushi Closer's annual Sushi Roll.

## Tech Notes
### Stack
+ Ruby 2.6.5
+ Rails 6.3
+ Node >= 10
+ Postgres
+ Redis
+ Sidekiq

### Work Locally
+ `git clone git@github.com:inveterateliterate/sushi-roll.git`
+ `cd sushi-roll`
+ `bundle install`
+ `yarn install`
+ `bundle exec rake db:create db:migrate db:seed`
+ `rake start`
+ `open localhost:3000`
+ running workers:
  + `redis-server`
  + `bundle exec sidekiq`
