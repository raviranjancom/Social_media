Pages : 
  Login Page
  Signup Page
  Create Profile Page
  Edit Profile Page
  Create Post Page
  Delete Post Page
  Update post page
  Password Reset Page
  Feed/Home page
  User Profile Page
  Search Results Page
  Post Comment Page

Features :
  Follow/Unfollow Users
  Like/Unlike the posts
  Download the post images
  Comment on user posts
  User suggestion section
  Search users through the search bar

  
Tools and Techs :
  Backend Framework: Django
  Front-end : Bootstrap, SCSS, HTML,CSS, Javascript
  Database: Sqlite3


Installation : 
  Fork this repo
  Clone the repo to your local system
  git clone https://github.com/raviranjancom/Mr_Robot.git
  cd Mr_Robot
  Make sure you have python installed on your system.
  
  Create a Virtual Environment for the Project
  
  If u don't have a virtualenv installed
  
  pip install virtualenv
  For Windows Users
  
  virtualenv env
  env/Scripts/activate
  For Linux Users
  
  virtualenv env
  source env/Scripts/activate
  If you are giving a different name than env, mention it in .gitignore first
  
  Install all the requirements
  
  pip install -r requirements.txt
  cd social
  Make migrations/ Create db.sqlite3
  
  python manage.py makemigrations
  python manage.py migrate
  Create a super user. This is to access Admin panel and admin specific pages.
  
  python manage.py createsuperuser
  Enter your username, email and password.
  
  Run server
  
  python manage.py runserver
  
