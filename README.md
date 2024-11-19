--->The folders client and server both should be run simulatenously and the MongoDB database should be connected inorder to load the project.

--->The database is managed through MongoDB Atlas which connects to the project as an MONGO_URL in the .env file

1) Navigate through the server folder and find .env file abd paste your unique MONGO_URL to get connected to your own database cloud.
2) Go inside the client directory and use 'npm run start' command to start the client (Frontend).
3) Go inside the server directory and use 'node index.js' command to start the server (Backend).

---> Your MONGO_URL can be obtained by creating your own cluster on the MongoDB Atlas platform.
