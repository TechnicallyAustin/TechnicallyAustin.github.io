---
layout: post
title:      "Spotify Favorites"
date:       2020-07-30 17:21:02 +0000
permalink:  spotify_favorites
---

I love music and i'll listend to it everyday, i have multiple sets of headphones and a robust spotify library, i even started collecting Vinyls.

Given my adoration for music I think that every project I build while learning via flatiron will involve music. As my programming knowledge grows, I can see new areas of intrest developing for me and hopefully the apps i build are a foundation for me to explore those intrests.

When i started building this application things were very confusing, i didnt really have an idea of where i wanted to start, what direction i wanted to go, or what i wanted to ultimately accomplish. A good bit of research and support from Dominique helped me get things started and really push me to where i needed to go.

Originally my app idea was to..

1. Have users that could signup log in and log out
2. users could create a playlist and then add a song from a DB of Spotify songs
3. The playlist would be the owner of many songs 
4. Users would be the owner of many playlists
5. Users would then be able to perform AR CRUD methods on the playlists and the songs.

I liked this because i saw it as a way to tie the songs to spotify but that wasnt really what needed to be done.

I needed my model to be abe to CRUD its own resources, but having a db of pre-exisiting songs eliminated the need for that.

Instead of using a existing DB and mapping rows to objects i decided to transitin my project to this..

1.Users can signup, sign in, and sign out
2.Users can create a playlist sound -- (I think of this like the spotify "Go to Song Radio" feature for songs.)
3.The playlist has a title and a description but owns a song.
4.The song is entered via text by the user and saved to the songs table.
5. A user can have many playlists and playlists can have many songs. -- (for now the playlist is limited to 1 song)
6. A users playlist can perform CRUD methods on its self or it's songs.
7. eventually i want to add features to this app as well as some CSS and make it an look and feel really smooth

This project very much like the last one cleared a lot of the fog surrounding the way the different concepts we have learend through out this module are interconnected. Again concepts that previously felt like they were floating have started to settle, but i do think i will be revisiting this module for more a deeper understanding.
