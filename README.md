# Welcome to My Allocine
***

## Task
I had a bit of trouble with the INNER JOIN and the last one caused a bit of trouble.

## Description
I learned from W3school. :)

## Installation
wget https://storage.googleapis.com/qwasar-public/track-claris/movies.db

## Usage
Description of tables:

actors:
id – this is a unique ID for each actor
act_fname – this is the first name of each actor
act_lname – this is the last name of each actor
act_gender – this is the gender of each actor

genres:
id – this is a unique ID for each genres
gen_title – this is the description of the genres

directors:
id – this is a unique ID for each director
dir_fname – this is the first name of the director
dir_lname – this is the last name of the director

movies:
id – this is the unique ID for each movie
mov_title – this column represents the name of the movie
mov_year – this is the year of making the movie
mov_time – duration of the movie i.e. how long it was running
mov_lang – the language in which movie was casted
mov_dt_rel – this is the release date of the movie
mov_rel_country – this is the name of the country(s) where the movie was released

movies_genres:
mov_id – this is the ID of the movie, which is referencing the mov_id column of the table movies
gen_id – this is the ID of each genres, which is referencing the gen_id column of the table genres

directors_movies:
dir_id – this is the ID for each director, which is referencing the dir_id column of the table directors
mov_id – this is the ID of the movie, which is referencing the mov_id column of the table movies

reviews:
id – this is the unique ID for each reviewer
rev_name – this is the name of the reviewer

movies_ratings_reviews:
mov_id –this is the ID of the movie, which is referencing the mov_id column of the table movies
rev_id – this is the ID of the reviewer, which is referencing the rev_id column of the table reviews
rev_stars – this is indicates how many stars a reviewer rated for a review of a movie
num_o_rating – this indicates how many ratings a movie achieved

movies_actors:
act_id – this is ID of actor, which is referencing the act_id column of actors table
mov_id – this is the ID of the movie, which is referencing the mov_id column of the table movies
role – this is the name of a character in the movie, an actor acted for that character
### The Core Team


<span><i>Made at <a href='https://qwasar.io'>Qwasar Silicon Valley</a></i></span>
<span><img alt='Qwasar Silicon Valley Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px'></span>
