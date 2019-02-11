# Chatapp Application

# Project description & features

  - Real time application with Action Cable on Rails
  - Users can interact with each other without reloading the page or pooling databases, everything is updated as soon as it is changed
  - Persistent storage of messages inside PostgreSQL database

## What I learned with this project

 - Rails database with PostgreSQL 
 - Action Cable (Rails 5+) for real time updates
 
 ## Want to recreate this app? 
 
 With Ruby, Rails and PostgreSQL installed, create a user in your PostgreSQL database with the name of "chatapp" with privileges of CREATEDB and run the following code in your bash console (inside the application's folder):
 
```sh
rails db:migrate
rails s
```
Now go to "localhost:3000" in your browser and the application should work
 
 ## License
 
GPL v3
