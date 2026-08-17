# 🎵 Aura — Music Player

A modern, elegant, and responsive **web-based music player** built with **HTML, CSS, and JavaScript**.

Aura provides a beautiful dark-themed interface with smooth animations, music playback controls, search functionality, shuffle, repeat modes, volume control, and a dynamic ambient background.

## ✨ Features

* 🎧 Play and pause music
* ⏮️ Previous and next track controls
* 🔀 Shuffle mode
* 🔁 Repeat modes

  * Repeat Off
  * Repeat All
  * Repeat One
* 🔍 Search songs by title or artist
* 🎚️ Interactive progress/seek bar
* 🔊 Volume control
* ⌨️ Keyboard support

  * Press `Space` to Play/Pause
* 🎨 Dynamic colorful gradient album artwork
* 🌌 Animated ambient background
* 🌓 Modern dark glassmorphism UI
* 📱 Responsive design
* ♿ Keyboard focus and reduced-motion support
* 💻 Works directly in the browser
* 🚀 No installation or build process required

## 🛠️ Technologies Used

* **HTML5**
* **CSS3**
* **JavaScript**
* **HTML5 Audio API**
* **Google Fonts**

  * Fraunces
  * Manrope

## 📂 Project Structure

```text
Aura-Music-Player/
│
├── index.html
├── README.md
│
└── music/
    ├── song1.mp3
    ├── song2.mp3
    ├── song3.mp3
    └── ...
```

## 🚀 How to Run the Project

### 1. Download or Clone the Repository

```bash
git clone https://github.com/your-username/Aura-Music-Player.git
```

### 2. Open the Project Folder

Make sure the following structure is maintained:

```text
index.html
music/
```

### 3. Run the Application

Simply open:

```text
index.html
```

with any modern web browser.

You can double-click the file or right-click and select:

```text
Open with → Google Chrome
```

No Python, Node.js, npm, or additional installation is required.

## 🎮 Music Controls

| Control      | Function                                                 |
| ------------ | -------------------------------------------------------- |
| ▶️ Play      | Starts the selected song                                 |
| ⏸️ Pause     | Pauses the current song                                  |
| ⏮️ Previous  | Goes to the previous track or restarts the current track |
| ⏭️ Next      | Plays the next track                                     |
| 🔀 Shuffle   | Plays songs in a randomized order                        |
| 🔁 Repeat    | Cycles through repeat modes                              |
| 🎚️ Seek Bar | Jump to any position in the song                         |
| 🔊 Volume    | Adjust music volume                                      |
| 🔍 Search    | Search songs by title or artist                          |
| `Space`      | Play or pause music                                      |

## ➕ Adding More Songs

To add your own music:

### Step 1

Add your `.mp3` file inside the `music` folder.

```text
music/
└── MySong.mp3
```

### Step 2

Open `index.html`.

Find the `TRACKS` array inside the JavaScript section and add your song information.

Example:

```javascript
{
    title: "My Song",
    artist: "Artist Name",
    file: "music/MySong.mp3"
}
```

Save the file and refresh your browser.

## 🎨 Design

Aura uses a modern visual style inspired by premium music streaming applications.

The interface includes:

* Dark background
* Glassmorphism panels
* Ambient gradient effects
* Smooth transitions
* Dynamic track colors
* Modern typography
* Responsive layout

Each song receives a unique colorful gradient that is used to create the visual atmosphere of the player.

## 🌐 Offline Support

The music player works locally in your browser.

Internet access is only useful for loading the Google Fonts. If you are offline, the application will automatically fall back to system fonts.

## 📸 Screenshots

You can add screenshots of your project here.

```markdown
![Aura Music Player Screenshot](screenshots/home.png)
```

## 🔮 Future Improvements

Possible future features include:

* ❤️ Favorite songs
* 📁 Playlist creation
* 🎼 Queue management
* 🖼️ Custom album artwork
* 🌙 Light and dark themes
* ⌨️ Additional keyboard shortcuts
* 📱 Improved mobile controls
* 💾 Save playlists using Local Storage
* 🎵 Drag-and-drop music support

## 👨‍💻 Author

**Rudra Narayan Bishoyi**

* GitHub: Add your GitHub profile link here

## 📄 License

This project is created for educational and personal use.

---

⭐ If you like this project, consider giving it a star on GitHub!
