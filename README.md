# README

This application was written to power keeptheshipsafloat.com, a family project to help people locate charities during the Coronavirus.

# Database
The application runs using Postgresql.  To install Postgresql, you can use homebrew, by running `brew install postgresql`.  If you choose not to automatically start Postgres when your computer starts, you can use `pg_ctl -D /usr/local/var/postgres start` to start it when your computer kicks off and you want to work on this project.

# Other requirements
You will also need to install node in order to run this application.  Please install by running `brew install nodejs`.  Yarn is also required: `brew install yarn`

# Starting the application
First you will need to create a database by running `rails db:create`.  Secondly, you will need to run `rails webpacker:install`.
