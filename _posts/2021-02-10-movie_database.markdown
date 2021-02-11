---
layout: post
title:      "Movie Database"
date:       2021-02-11 03:26:19 +0000
permalink:  movie_database
---

To conclude my journey at Flatiron, I was excited to try out a new concept that was quite different from my earlier projects.  I also decided to try out a new development environment.  Although the new environment worked out, the topic underwent several revisions as to more closely align with the type of projects I had previously created.  

My previous projects were created using a Mac, and I transitioned into the Windows environment to create my last project.  I ran into several errors when using the Windows environment.  Installing postgres was significantly more complicated in the Windows environment as compared to the Mac environment.  I needed to use the following code in order to install postgres:

`ridk exec pacman -S mingw-w64-x86_64-postgresql`


Initially, I was excited to build a chat application.  Upon reviewing the requirements and comparing those to the React Redux frontend needed for this application, I decided that implementing one new aspect would be challenging enough and changed my project to a movie database instead.

My movie database allowed a user to add multiple genres, with each genre containing multiple movies.  The user could also edit the genre name, delete a movie or add a movie to each type of genre.  The frontend was built with React Redux and the backend was built with Ruby on Rails.

I ran into my first challenge when creating the edit page for my genres component.  The genre page did not receive the ID of the genre due to the state not receiving the ID from the previous page.  I added a section that allowed for a smooth passing of the genre ID to the edit page state as follows:

`id: this.props.genre ? this.props.genre.id : null,`
 

The largest challenge I faced in completing this project was setting up the fetch code to fetch the genres and the movies.  At first, I attempted to fetch the movies as a nested component of the genre.  I decided that fetching them as an unnested component would actually work better and added that code instead.  

After realizing that my application was not fetching the movies due to the reducer not connecting to my container file, I realized that I needed the following code in order to connect the two files

```
genres: state.genreReducer.genres,

   movies: state.movieReducer.movies
```


After implementing this code, the container worked smoothly and my movies were finally loading into my application.  From there, I added the delete and add functionality for my movies, and my application functionedquite well.  I was satisfied with the final product.     
 

