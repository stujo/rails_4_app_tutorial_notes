Level 05 - Validations
-----------

#Overview
* Add FactoryGirl gem for testing
* Write RSpectests for the validations we want
* Add validations to Thing model

#Level Resources

* [https://github.com/thoughtbot/factory_girl/blob/master/GETTING_STARTED.md](https://github.com/thoughtbot/factory_girl/blob/master/GETTING_STARTED.md)

#Do it for Yourself

* Branch name for this feature: 'validations'
* Run ```git checkout -b validations``` to create a switch to the new branch


* The following validations are required for the ```Thing``` model
  * ```name``` is required and must be between 2 and 100 in length
  * ```description``` is option but can be no longer than 1000 

* Add FactoryGirl (Research Required)

* Write RSpec tests using FactoryGirl for these yet-to-be-written validations

* Update Thing to validate according to these new rules and tests

__After__ you've made your changes, commit and push your branch up to your repo

```
	(validations)]$ git push --set-upstream origin validations
```

#Testing your Progress

What happens when you....?

* Run ```rspec```
* Run ```rails s```
* View [http://localhost:3000/things](http://localhost:3000/things) while your server is running
* Add some Things but make some errors
* Edit some Things but make some errors

