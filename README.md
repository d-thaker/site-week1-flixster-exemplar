# 🍿 Flixster

**Flixter** is a movie listing website showing the latest movies currently playing in theaters. The web app is built with vanilla HTML, CSS and JavaScript and utilizes [the Movie Database API](https://developers.themoviedb.org/3/getting-started/introduction).

![Flixter Preview](https://i.imgur.com/DZtu7O8.png)

## User Stories

The following **required** functionality is completed:

- [ ] User can view a list of current movies from The Movie Database API as a grid view
  - The grid element should have an id of `movies-grid`
  - Each movie wrapper element should have a class of `movie-card`
- [ ] For each movie displayed, user can see the following details:
  - Title - the element should have a class of `movie-title`
  - Image - the `img` element should have a class of `movie-poster`
  - Votes - the element should have a class of `movie-votes`
- [ ] User can load more current movies by clicking a button at the bottom of the list
  - The button should have an id of `load-more-movies-btn`.
  - When clicked, the page should not refresh.
  - New movies should simply be added to the bottom
- [ ] Allow users to search for movies and display them in a grid view
  - There should be a search input element with an id of `search-input`
  - Users should be able to type into the input
  - When a user hits 'Enter', it should send a search request to the movies API
  - The results from the search should be displayed on the page
  - There should be a close icon with an id of `close-search-btn` that exits the search, clears results, and shows the current movies displayed previously
- [ ] Website accounts for basic HTML/CSS accessibility features
- [ ] Website should be responsive

The following **stretch** features are implemented:

- [ ] Allow user to view more details about a movie within a popup
  - The popup wrapper element should have a class of `movie-popup`
  - Display the movie overview in an element with the class name of `movie-overview`
- [ ] Improve the user experience through CSS & Animation
- [ ] Allow movie video trailers to be played using [embedded Youtube](https://support.google.com/youtube/answer/171780?hl=en)

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app functionality!
