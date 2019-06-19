# liri-node-app

Description 
-----------
 A simple program that uses few apis to get information on user input data. The user input must be capable with the command. For example concert-this drake.

Requirement
----

*node.js*

A run time environment that allows to use of javascript code outside the browser.

> you can download the installer  at https://nodejs.org/en/


Need a Spotifiy client key and Secret. You can find instruction in finding the info by clicking on the "node-spotify-api" hyperlink.

Instructions 
---

*git clone*

>https://github.com/JetenderG/liri-node-app.git

*running the script commands*

>node liri.js *command*

There are 4 command in this node application:
------------

1. concert-this (name of artist)

This command will find a concert where the artist will be. The date of the concert and place where it is.

api used: https://rest.bandsintown.com/artists/

 2. spotify-this-song (song)

This command will allow you to find info one the song. Specifically artist(s) names and albums. It may also allows a preview of song if available

library: node-spotify-api

3. movie-this (movie name)

The command allows to get information on the movie from ratings to actors. Just the basic information.

api:http://www.omdbapi.com

4. do-what-it-says

This command uses the same command as movie-this but just uses the command name itself

api:http://www.omdbapi.com

REMEMBER TO USE NODE FILE-NAME COMMAND NAME

Built With
-----

 - [Axios](https://www.npmjs.com/package/axios) HTTP Request Promise
 - [Dotenv](https://www.npmjs.com/package/dotenv) Uses Environment Variable
 - [node-spotify-api](https://www.npmjs.com/package/node-spotify-api) Uses Spotify Api