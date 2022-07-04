# WatchMate-IMDB
WatchMate is a IMDB Clone based on Spring framework(Spring MVC+ Spring boot + Spring data). 
<br/>Implemented JPA/Hibernates ORM for performing Standard crud operations with MYSQL as the backend database.
## Data Model
The Film entity holds 3 properties 
<br/>id-       int
<br/>name-     String
<br/>genre-    String
<br/>director- String
<br/>year -    int
## User Interface
The User-Interface consists of the following pages (under the designated routes):
### Index page
Route: /(GET)
<br/> List all movies.
### Create page
Route: /create (GET and POST)
<br/>GET shows a form to create a film. POST saves the form data into the database as new film.
### Delete page
Route: /delete/{id} (GET and POST)
<br/>GET shows a form to delete a certain film. POST confirms deleting a film and removes the film from the database.
### Edit page
Route: /delete/{id} (GET and POST)
<br/>GET shows a form to delete a certain film. POST confirms deleting a film and removes the film from the database.
