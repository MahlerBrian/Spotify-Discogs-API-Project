# Spotify-Discogs-API-Project
Name: Will it Spin?

Overview:
Most people, even vinyl collectors, listen to music on streaming services. It's the best way to discover new music, based on what we're already listening to. For vinyl collectors, discovering new music inevitably leads to the question: can I find this album as an actual record? Will it spin?

This app allows Spotify users to pull up a list of their 20 most recently played tracks, and see whether or not the albums are for sale online in a vinyl lp format. 

Live Demo: https://spotifydiscogsapiproject--brian-albert.repl.co/

Experience:
The userflow is very simple, with only two screens. On the homescreen, the user logs in with their Spotify account to retrieve their recent play history. 
![alt text](https://github.com/MahlerBrian/Spotify-Discogs-API-Project/blob/master/willItSpinScreen1.PNG)

If you don't have a Spotify account and don't want to register, you can sign in using this demo account:

Username: i1593j6y9so01985pb51hfu6n

Password: knockknockknock


Clicking the 'login' button will direct the user to Spotify's account login page. After logging in, the user is redirected back to 'Will it Spin?' with the user's 20 most recently-played tracks displayed along with the artist and album information and a thumbnail image of the album cover. The app then uses the Spotify data for each track, and makes a query to the Discogs.com database. If the album is found in Discogs's database, it creates a link to that album's page in the Discogs marketplace, which is rendered in the DOM alongside the track, artist, and album data from the Spotify API.  
![alt text](https://github.com/MahlerBrian/Spotify-Discogs-API-Project/blob/master/willItSpinScreen2.PNG)

NOTE: Songs will not instantaneously appear on your list as you play them in Spotify. It may take a minute or two for the Spotify API to update!

Technology:
This app is built with HTML, CSS, and JavaScript, and uses jQuery methods. 
