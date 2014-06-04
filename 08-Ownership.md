Level 08 - Associations!
-----------

#Overview
* Make ```Thing``` belong to ```User```
* ```User``` has_many ```Thing```s
* Update Seed File to reflect new model associations

#Level Resources



#Do it for Yourself

* Branch name for this feature: 'ownership'

* Run ```git checkout -b ownership``` to create and switch to the new branch




__After__ you've made your changes, commit and push your branch up to your repo

```
	(seeding)]$ git push --set-upstream origin ownership
```

#Testing your Progress

What happens when you....?

* Try to make a new Thing in your console?
* Try to make a new Thing in your browser?
* 

* Run ```rspec```
* Run ```rake db:migrate```
* Run ```rake routes```
* Run ```rails s```
* View [http://localhost:3000/things](http://localhost:3000/things) while your server is running
* View and Edit some of the seeded Thing
* DELETE ALL YOUR DATA! - Run ```rake db:reset```
* Re-seed database

#Update Your README.md

* Explain what you did
* What is the relationship between has_many and belongs_to?
* What actually happens when we add associations between models?
	* What does it do behind the scenes?  
	* How does it allow us to shorten our controller methods?  Think about what your code would look like if you couldn't use model associations.
* How do Rails migrations work?  
* Do you need to name a migration anything specific?  Are ther
* What's the difference between `user:references` and `user_id:integer`
* How do you undo a migration?



