Level 07 - Authentication With Devise
-----------

#Overview
* Install Devise
* Add a root route to the hello world action
* Install the Devise Views
* Allow Users to Register
* Allow Users to Login
* Allow Users to Logout
* Restrict All things routes to logged in users
* Redirect to the things index page on login
* Redirect to the root page on logout
* Bonus: Update Devise views to match bootstrap

#Level Resources

* [https://github.com/plataformatec/devise#getting-started](https://github.com/plataformatec/devise#getting-started)
* [http://guides.rubyonrails.org/routing.html](http://guides.rubyonrails.org/routing.html)

#Do it for Yourself

* Branch name for this feature: 'authentication'

* Run ```git checkout -b authentication``` to create a switch to the new branch

* Add your root route to the hello world page

* Add Devise to your app and create a User model

* Install the Devise Views

* Add an Authentication check to all actions on the Things controller

* Investigate how to set the redirects on login and logout and implement: 
	* Redirect to things index on login
	* Redirect to root route on logout


__After__ you've made your changes, commit and push your branch up to your repo

```
	(seeding)]$ git push --set-upstream origin authentication
```

#Testing your Progress

What happens when you....?

* Run ```rails s```
* View [http://localhost:3000/things](http://localhost:3000/things) while your server is running
* View and Edit some of the seeded Thing
* DELETE ALL YOUR DATA! - Run ```rake db:reset```

#Update Your README.md

* Explain what you did
* Explain each of these devise behaviours:
	* Confirmable
	* Recoverable
	* Registerable
	* Rememberable
	* Trackable
	* Timeoutable
	* Validatable
	* Lockable



