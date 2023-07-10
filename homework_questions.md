1.What is responsible for defining the routes of the games resource?
A.The create_router.js file is defining the routes.
2.What do you notice about the folder structure? Whats the client responsible for? 
A.It is divided into Client and Server. The client is responsible for the front end- the input from the user, and the display to the user.
3.Whats the server responsible for?
A.The server is responsible for the back end- sending and fetching data from the database.
4.What are the the responsibilities of server.js?
A.It connects the client, server and database together.
5.What are the responsibilities of the gamesRouter?
A.I am not entirely sure.
6.What process does the the client (front-end) use to communicate with the server?
A. Various forms of fetch (POST and DELETE) in the file GamesService.js, found in the services folder.
7.What optional second argument does the fetch method take? And what is it used for in this application? Hint: See Using Fetch on the MDN docs
A. There are many options for the second argument, one of which is the method, eg, GET or POST. This application makes use of POST and DELETE, in order to post a game, or delete a game from the database.
8.Which of the games API routes does the front-end application consume (i.e. make requests to)?
A.'http://localhost:9000/api/games/' and 'http://localhost:9000/api/games/id'. GET, POST, DELETE, PUT.
9.What are we using the MongoDB Driver for?
A.To run MongoDB in order to connect to the database.