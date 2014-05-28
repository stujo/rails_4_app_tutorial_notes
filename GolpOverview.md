
Golp! Search, Find and Share Your Favorite Things!

---

#Rails Track - Overview

Welcome to your new job at Golp! we are a startup and you are on the team

This week we are going to build an application together!

* Each day we will share our User Stories with you

* Each User Store will describe one feature

* Your job will be to implement the feature assigned to you

* We will share a master repository and you will fork it, just like the open source

    * Many of you will work on the same feature each day

    * You will each work in your own repo

    * You must submit a working solution to the feature assigned to you

    * Each day we'll pick one implementation of each feature and integrate it into master

    * We will then sync up the repositories with the master and begin the process again

* Some features will be core MVP features which all team members must complete

* Some additional features will be available to team members who have completed the day's MVP

You will independently with limited instructor support, you are expected to research and find your own solutions to
the feature challenges. This is the time to build your confidence that you can solve problems without assistance


#Pre-Work

Before we can use this workflow we'll need to set up the git repositories

* This is our master repository:
  * [https://github.com/wdi-sf-march-2014/golp](https://github.com/wdi-sf-march-2014/golp)
* Fork this repository to your GitHub account
* Clone your fork locally


#Daily Feature Workflow

* Instructors Present User Story to the team:

    * User Story
      * Has Name
      * Has Persona
      * Has Description
      * Has Feature Test(s)

* Instructors then present overview of relevant material and  provide you with some pointers and documentation
references

* ~15 Minutes: Group discussion to ensure shared understanding of feature

* 5 Minutes: break

* ~15 Minutes : SOLO investigation (no coding)

* ~15 Minutes : Pair Discussion (no coding)

* ~15 Minutes Group discussion of possible solution directions, clarification of approach

* SOLO work on the feature (see below)

* At the end of the allotted time Every Student will explain their code to one other student

* Then switch roles with partner

* Then Instructors will pick one student explain their partner's code


#SOLO work
On this project you are working independently and on this project you are NEVER working on master repo directly

Before you start working on a feature:

* Ensure you are on master branch
* Ensure git status is clear
* Create a new feature branch from the updated master branch
    ```(master)$ git checkout -b feature_name```
* Make your changes on this branch

Once you've completed your feature work:

* Commit and push your branch to your github repo:
    ```(feature_name)$ git push origin feature_name```

* On github create a Pull Request from your feature_name branch to the master repo's feature_name branch
* Review your pull request with another student to get feedback
* Make any changes you both feel are necessary and make sure all tests are passing

Once you feel your feature is ready for prime time:

* Work with an instructor on a review of your pull request



#Resources


##Geocoding
* https://github.com/alexreisner/geocoder


##Simple Form with Bootstrap
* https://github.com/rafaelfranca/simple_form-bootstrap

##Devise
* https://github.com/plataformatec/devise/wiki/How-To:-Add-:confirmable-to-Users
* https://github.com/intridea/omniauth-github
* http://sourcey.com/rails-4-omniauth-using-devise-with-twitter-facebook-and-linkedin/
* http://www.jacopretorius.net/2014/03/adding-custom-fields-to-your-devise-user-model-in-rails-4.html

##Background Emails
* https://github.com/plataformatec/devise/wiki/How-To%3A-Send-devise-emails-in-background-%28Resque%2C-Sidekiq-and-Delayed%3A%3AJob%29
* http://blog.remarkablelabs.com/2013/01/using-sidekiq-to-send-emails-asynchronously

##Adding a Gravatar
* http://railscasts.com/episodes/244-gravatar?view=asciicast

##Sass / Bootstrap
* http://alademann.github.io/sass-bootstrap/css/

##Sidekiq
* http://cowjumpedoverthecommodore64.blogspot.com/2013/07/scaling-heavy-web-requests-with-sidekiq.html?m=1
* https://github.com/mperham/sidekiq/wiki/Monitoring

##Full Text Search
* http://texticle.github.io/texticle/
* https://coderwall.com/p/vngr0a
* http://dev.mikamai.com/post/77171462056/easy-full-text-search-with-postgresql-and-rails
* https://github.com/Casecommons/pg_search/blob/master/README.md

##Paperclip
* https://github.com/thoughtbot/paperclip/blob/master/README.md
* https://devcenter.heroku.com/articles/paperclip-s3

##Job Scheduling
* https://github.com/jmettraux/rufus-scheduler
* https://devcenter.heroku.com/articles/scheduler
* https://github.com/jrgifford/delayed_paperclip
* https://github.com/Moove-it/sidekiq-scheduler

##Event Handlers and Turbolinks
* http://srbiv.github.io/2013/04/06/rails-4-my-first-run-in-with-turbolinks.html


