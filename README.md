# README



This README would normally document whatever steps are necessary to get the

application up and running.



Things you may want to cover:

##Ruby Version

* Ruby version 2.4.5p335 (2018-10-18 revision 65137) [x64-mingw32]


* System dependencies



* Configuration



* Database creation

* Database creation



* Database initialization



* How to run the test suite



* Services (job queues, cache servers, search engines, etc.)



* Deployment instructions



* ...
##localhost
Steps to run the application on localhost 
  1. Pull the app from the GitHub repository at https://github.com/matthew-k-james/toy_app 
  2. Open the command line and navigate to the toy_app folder 
  3. run 'bundle install' 
  4. run 'bundle exec rake db:migrate'

  Once set up, to run the app on localhost: 
  5. run 'rails server' 
  6. go to 'http://localhost:3000/' and the app should be running 

##Heroku
1. Run 'bundle install --without production' 
2. Run 'heroku --version' to see if heroku is installed
3. If you get a message that the command isn't recogmised, then go to https://devcenter.heroku.com/articles/heroku-cli and select the correct installer for your computer (the Win10 machine I'm writing this on uses the Windows 64-bit installer). When downloaded, install. 
4. Shut down and re-open your command line and re-run command 2 to check it's worked correctly.
5. Use the 'heroku login' command and enter your credentials 
6. Link your cloned repo and heroku using command 'heroku git:remote -a mysterious-brushlands-79943'

Once set up in Heroku, to run the app:
7. heroku run rake db:migrate (has needed to be run each time a table is added using rails)
8. Then push your code to heroku using 'git push heroku master
9. Enter https://glacial-ravine-70104.herokuapp.com/ in your browser
