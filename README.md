== start-r4

This is a project used to start greenfield projects in rails 4.

* To avoid share sensitive information this project configure a ```local_env.yml``` file as proposse [this][http://railsapps.github.io/rails-environment-variables.html] post in the option number 3

* Almost all projects that I've started needs an ```User``` model, so this project has an ```User``` model with basic authentication through devise gem

* It has an Admin site using active-admin gem

* It has a basic bootstrap layout very easy to follow and some static pages to start

== Repository Configuration
* Clone it

* Replace "rails-r4" and the word "Start" with the name of your project in everywhere.
  * Rakefile
  * config/application.rb
  * config/environment.rb
  * config/environments/production.rb
  * config/environments/test.rb
  * config/initializers/active_admin.rb
  * config/initializers/secret_token.rb
  * config/initializers/session_store.rb
  * config/routes.rb

* Change origin: ```git remote set-url origin git://new.url.here```


== App Configuration
* cp ```config/database_example.yml``` to ```config/database.yml``` and configure it

* cp ```config/local_env_example.yml``` to ```config/local_env.yml``` and configure it

* run ```bundle install```

* run test suite ```bundle exec rspec```
