# flixx-app
# TMDB Interface Documentation

## Overview
This script interfaces with The Movie Database (TMDB) API to display popular movies and TV shows, detail views, and manage searches and pagination.


<img width="1338" alt="Screenshot 2023-11-07 at 7 05 19 PM" src="https://github.com/hkeian47/flixx-app/assets/56659307/1cc7ab67-fe18-4ad3-bdf7-95fdb49ddc5e">

## Main Functions
- **Display Functions**: 
  - `displayPopularMovies()`, `displayPopularShows()`, `displayMovieDetails()`, `displayShowDetails()`
    - Fetch and render movie/show details in card format.
- **Search and Pagination**: 
  - `search()`, `displaySearchResults(results)`, `displayPagination()`
    - Handle search operations and paginate results.
- **Utility Functions**: 
  - `fetchAPIData(endpoint)`, `searchAPIData()`
    - Perform API calls to TMDB.
- **UI Helpers**: 
  - `showSpinner()`, `hideSpinner()`, `showAlert(message, className)`
    - Manage UI elements for loading and alerts.
- **Page Initialization**: 
  - `init()`
    - Initializes the appropriate UI components based on the page loaded.



