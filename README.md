# Base Bootstrap

### Rails App with Mongoid

 MongoDB is used as a datastore with the "Mongoid":http://mongoid.org/
gem for quick development without schemas or migrations.


## Quick start

Clone the git repo - `git clone https://github.com/fabianoleite/base_bootstrap.git` -
 or [download it](https://github.com/fabianoleite/base_bootstrap/zipball/master)

* Rename all BaseBootstrap references to your own app name
* Rename the session key on config/initializers/session_store.rb
* Generate a new secret token with `rake secret` and replace it on config/initializers/secret_token.rb

## Dependencies

### Before running this app, you will need:

* The Ruby language (version 1.9.3)
* Rails 3.2.x
* A working installation of "MongoDB":http://www.mongodb.org/ (version 1.6.0 or newer)

See "Installing Rails 3.2.x":http://railsapps.github.com/installing-rails.html for detailed instructions and advice.

### Installing MongoDB

If you don't have MongoDB installed on your computer, you'll need to install it and set it up to be always running on your computer (run at launch). On Mac OS X, the easiest way to install MongoDB is to install "Homebrew":http://mxcl.github.com/homebrew/ and then run the following:

<pre>
brew install mongodb
</pre>

Homebrew will provide post-installation instructions to get MongoDB running. The last line of the installation output shows you the MongoDB install location (for example, */usr/local/Cellar/mongodb/1.8.0-x86_64*). You'll find the MongoDB configuration file there. After an installation using Homebrew, the default data directory will be */usr/local/var/mongodb*.
