## What is this

A cleaner and super simple way to run ghost blog on heroku. 

_"It can run on your server as well :) Setup the config as locally then deploy with `./bin/deploy-production` "_


## Running locally
1. Make sure you have **node version 10.x** installed installed.
2. Open terminal
3. Navigate to project root - (use `cd` command )
4. Run npm install
5. Copy `.env.example` and save it as `.env`
6. Edit the configurations to match your development environment
7. Run `./bin/deploy-development`
8. You should be able to have the url of your blog echoed in the terminal. Copy and paste in your browser.


## Running in Heroku

1. Open terminal - make sure `heroku cli` is installed
2. Navigate to project root 
3. Run heroku login to initialize `heroku login`
4. Create an heroku app by running `heroku create`. You will get a url for your app.
5. Open heroku dashboard `https://dashboard.heroku.com/` and navigate to the app created above,
6. Go to app settings, and click config
7. Enter the values in the `.env` file each in a separate config item.
8. Once this is done, its now time to deploy and test your blog.
9. Commit any changes you have made locally 
10. Run `git push heroku master` 
11. Voilla!! refresh your blog link in the browser
