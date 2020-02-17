---
layout: post
title:      "Billboard 100 Decade"
date:       2020-02-17 14:32:24 -0500
permalink:  billboard_100_decade
---


## The idea
It was my hope that this project would go incredibly smooth and I would I understand everything that needed to be done outright. Unfortunately, that was not the case.

The general idea was that I would scrape the Billboard 100 chart for the 2010 - 2019 decade. using each chart element, I would initialize objects. Rank, song name, artist, peak and peak date.

I would then build out a CLI that would list a song name, after the user selected the song it would list each of that song’s attributes.

This all sounded really simple in my head, but as with most things I suffer from critical overcomplication.

The first time through building my project, I had the idea that each attribute on the chart would create an individual class.
after building out each class I ran into more problems with my environment file and class relationships. This issue really caused me to rethink how complex this idea was and what exactly I needed to accomplish what I wanted.


## Help me

After some very useful technical mentoring I was able to simply my project to something that was much more understandable.

rather than creating theses 

### classes
* artist
* song
* peak
* rank
* peak date
* CLI
* scrapper

and then creating relationships between them.
Originally my scrapper would scrape each entire chart element and try to initialize artist, song, rank, 

I instead moved to the simple idea of 

### classes
* song
* CLI
* scrapper

in this build, the scrapper class is significantly less complex and rather than try to create objects for 5 different classes,

#### it...

*creates one song object per chart element
* uses each CSS selector in the chart to assign peak, rank, song, artist and peak date as attributes for the song object
* Rather than a well built out class with a handful of methods for my song class there is only initialize with arguments and    a self. All class method so that all of the songs can be read.


## Finished Project

For this to be a CLI app I figured that displaying 100 chart items may be a bit overbearing in regard to navigation and formatting, so for simplicity sake I reduce the song list to 10 songs.
this can be changed by editing the range my limited array variable in my scrapper class though so I can play with different lengths.

#### The program welcomes the user, and will display my limited array of 10 song names
the user can either type "Done!" to quit, or the name of the song to see more information on it.

#### Each song displays its 
*rank
*name
*artist
*peak
*peak date

#### The program then displays the list again and prompt the user for an additional input
* either a song name or done!
* *will eventually expand the list and build out more information and menus for the user **

#### From the song info display menu, the user can either type
* Another song name and receive its information
* Done! to exit the program.


### conclusion

Honestly throughout this course there has been a lot of new information throw at me and at times I feel as if everything I have learned is just floating around in my head. If I ever want to use the information, I’ve learned I almost always would need a reference.

As I worked (struggled) through this project there were concepts that I struggled with earlier but as I moved forward, they became so natural for me to use it was laughable.

The biggest learning curve for this project though was absolutely Visual studio code. I took entirely too long to figure out. Now that I get it though, it again is very comedic albeit a great tool!

I feel as if a good amount of our course work has actually landed in my mind this project was a painstaking but great experience and even as I failed my way through it, I still enjoyed it 






