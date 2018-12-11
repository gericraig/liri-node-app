# Liri

About
-
Liri stands for Language Interpretation and Recognition Interface. It is a command line nope app that takes in parameters and gives back data.

Motivation
-
This is a project at the Berkeley Bootcamp where we are learning to implement node.js.

What it does
-
Spotify

node liri.js spotify-this-song '<song name here>'
 
This will show the following information about the song in your terminal/bash window:
* Artist(s)
* The song's name
* A preview link of the song from Spotify
* The album that the song is from.

If no song is provided then your program will default to "The Sign" by Ace of Base.

Bands In Town

node liri.js concert-this <artist/band name here>

This will search the Bands in Town Artist Events API  for an artist and render the following information about each event to the terminal:
* Name of the venue
* Venue location
* Date of the Event.

If no song is provided then your program will default to "The Sign" by Ace of Base.

OMDB

node liri.js movie-this '<movie name here>'
 
This will output the following information to your terminal/bash window:
* Title of the movie.
* Year the movie came out.
* IMDB Rating of the movie.
* Rotten Tomatoes Rating of the movie.
* Country where the movie was produced.
* Language of the movie.
* Plot of the movie.
* Actors in the movie.

If the user doesn't type a movie in, the program will output data for the movie 'Mr. Nobody.'

 Technologies Used
-
* Node.js
* JavaScript
* Spotify API (npm module)
* OMDb API (npm module)
* Bands in Town Artist Events API (npm module)
* Moment (npm module)
* DotEnv (npm module)
* Inquirer (npm module)

Authors
-
Geri Craig

Copyright
(C) gericraig 2018. All Rights Reserved.



