# Movie Deck Project

## Project Objective

The objective of this project is to build a web-based application that displays a list of the most popular movies of all time. The application will be developed using HTML, CSS, and JavaScript. It will provide users with functionalities like sorting movies by release date and rating, searching for movies by name, and creating a favorites list. The favorites list will be persistent, even if the browser is refreshed.

## Project Context

With the rise of OTTs, the number of movies and TV shows being released daily has increased exponentially. This has made it difficult for audiences to filter through movies and create their watchlists. This platform aims to provide users with a place to view only the most popular movies, filter them based on their preferences, and create their watchlists by adding movies to the favorites section.

## Tech Stack Prerequisites

- HTML
- CSS
- JavaScript

## Project Steps

1. **Set up the project:**
   - Create the HTML, CSS, and JavaScript files in the project directory.
   - Link the CSS and JavaScript files to the HTML file.

2. **Write the HTML and CSS of the project:**
   - Create the HTML elements required for all the components in the web page, such as the header, search bar, sorting options, tabs, lists, and footer.
   - Style all the HTML elements using CSS appropriately.

3. **Render the movies list:**
   - Fetch movie data from an API (e.g., [https://api.themoviedb.org/3/movie/top_rated](https://api.themoviedb.org/3/movie/top_rated)) and display the title, vote count, and vote average values of each movie in cards.
   - Render the poster of each movie in the card by appending the `poster_path` value from the API response to the base URL: `https://image.tmdb.org/t/p/original/`.

4. **Implement the search and sorting functionality:**
   - Filter the displayed list of movies by their title based on user input in the search box using the `filter()` function.
   - Implement options to sort the list of movies based on their release date and ratings in ascending and descending order using the `sort()` function.

5. **Implement the Favorites tab:**
   - Allow users to add and remove movies from their favorites list.
   - Create a favorites tab where all the favorite movies of the user will be listed.
   - Ensure that the search and sorting functionalities work on the favorite movies list when in the favorites tab.

6. **Implement persistent storage and API error handling:**
   - Store the data of the favorite movies in the local storage to retain the information even if the browser is refreshed.
   - Display an error message if the API takes too long to load or returns a negative status code.

## Project Checkpoints

- HTML and CSS setup and styling.
- Rendering the movies list.
- Implementing search and sorting functionality.
- Creating the Favorites tab.
- Implementing persistent storage and API error handling.

Note: Make sure to replace API endpoints, keys, and other placeholders with the appropriate values in your actual implementation.