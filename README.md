# Authentication-using-mongoDB
To use this, add your db name in config/dbconfig.js

#Adding User:
To add user use the endpoint /adduser
pass name and password in the body of the request to add user

#Authentication:
To authenticate a user use the endpoint /authenticate
pass name and password in the body as same in adduser
As a result you will be provided with a token

#Geting Info:
TO get info of a user use the endpoint /getinfo
pass Authorization as bearer <!token> to get the info of authenticated user
