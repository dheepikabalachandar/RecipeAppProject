# Recipe Sharing Full Stack App (MERN Stack)

## Table of Contents

- [Screenshots](#screenshots)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Folder Structure](#folder-structure)
- [Technologies Used](#technologies-used)
- [Live Demo](#live-demo)

- ## Screenshots
 
 ![Screenshot1](./public/static/images/website1.png);
 ![Screenshot2](./public/static/images/website2.png);
 ![Screenshot3](./public/static/images/website3.png);
 ![Screenshot4](./public/static/images/website4.png);

## Features

1. **User Authentication**: Secure user authentication and registration system.
2. **Recipe Management**: Create, edit, and delete your recipes.
3. **Recipe Discovery**: Browse and search for recipes shared by other users.
4. **Comments and Ratings**: Leave comments and rate recipes.
5. **Favorite Recipes**: Save your favorite recipes for easy access.
6. **Responsive Design**: Works seamlessly on both desktop and mobile devices.


## Getting Started



1. Navigate to the project directory:

       cd Mern-Recipe-App   

2. Navigate to the client directory:
     
       cd client 
       cd my-app 

3. Install client dependencies:

       npm install 

4. Return to the project root:

       cd ..
       cd ..

5. Navigate to server folder:

       cd server

6. Create a `.env` file in the project root and configure your environment variables:
   
       PORT=2000
       MONGODB_URI=mongodb://localhost/recipe-app
       SECRET=your-secret-key

Replace `your-secret-key` with a secure secret for JWT token generation.

8. Start the development server

       node index.js


## Folder Structure
The project follows a standard MERN stack folder structure:

- client: Contains the React frontend application.
- server: Contains the Express.js backend application.
- Schema: Define the MongoDB schemas and models.
- routes: Define the API routes.
- controllers: Handle route logic and interact with the database.
- middlewares: Custom middleware functions.
- db: Configuration files (e.g., database connection).

## Technologies Used
#### Frontend:

- React

#### Backend:

- Node.js
- Express.js
- MongoDB (Mongoose)
- JSON Web Tokens (JWT) for authentication
- bcrypt for secured password hashing


## Live Demo

Check out the live demo of the Recipe Sharing Full Stack App [here](https://benevolent-donut-65e579.netlify.app).
Netlify :benevolent-donut-65e579.netlify.app


