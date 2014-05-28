Things
=====================

Golp is a database of ```Thing```s

#Level 01 - A New App

##Before we Start
* We are making a new app called golp which will eventually run on Heroku

* The core of our app will be Things which are stored in a postgres database

* We will use rspec instead of test unit so we'll use the -T option to the ```rails new``` command

* We don't need coffeescript so we'll comment that out in our Gemfile

```
    # gem 'coffee-rails'
```

* We'll add our default set of development gems including

```
	group :development do
		gem 'quiet_assets'
		gem 'better_errors'
	end
```

And maybe these too:

Support for chrome rails plugin:

    group :development do
      gem 'meta_request' # https://chrome.google.com/webstore/detail/railspanel/gjpfobpafnhjhbajcjgccbbdofdckggg
    end

For pry / debugging fans:

    group :development do
      gem 'binding_of_caller' # Going up the stack  binding.of_caller(2).eval('var = :hello')
      gem 'awesome_print' # In the rails console: ap Account.limit(2).all
      gem 'pry-rails' # Uses pry instead of irb for the console
      gem 'pry-byebug'
    end

* Add RSpec after reading this:
[how-can-i-tell-rails-to-use-rspec-instead-of-test-unit-when-creating-a-new-rails](http://stackoverflow.com/questions/6728618/how-can-i-tell-rails-to-use-rspec-instead-of-test-unit-when-creating-a-new-rails)

    gem 'rspec-rails'

    $ bundle install
    $ rails g rspec:install


##Level Resources

* https://github.com/evrone/quiet_assets
* https://github.com/charliesome/better_errors
* https://chrome.google.com/webstore/detail/railspanel/gjpfobpafnhjhbajcjgccbbdofdckggg
* https://github.com/deivid-rodriguez/pry-byebug

##Let's Do It

* Branch name for this feature: 'getting_started'

This one is a little tricky for branch naming because our git repo won't exist until after we run rails new

So after we run rails new, we cd to the app directory and run ```git init```. Then, before we add or commit any files,
we run ```git checkout -b getting_started``` to create a switch to the new branch

__After__ you've made your changes, commit and push your branch up to your repo

```
	$ git push origin getting_started 
```



#Level 02 - A Static Home Page with Bootstrap

* Add a Pages Controller with a home action, using the

* Add bootstrap 3 to application / layout

Add Bootstrap generators:

* https://github.com/decioferreira/bootstrap-generators


#Level 1 - Basic Scaffold


* Add Bootstrap generators 
* Add the bootstrap generators so that we can use built in generators later on
* 
* [bootstrap-generators](https://github.com/decioferreira/bootstrap-generators)



Each Thing has:

* id:integer -  Primary Key
* name:string - The name of the thing
* description:text - A free form text description

We are going to use the scaffold generator to get started

Learn about scaffold generators and run it

Understand what it did, and how EVERYTHING works

#Level 2 - Adding a Search Form

* Use a Form Object
* Validate the search input

#Level 3 - Adding Pagination

* Use Kaminari Gem


#Level 2 - Adding a Location

Each Thing now needs:

* latitude:float - Latitude of Thing
* longitude:float - Longitude of Thing

This needs a migration




#Level 3 - Searching By Location






#Level 4 - Adding Reverse Geocoding

Reverse Geocoding

* full_street_address - GeoCoded Street Address
