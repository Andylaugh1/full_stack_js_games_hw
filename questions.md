1. What is responsible for defining the routes of the games resource?
The general data routes are defined in the create_router file. However the specifc instance of the games router is in the server.js file


2. What are the the responsibilities of server.js?
Server.js is responsible for connecting the the routes from the view to the database, it makes the requests either way. The router manages the connection to the front end from the back end.



3. What are the responsibilities of the gamesRouter?
The games router is the specifc router which has been created to manage the games routes. Whereas the create_server file is just for general data, the gamesRouter is specific.



4. Which of the games API routes does the front-end application consume (make requests to)?
It makes requests to the delete(destroy API), and post request(create API)

Extensions:
1. What are we using the MongoDB Driver API for?
It allows us to more easily and continuously connect our routes and server to the mongo database, allowing us to create our own API and store our own data in the Mongo db, whilst using the RESTFUL routes efficiently.

2. Why do we need to use ObjectId from the MongoDB driver API?
We use object ID as we know that every entry in our database collection will have unique ID, even if every other piece of data is similar. It means we can update, view, or delete the correct db object using our RESTFUL routes.
