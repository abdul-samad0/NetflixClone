Netflix Clone using MERN Stack
Overview
This Netflix clone is developed using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It involves data extraction from the TMDB API and storing it in MongoDB. The frontend interacts with the backend through Express and Node.js, making API calls to retrieve movie and TV show data.

Data Extraction
The data extraction process is handled by the dataExtraction.js file in the Extraction code folder. This script pulls data from the TMDB API and stores it in MongoDB.

Frontend Features
Home Page: Displays different popular, top-rated movies, and TV shows.
Movies Filter: Shows only movies.
TV Shows Filter: Shows only TV shows.
Backend Features
Endpoints:
/api/movies: Retrieves all movie data.
/api/tvshows: Retrieves all TV shows.
/api/addMovie/userId/movieId: Adds a movie to the user's favorite list.
/api/removeMovie/userId/movieId: Removes a movie from the user's favorite list.
/api/addTvshows/userId/tvshowsId: Adds a TV show to the user's favorite list.
/api/removeTvshows/userId/tvshowsId: Removes a TV show from the user's favorite list.
User Authentication:
Signup and Login: Implemented with password hashing and JWT.
Verified Users Only: Only verified users are allowed to add and remove movies and TV shows.
Project Structure
Extraction Code Folder: Contains dataExtraction.js for TMDB API data extraction.
Frontend: Implements the Netflix UI with React.
Backend: Utilizes Express and Node.js for server-side logic.
Database: MongoDB is used to store user and movie/TV show data.
How to Run
Clone the repository.
Run the frontend and backend separately.
Ensure MongoDB is set up and connected.
Use the provided API endpoints to interact with the application.
Additional Considerations
JWT Token: Used for user authentication.
User Authorization: Only verified users can add and remove movies and TV shows.