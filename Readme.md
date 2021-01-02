# Login-logout project

I have used **Node.js + express + MongoDB** to create an successfull login-logout application.


## Start by installing below packages:
- npm i express bcryptjs passport passport-local ejs express-ejs-layouts mongoose connect-flash express-session 
- npm i -D nodemon

## Used https://www.mongodb.com/cloud/atlas for database.


## Download and run below commands to see the working application

- $ npm install
- In config/keys.js update the value of MongoURI as per your account in mongodb. 
**Note:** Do not forget to add the passport and dbname.
**Warning:** If you are receiving an bad authentication error, chnage your password to the simple string, special characters in password can create an complications in this case.
- $ npm start 
- Visit http://localhost:5000

## Customize
- **To change the Icons:** Use https://fontawesome.com/
- **To change the Theme:** Use https://bootswatch.com/
