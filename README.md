# Spotify Clone - Web Music Player

This project is a simple Spotify-inspired web music player built using HTML, CSS, and JavaScript. It demonstrates how a browser-based music player works, including features like playing songs, pausing songs, navigating between tracks, and displaying song progress.

The project focuses on frontend development and basic JavaScript functionality for handling audio playback.

---

## Features

- Play and pause songs
- Next and previous song navigation
- Song progress bar with seek functionality
- Dynamic song list display
- Song cover images
- Animated indicator showing the currently playing song
- Basic responsive design

---

## Technologies Used

- HTML5 for the structure of the web page
- CSS3 for styling and layout
- JavaScript (Vanilla JavaScript) for functionality and interaction
- Font Awesome for music control icons
- Google Fonts for typography

---

## Project Structure

```
spotify-clone/
│
├── index.html        Main HTML file
├── style.css         Styling for the music player
├── script.js         JavaScript logic for music functionality
│
├── songs/            Folder containing audio files
│   ├── 1.mp3
│   ├── 2.mp3
│   └── ...
│
├── covers/           Song cover images
│   ├── 1.jpg
│   ├── 2.jpg
│   └── ...
│
├── logo.png          Spotify logo image
├── bg.jpg            Background image
└── playing.gif       Animation for playing indicator
```

---

## How the Application Works

The application uses the HTML Audio API to play and control music files.

### Play and Pause

Clicking the play button starts the music. Clicking it again pauses the current song. The play button icon changes depending on the playback state.

### Progress Bar

The progress bar shows the current playback progress of the song. Users can move the slider to skip to different parts of the song.

### Song Selection

Users can select songs directly from the list. When a song is selected, it loads and begins playing immediately.

### Next and Previous Controls

Users can move to the next or previous track using the navigation buttons.

---

## How to Run the Project

1. Clone the repository

```
git clone https://github.com/your-username/spotify-clone.git
```

2. Open the project folder

```
cd spotify-clone
```

3. Run the project

Open the `index.html` file in any web browser.

---

## Learning Objectives

This project helps in understanding:

- DOM manipulation
- Event listeners in JavaScript
- Audio handling using JavaScript
- Building interactive web interfaces
- Frontend project structuring

---

## Possible Future Improvements

- Add volume control
- Add shuffle and repeat options
- Improve mobile responsiveness
- Add playlist management
- Connect to a backend for dynamic song loading
- Add user login functionality

---

## Author

Palak Sahu

B.Tech in Computer Science (AI and ML)

Interested in Machine Learning, Artificial Intelligence, Data Analytics, and Web Development.

GitHub: https://github.com/your-github  
LinkedIn: https://linkedin.com/in/your-linkedin
