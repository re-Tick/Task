# Task
It is an api that login and register users. It uses JWT.

It listens for login post request at "/user/login" containig email and password in req.body. It returns a json object with access token.
screenshot: https://res.cloudinary.com/dizobycpj/image/upload/v1615795613/test/rwlhze5de65cv1uttwoj.png

It listens for register post request at "/user/register" containing name, email, password and phoneNo in its req.body. It also returns a json object with access token. Screenshot: https://res.cloudinary.com/dizobycpj/image/upload/v1615795512/test/zyumajpoy6w3mcwcqhtl.png
Screenshot: https://res.cloudinary.com/dizobycpj/image/upload/v1615795512/test/zyumajpoy6w3mcwcqhtl.png
 
You can also check whether you are logged in or not on going to url "user/refresh_token" which returns access token as json object.
ScreenShot: https://res.cloudinary.com/dizobycpj/image/upload/v1615795679/test/rgga5dctyrtasqog9gbz.png


