🎵 Music Player Web App

A modern web-based music player interface built using HTML, CSS, and JavaScript.
This project provides a clean and responsive music player UI with features such as playback controls, progress tracking, volume control, and interactive animations.

📌 Features
🎧 Play / Pause music
⏮ Previous and ⏭ Next track controls
📊 Interactive progress bar
🔊 Volume control slider
❤️ Like button animation
🔁 Repeat button
🎨 Modern UI with shadow and rounded design
📱 Centered responsive layout
🖼 Album artwork display
🛠 Technologies Used
HTML5 – Structure of the music player
CSS3 – Styling and animations
JavaScript – Audio control logic
Google Fonts – Typography
Font Awesome – Icons for controls
music-player/
│
├── index.html        # Main HTML file
├── style.css         # Styling for the player UI
├── script.js         # JavaScript functionality
├── images/           # Album artwork
└── music/            # Audio files

Player Container

The main card that holds the music player.

Album Art

Displays the current song's artwork.

Song Details

Shows:

Song title
Artist name
Progress Bar
Displays the current playback progress
Allows users to seek through the track
Player Controls

Icons include:

Previous
Play / Pause
Next
Repeat
Like
Volume Control

Allows users to adjust playback volume.

✨ Animations

The like button uses a CSS keyframe animation that scales and changes color when clicked.

Example:

@keyframes like {
 0%   { transform: scale(0.5); color: red; }
 50%  { transform: scale(2.5); color: red; }
 100% { transform: scale(1); color: red; }
}
🚀 How to Run the Project
Clone the repository
git clone https://github.com/yourusername/music-player.git
Open the project folder
Run the project

Open index.html in your browser.

📷 Preview

The player includes:

Album artwork
Song information
Progress timeline
Volume slider
Playback controls
🔧 Future Improvements
Playlist support
Shuffle functionality
Mobile responsiveness improvements
Dark mode
Song queue system
📄 License

This project is open-source and available under the MIT License.
