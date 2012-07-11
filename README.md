## Base Bootstrap
==========================

A Rails app skeleton, so I don't have to do it again and again, with Mongoid
* MongoDB is used as a datastore with the "Mongoid":http://mongoid.org/
  gem for quick development without schemas or migrations.


## Quick start

Clone the git repo - `git clone https://github.com/fabianoleite/base_bootstrap.git` -
 or [download it](https://github.com/fabianoleite/base_bootstrap/zipball/master)

* Rename all BaseBootstrap references to your own app name
* Rename the session key on config/initializers/session_store.rb
* Generate a new secret token with `rake secret` and replace it on config/initializers/secret_token.rb

## Dependencies

# Before running this app, you will need:

* The Ruby language (version 1.9.3)
* Rails 3.2.x
* A working installation of "MongoDB":http://www.mongodb.org/ (version 1.6.0 or newer)
