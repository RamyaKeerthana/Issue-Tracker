# Issue-Tracker
An issue tracker developed using Ruby on Rails
# Title - Issue Tracker

## Commands Used
We have used scaffolding devise to create add project , comments and user


  - rails generate scaffold Comment link_id:integer:index body:text
  - rake db:migrate
  - rails generate scaffold Link title:string url:string
  - rails generate devise:install
  - rails generate devise:views
  - rails generate devise User
  - rake db:migrate
 ### Home Page displays 
link to Home Signup Login

#### Home
It displays all the projects created by users

#### Sign up
It enables Users to Create an Account

#### Login
It enables the users to login who already created the account
#### Characteristics

Clicking on the project name shows the title and link to  the project 

Everyone can upvote downvote on a project

Only the owner of the project  can edit or destroy their project

Any logged in user can comment on a project 

Only the owner of a comment can edit and destroy it 
