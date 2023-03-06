# Music_Player_App

This is a simple java project using java core and OOPs concepts, in which a user can create an album and add songs to the album. The user can also create a playlist and add songs to the playlist from the album. Finally, the user can play the songs in the playlist.

The project contains two classes:

Album: A class representing an album, containing the album's name, artist, and a list of songs in the album.

Song: A class representing a song, containing the song's title and duration.

## Class Album
### Fields
name : String - representing the name of the album

artist : String - representing the name of the artist

songs : ArrayList<Song> - representing the list of songs in the album

### Methods
*Album(String name, String artist) - A constructor method to create an Album object.

*findSong(String title): A method to find a song in the album based on the title.

*addSong(String title, double duration): A method to add a song to the album.

*addToPlayList(int trackNumber, LinkedList<Song> PlayList): A method to add a song to the playlist based on the track number.

*addToPlayList(String title, LinkedList<Song> PlayList): A method to add a song to the playlist based on the title.

## Class Main
This class contains the main method to run the Music Player App.

### Fields

albums: ArrayList<Album> - representing the list of albums in the music player.

### Methods

*main(String[] args): The main method to run the Music Player App.

*play(LinkedList<Song> playList): A method to play the songs in the playlist.

*printMenu(): A method to print the available options for the user.

*printList(LinkedList<Song> playList): A method to print the list of songs in the playlist.

## Usage

To use the Music Player App, run the Main class. The app will create two albums, Album1 and Album2, and add songs to them. Then, the app will create a playlist and add songs to it from the albums. Finally, the app will play the songs in the playlist.

Available options to the user are:

0 - to quit

1 - to play the next song

2 - to play the previous song

3 - to repeat the current song

4 - to print the playlist

5 - to print the available options

6 - to remove the current song from the playlist

Enjoy the Music Player App!
