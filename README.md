# FBMessengerBot
This is sample bot server to link with FB messenger Webhook. Messenger will simply echo the messege it recieved back to the user.

# Setup

1. Install nodeJs
2. Clone the repo and run npm init. This will get all the required packages for the app to run.
3. Use any applications to host this on Internet. I used Heroku to host the application, use the page https://devcenter.heroku.com/articles/getting-started-with-nodejs#introduction to setup.
4. Follow the steps in page https://developers.facebook.com/docs/messenger-platform/guides/quick-start to setup your test app.
	You will provide Verify Token in Step 2 for the page. Store it and use in line 18 of main.js
	You will create a Page Access token in Step 3 for the page you have create. Use it in Line 56 of main.js
5. Once both the steps are done, login to the account from which you devloped the app and test by sending an sample message to the page you have created.
