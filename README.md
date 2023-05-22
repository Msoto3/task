# task

DESCRIPTION: 
  this is a task project that I have made using php,css, and mySQL from phpmyAdmin, in order to solidify my understanding of php and using databases to manipulate my code and to save data like done in the real world.


ABOUT: 
  I have a login page that ask for a username and password, if you do not have a password, then there is a signup page where you would put your username and password, from there the data will be stored in a database so that your profile is saved and now you are able to go in the page that is used for creating your to do list. You may save it, delete it and once you are done you can simply sign out and all data will still be saved for when you log back in next time
  
 
 DATABASE:
    You may attempt to recreate the page with the code all you have to do is create these tables as such, once created you can download the code and it will work, one way to get this working is by using myphpadmin through xammp.
    
    - CREATE DATABASE projects;
    
    - CREATE TABLE users(
        usersId int AUTO_INCREMENT,
        usersName varchar(250),
        usersEmail varchar(250),
        usersPWD varchar(250),
        PRIMARY KEY(usersId)
        
    );
    - CREATE TABLE todo(
       name varchar(250),
       task varchar(250)
    );
