# README

This is a web app in which user can chat in real-time built using the [Rails](http://rubyonrails.org) framework.


### Requirements
* Rails 5.2.2
* PostgreSQL

### Running Locally

Make sure you have [Ruby](https://www.ruby-lang.org), [Bundler](http://bundler.io) installed.

```sh
git clone https://github.com/aakashjhawar/ChatApp.git #You can also clone your own fork
cd ChatApp
bundle install
rails db:create
rails db:create
rails s
```
Your app should now be running on [localhost:3000](http://localhost:3000/).

## Deploying to Heroku

```
heroku create
git push heroku master
heroku run rake db:migrate
heroku open
```

## Documentation

For more information about using Ruby on Heroku, see these Dev Center articles:

- [Ruby on Heroku](https://devcenter.heroku.com/categories/ruby)
- [Getting Started with Ruby on Heroku](https://devcenter.heroku.com/articles/getting-started-with-ruby)
- [Heroku Ruby Support](https://devcenter.heroku.com/articles/ruby-support)
