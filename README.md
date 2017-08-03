##Movie Watch-list

We're going to create a project to:
* search an API of movies
* see a list of the found movies
* save a movie to a "to-watch" list (stored in a DB)
* see the list of "to-watch" movies 
* delete a movie from the "to-watch" list 
* clear the search results

The finished project will look something like this:

![movielist](/images/moviesToWatch.png)

##Technologies

* Back-end - Spring Boot
* Front-end - React
* Database - MySql
* Data API - [OMDB API](http://www.omdbapi.com/)
    * OMDB requires an API Key - Slack Nathan for one!

##User Stories
* As a user, I can search for a movie by entering a name in the search field
* As a user, I can see the results from OMDB in a list of movies on the page
* As a user, I can click an "add" button next to a movie in the list to save the movie 
* As a user, when I save a movie, I should see it in a list called "my movies"
* As a user, I can click a delete button in the "my movies" list to remove a movie from the list
* As a user, I can clear the list of search results by clicking a "clear" button

Start by making a new project from scratch. Front-end and back-end should live in different repositories on Github. Write this using full TDD so start with acceptance tests, then integration tests, and finally unit tests. 
