Twitter analog app
==================
> Working app can be found [here](https://twitter-analog-app.herokuapp.com/) on heroku

Simple prototype of twitter like site with microposts.

You can check possibilities of app by sign in with `example@mail.com` login and `foobar` password. It's demo user with admin privilegies.

After deploy it's possible to create test users with microposts and following relationships
    
    rake db:populate

Views are coded on HAML and SASS. Have tests on Rspec and Cucumber. 