# usePopcorn - A React Movie Application

"usePopcorn" is a dynamic and interactive web application built with React that allows users to search for movies, view detailed information, rate them, and maintain a personal watchlist. This project was developed to practice and showcase fundamental and advanced React concepts, including state management, component composition, and custom hooks.

## Features

* **Movie Search**: Seamlessly search for any movie using the OMDb API.
* **Detailed Movie Information**: View comprehensive details for each movie, including the plot, cast, director, runtime, and poster.
* **Interactive Rating System**: A 10-star rating system to give a personal rating to movies.
* **Personal Watchlist**: Add movies you have watched to a persistent watchlist.
* **Watchlist Statistics**: Get an overview of your watched movies, including the total count, average rating, and total watch time.
* **Persistent State**: Your watched list is saved in your browser's local storage, so your data is not lost on a page refresh.
* **Responsive Design**: A user-friendly and responsive layout that works on various screen sizes.

## Technologies Used

* **React**: The core of the application is built using the React library.
* **JavaScript (ES6+)**: Modern JavaScript syntax is used throughout the project.
* **CSS**: Custom styling for the application's components.
* **HTML**: The structure of the web application.
* **OMDb API**: Used to fetch movie data.

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

You will need to have Node.js and npm (or yarn) installed on your machine. You will also need to get an API key from [OMDb API](https://www.omdbapi.com/apikey.aspx).

### Installation

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/KhuramMirza/usepopcorn.git](https://github.com/KhuramMirza/usepopcorn.git)
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd usepopcorn
    ```
3.  **Install NPM packages:**
    ```sh
    npm install
    ```
4.  **Create a `.env` file** in the root of your project and add your OMDb API key like so:
    ```
    REACT_APP_OMDB_API_KEY=your_api_key_here
    ```
5.  **Start the application:**
    ```sh
    npm start
    ```
    The application will be available at `http://localhost:3000`.

## Usage

Once the application is running, you can use the search bar to look for movies. Click on any movie in the search results to see more details. From the details view, you can rate the movie and add it to your watched list. Your watched list and your ratings will be displayed on the right-hand side of the application.

## Acknowledgements

This project was inspired by and is based on the "usePopcorn" project from the "The Ultimate React Course" by Jonas Schmedtmann.