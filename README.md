You need:

* Ruby 2.1.0 and Rubygems
* Bundler gem

Then, from the command line, run:

    bundle install
    bundle exec rake db:create
    bundle exec rake db:migrate
    bundle exec rake db:seed
    bundle exec rails server

Open the application in:

    http://localhost:3000