talkwithme
==========

talkwithme is a very simple chatroom app built using [Tornado](tornadoweb.org) web framework with Python

I am using the official [Tornado chat script](https://github.com/facebook/tornado/tree/master/demos/chat) but I have made little modifications and added few more files so that it runs on Heroku. 

 - Create a [Heroku](https://id.heroku.com/signup) account and [set up](https://devcenter.heroku.com/articles/quickstart) on your machine
 -  Create a some directory on your desktop, give a name something you like (doesn't matter at all) and `cd` into it.  - Run : 
        `heroku login` 
 - Check out this [repo](https://github.com/avinassh/talkwithme) by running: 
        `git clone https://github.com/avinassh/talkwithme.git`
 - Now create a new Heroku app by running: `heroku create --stack cedar`
 - Now push the chatroom code to heroku by: `git push heroku master` 
 - Run this to open the chatroom in browser: `heroku open`

Thats all! :sunglasses:
