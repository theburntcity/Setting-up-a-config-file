# Setting up a config file

A config file is a place where you can store private information liek:
1. Passowrd
2. usernames
3. secert keys
4. ip addresses
5. other anything that you want to keep out of your code files  
  
First part is for a postgres database, it could be for any database server.  
The major parts of login in to the server: usermame, ip address, password, database name. There is an example [login with flask-login](https://github.com/theburntcity/flask-login) 
The second part is for flask secert key.  
The third part is for emails. This will be include smtp server address, username, password, port. 