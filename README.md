# EatDaBurger

Create custom burgers, eat burgers, and view burgers (both eaten and yet-to-be-eaten)!

## Live Link
https://

## Technologies Used
- JavaScript
- Node
- Express
- Handlebars
- MVC

## Code Explanation
- Our main file, which houses most of the dependencies that we'll be using and the initial server set-up, is server.js
- We set up and populate our database with schema.js and seeds.js
- Then, we create our connection to the database in connection.js
- We develop our ORM to run simpler methods to query database (read, write, and update)
- Our controller takes in the data response from the queries, and then routes and renders it via Handlebars, resulting in a fully functional app
- We have our GET request, which retrieves burgers; POST request, which adds burgers; and PUT request, which updates the status of burgers from not devoured to devoured
## autor
Taeyeong (T.J.) Park