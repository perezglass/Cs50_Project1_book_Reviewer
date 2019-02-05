# Project 1

Web Programming with Python and JavaScript



When you start my app first time you will be redirected to login page where you can sign up and log in.
login.html file extends layout.html. There are two forms in login page, one for registering a second for logging in.
One and only javascript function check if passwords match during registration process. Existing users also is checked before registration.
Succesfully registered you can try log in , in case of incorrect data message shows. Once logged in username displays next to log out button.


From goodread.com API rating count and rating itself are loaded. 
Also all reviews received from users along with ratings are loaded one under one. On the bottom there is a place where you can leave your review
and rating of max 5 points. You can send only one review. On the very bottom there is a link to API page.

application.py is a main app file. Contains routing to all html files , queries to database and all other functions.
helpers.py contains one function
 
import.py creates 3 tables-users, reviews and books. After books are created it read csv file and loads all books skipping firs line.
