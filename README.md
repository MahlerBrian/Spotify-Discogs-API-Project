# Spotify-Discogs-API-Project
API capstone using Spotify and Discogs APIs

Overview:
For this project, I am creating an app called "Will it Spin?". 
This app calls on third-party API's at Spotify and Discogs. 
Spotify is the well known music streaming service, and Discogs is an online 
database and marketplace for vinyl records, cd's, and cassettes. This app allows 
Spotify users to check whether the music they're listening to is for sale in a 
physical form. 

The user logs in with their Spotify account to retrieve their recent play history.
The user's 20 most recently-played tracks are displayed along with the artist and album information, 
and a thumbnail image of the album cover. The app then takes this data and makes a query to 
the Discogs.com database, and creates a link to that album's page in the Discogs marketplace. 

One outstanding issue is the inconsistent returns from the Discogs API. Some queries return the right
uri for that album, while others don't return anything even though that album does turn up in searches on 
the Discogs website. 
