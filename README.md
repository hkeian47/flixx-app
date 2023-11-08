# flixx-app
# TMDB Interface Documentation

## Overview
This script interfaces with The Movie Database (TMDB) API to display popular movies and TV shows, detail views, and manage searches and pagination.

## Configuration
- **Global Object**: Stores current page, search parameters, and API configuration. 
  - Replace `apiKey` with a valid TMDB key.

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



