# Movie Library Web Application

## Installation
Follow these steps to set up and run the application on your local machine:

### 1. Clone the repository

bash

mkdir movie-library

cd movie-library

git clone https://github.com/aastha-mittal12/MOVIEAPPLICATION.git

### 2. Install Backend dependencies
cd backend

npm install

### 3. Set up environment variables

Create a .env file in the server directory and add the following environment variables:

PORT= portno.

dburl=your_mongodb_connection_string

reacturl = reacturl

### 4. Start the server
npm start

### 5. Install client dependencies

Open a new terminal window and navigate to the client directory:

cd frontend

npm install

 cd Components 
 
 mkdir services 
 
 cd services 
 
 touch helper.jsx 
 
 ### 6. Set up environment variables
In your helper.jsx

export const base_url = your backend url either localhost or  global

export const omdbapi = 'https://www.omdbapi.com/?apikey=<YOUR_API_KEY>&'

NOTE : To generate Api key :https://www.omdbapi.com/apikey.aspx
### 7. Start the client

npm run dev 

## Overview

This is a movie library web application built using the MERN stack (MongoDB, Express.js, React.js, and Node.js). The application allows users to sign up, log in, search for movies using the OMDB API, create movie lists, and manage those lists.

## Features

- User authentication (Sign In/Sign Up)
- Search movies and view details using the OMDB API
- Create, view, and manage movie lists (similar to YouTube playlists)
- Lists can be either public or private
- Responsive and user-friendly layout

## Prerequisites

Before you begin, ensure you have met the following requirements:
- Node.js and npm installed
- MongoDB installed and running
- OMDB API key


## Usage

### Register a New User

1. Navigate to the Sign Up page.
2. Enter your name, email, and password to create a new account.
3. After registration, you will be logged in and redirected to the home screen.

### Log In

1. Navigate to the Sign In page.
2. Enter your email and password to log in.
3. After logging in, you will be redirected to the home screen.

### Search for Movies

1. On the home screen, use the search bar to search for movies by title.
2. View the search results and movie details.

### Create and Manage Movie Lists

1. Create a new list by providing a list name and setting the visibility (public or private).
2. Add movies to your list from the search results.
3. View and manage your movie lists on the home screen.

## Hosting

This project is hosted on [Render & Netlify ]. You can access the live application and view the code using the links below:

- [Live Application](https://silly-brigadeiros-44e92f.netlify.app)
- [Source Code](https://github.com/aastha-mittal12/MOVIEAPPLICATION)

## Contact

If you have any questions or feedback, please contact [Your Name] at [your.email@example.com].
Feel free to customize this template according to your specific application details and requirements.
