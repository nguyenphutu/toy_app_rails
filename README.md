run bundle
  $ bundle install --without production

run migrate
  $ rails db:migrate

run application
  $ rails server

push to heroku
  $ heroku create
  $ git push heroku master

run migrate in heroku application
  $ heroku run rails db:migrate
  
