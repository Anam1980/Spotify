# Spotify
Spotify is a digital music service that gives you access to millions of songs. Below are the details of a web application that allows users to create and manage playlists, add songs, artists, and albums to the database. It is designed to facilitate the creation and sharing of music playlists, and to track user preferences for songs, artists, and albums.

The following are the high-level requirements for the Spotify web application:

Create user: This API creates a new user with a given name and mobile number.
Create artist: This API creates a new artist with a given name.
Create album: This API creates a new album with a given title and artist name. If the artist does not exist, the API creates a new artist first.
Create song: This API creates a new song with a given title and album name. If the album does not exist, it throws an exception.
Create playlist based on length: This API creates a new playlist with a given title and adds all songs with a given length to the playlist. The creator of the playlist is the given user, who is also the only listener at the time of playlist creation.
Create playlist based on name: This API creates a new playlist with a given title and adds all songs with the given titles to the playlist. The creator of the playlist is the given user, who is also the only listener at the time of playlist creation.
Find playlist: This API finds a playlist with a given title and adds the given user as a listener to that playlist. If the user is the creator or already a listener, it does nothing.
Like song: This API allows a user to like a given song, which also auto-likes the corresponding artist. If the user has already liked the song, it does nothing.
Most popular artist: This API returns the artist with the maximum number of likes.
Most popular song: This API returns the song with the maximum number of likes.
