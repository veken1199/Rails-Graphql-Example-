# README

# Rails GraphQL Example

This is a simple example of how to create small API using Rails and GraphQL. 

This project follows [Eddy Karanja tutorial](https://www.a.io/karanjaeddy/build-a-to-do-list-api-with-graphql-api-rails-5-part-1-irjt1e7jm). It will also include extra features and details. 

## How to run this example
### Database:
For this example, we are using Postgres local container that is provided with the source code.
To start Postgres container:
```
$ docker-compose up
```
To makesure all table are created and properly migrated:
```
rails db:create
rails db:migrate
rails db:migrate RAILS_ENV=test
```

### Runing the Tests
To rspec tests at any point:
```
bundle exec rspec
```
