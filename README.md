# :octocat: PLACEHOLDER APP NAME :octocat:

## App :
#### A visual representation of Spotify's library that users can navigate through.  
#### By visually representing this data, users will more easily be able to identify artist/song affiliations.  

## MVP :
#### User features:
* Create an account **OR** Access an existing account
* Login / Logout
* **Navigate** through the visual Library of music
* **Search** Library via input 
* Save songs / albums / playlists
* Typical Spotify interactions/functionality (like, pause, play, next song, etc)

#### App features:
* Breadcrumb navigation bar *(Genres -> Artists -> Albums -> Songs)*
* At each level of scope, only applicable data will be supplied
    - Genre: A visual display of music genres : 
    >Selecting a specific genre will then populate the screen with artists in that genre
    - Artists: A visual display of music artists from the selected genre (previous layer being genre)
    >Selecting a specific artis will then populate the screen with albums or songs from that artist
    - Albums: Albums specific to the user selected artist, with songs to sample
    - Songs: Songs specific to the user selected artist/album
* Intuitive button navigation to dive deeper into the library or back up to a layer


## Future Features: 
   - Library data will be mapped visually (D3)
        * More popular artists/genre/songs will be represented with larger text, warmer colors or proximity to focal points 
