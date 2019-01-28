# Spotify-Discogs-API-Project
Name: Will it Spin?

Overview:
Most people, even vinyl collectors, listen to music on streaming services. It's the best way to discover new music, based on what we're already listening to. For vinyl collectors, discovering new music inevitably leads to the question: can I find this album as an actual record? Will it spin?

This app allows Spotify users to pull up a list of their 20 most recently played tracks, and see whether or not the albums are for sale online in a vinyl lp format. 

Live Demo: https://spotifydiscogsapiproject--brian-albert.repl.co/

Experience:
The user logs in with their Spotify account to retrieve their recent play history.
The user's 20 most recently-played tracks are displayed along with the artist and album information, 
and a thumbnail image of the album cover. The app then takes this data and makes a query to 
the Discogs.com database, and creates a link to that album's page in the Discogs marketplace. 

Technology:
This app is built with HTML, CSS, and JavaScript, and uses jQuery methods. 
(add more on ajax request?)

One outstanding issue is the inconsistent returns from the Discogs API. Some queries return the right
uri for that album, while others don't return anything even though that album does turn up in searches on 
the Discogs website. 
