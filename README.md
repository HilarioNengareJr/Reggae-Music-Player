
  <h2 align="center">eggae Music Player</h2>

This reggae music app is a simple website built with HTML, CSS, and JavaScript. The app allows users to play, pause, skip, and shuffle music, with additional features like volume control, repeat functionality, and a dynamic playlist.

## Features

### 1. Music Data

- All music information, including background images, posters, titles, albums, years, artists, and file paths, is stored in the `musicData` array.

### 2. Playlist

- The playlist is dynamically generated based on the `musicData`. Each item includes a button with a poster image and an equalizer icon.

### 3. Playlist Modal Sidebar

- Clicking the playlist button in the top app bar toggles the playlist modal sidebar, and clicking on the overlay or any playlist item hides the modal.

### 4. Playlist Item

- Clicking a playlist item removes the active state from the previously played music and adds the active state to the clicked music.

### 5. Player

- The player section dynamically displays information about the currently playing music, such as the poster, title, album, year, and artist.
- The audio source is created for the current music, and various elements are updated based on the selected music.

### 6. Duration and Seek

- The duration of the music is displayed, and the seek range allows users to navigate within the track.

### 7. Play Music

- Clicking the play button toggles between playing and pausing the music.

### 8. Running Time

- The running time is continuously updated while the music is playing.

### 9. Range Fill Width

- The width of the range fill is updated as the user adjusts the range input.

### 10. Seek Music

- Changing the player seek range seeks the music to the corresponding position.

### 11. End Music

- The app checks if the music has ended, resets the player if it has, and removes the active state from the play button.

### 12. Skip to Next/Previous Music

- Buttons allow users to skip to the next or previous track, updating both the player information and playlist item.

### 13. Shuffle Music

- Clicking the shuffle button toggles the shuffle state, and the next track is selected randomly if shuffling is enabled.

### 14. Repeat Music

- Clicking the repeat button toggles the loop functionality.

### 15. Music Volume

- Users can adjust the volume using the volume range input, and the volume icon changes based on the volume level.

### 16. Mute Music

- Clicking the volume button mutes or unmutes the audio source.

