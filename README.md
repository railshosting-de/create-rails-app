# wrapper-rails

Creates a docker based rails wrapper app using the quickstart-rails docker image.

## Prerequisites

To use create-rails-app, you must have:

- git
- docker
- docker-compose

## Installation

The rails wrapper app is tested on Linux and MacOS.

1. Install create-rails-app.

   ~~~ sh
   git clone https://github.com/railshosting-de/wrapper-rails.git
   sudo mv rails /usr/local/bin/rails
   ~~~

2. Pull the docker-quickstart image

   ~~~ sh
   docker pull railshosting/quickstart-rails
   ~~~

3. Create new Rails app with mysql dbms

   ~~~ sh
   rails new test-app -d mysql
   ~~~

4. Run app

   ~~~ sh
   cd test-app
   docker-compose up
   ~~~

5. Open app in browser

   http://localhost:3000


## Customization

You can find the source code of the quickstart-rails image here:

https://github.com/railshosting-de/quickstart-rails.git