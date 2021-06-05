# Go-Frames

The goal of this project is to build an api to query the web gallery of art (https://www.wga.hu/)

## Goals for Project 
### The following api endpoints must be completed i.e MVP

1. GET /GetAllArtists to get a full list of artists found on wga.hu 

2. GET /Get/Artist/{artist} where artist a valid name found in /GetAllArtists, return a list of urls for that artist's work. 

## Future Plans

1. Classify artists by mood using nn
2. create an endpoint GET /Get/Artist/rand/{mood} which will return 1 art piece based on mood 
