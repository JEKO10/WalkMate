<h1 align="center">
  WalkMate<br>
  (Full-stack app)
</h1>
<br>


## Table of contents
- [Project task](#project-task)
- [Project overview](#project-overview)
- [Built with](#built-with)
- [Live preview](#live-preview)


## Project task
This is a full stack application built with HTML/CSS/JS on the front end and Flask on the back end. A user can register by providing an email address and a password. 
After logging in, the dashboard will show all users, and you can search for users by location to find people nearby who want to walk with you.

## Project overview
The Home page contains information about WalkMate, why should you use it, and satisfied customers. You have to register or log in to access the Dashboard page. Register and login pages are powered by the wtforms Flask package. Passwords are hashed and secured by the werkzeug package. The Dashboard page contains the best Walk-mates at the top of the page. Those are Mates who walked the most kilometers together. All of our service users are listed below. The navbar contains a Logout button and input for filtering users by location. Filtering is used to find Mates nearby who want to walk with you. The filtered users' table is shown below the all users table. There is one more page as well. The page How to Contact Mates contains information on how to contact Mates, preferably, in your area. You can contact users via email or Facebook because they must provide email and Facebook when registering. For adding users, I used SQLAlchemy to communicate with the Sqlite3 database.

## Built with
- HTML
- CSS (Sass)
- JavaScript
- Python (Flask)
- Sqlite3 database
- Railway cloud
 
## Live preview
[Click for live preview](https://walkmate.up.railway.app/)
