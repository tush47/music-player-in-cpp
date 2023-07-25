# music-player-in-cpp

![image](https://github.com/tush47/music-player-in-cpp/assets/110597823/1bc741aa-7b0c-4016-8aa0-2b899660d997)










this is a code for music player system coded in c++
The given code is a program for managing a playlist of songs. It allows users to perform various operations such as adding songs, deleting songs, searching for songs, playing songs, displaying the playlist, etc. The playlist is implemented using a doubly linked list.

Here's a breakdown of the code:

The code includes necessary header files and defines a structure for the playlist node.

The tofile function is used to write a song name to a file called "playlist.txt".

The add_node function is used to add a new song to the playlist. It prompts the user to enter the song name, stores it in a new node, and adds it to the end of the playlist.

The add_node_file function is similar to add_node but is used to add songs from a file to the playlist.

The delete_file function is used to delete a song from the "playlist.txt" file. It creates a temporary file, copies all songs except the one to be deleted to the temporary file, and then replaces the original file with the temporary file.

The del_node function is used to delete the last node from the playlist.

The printlist function is used to display all the songs in the playlist.

The count_nodes function counts the total number of songs in the playlist.

The del_pos function deletes a node at a specified position in the playlist.

The search1 function is used to search for a song in the playlist based on the user's input.

The create function initializes the playlist by setting the top pointer to NULL.

The push function adds a recently played song to a separate linked list.

The display function displays the recently played songs.

The play function allows the user to choose a song to play from the playlist. It adds the played song to the recently played list.

The recent function displays the recently played songs.

The topelement function displays the last played song.

The sort function sorts the playlist in ascending order based on the song names.

The addplaylist function adds songs from the "playlist.txt" file to the playlist.

The del_search function is a menu-based function that allows the user to delete a song from the playlist either by searching for it or specifying the position.

The main function is the program's entry point. It presents a menu to the user and performs the corresponding operations based on their choice.

Please note that there are a few improvements that can be made to the code, such as using std::string instead of character arrays, handling user input more robustly, and improving error handling.
