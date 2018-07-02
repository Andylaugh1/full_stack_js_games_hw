1. What is responsible for defining the routes of the games resource?
The general data routes are defined in the create_router file. However the specifc instance of the games router is in the server.js file


2. What are the the responsibilities of server.js?
Server.js is responsible for connecting the the routes from the view to the database, it makes the requests either way. The router manages the connection to the front end from the back end.



3. What are the responsibilities of the gamesRouter?
The games router is the specifc router which has been created to manage the games routes. Whereas the create_server file is just for general data, the gamesRouter is specific.



4. Which of the games API routes does the front-end application consume (make requests to)?
It makes requests to the delete(destroy API), and post request(create API)
