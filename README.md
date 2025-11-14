# 🎵 Web Music Player (Upload From Local)

A simple, elegant **web-based music player** built with **HTML, CSS, and JavaScript** that allows users to **upload songs from their local device** and play them directly in the browser.

---

## 🚀 Features

- 🎧 **Upload & Play Music:** Select one or multiple `.mp3` files from your device and play them instantly.  
- 🧾 **Dynamic Playlist:** Automatically lists all uploaded songs.  
- ⏯️ **Playback Controls:** Play, pause, next, and previous functionality.  
- 📊 **Progress Bar:** Displays playback progress with the ability to seek within the song.  
- 🔊 **Volume Control:** Adjustable volume using a slider.  
- 🌀 **Animated Album Art:** Rotating album image while playing.  
- 💡 **No Preloaded Songs:** The player starts empty — user uploads define the playlist.

---

## 🧩 Project Structure

```

web-music-player/
│
├── index.html      # Main HTML structure
├── style.css       # Styles and design
├── script.js       # Functionality and logic
└── README.md       # Documentation

```

---

## 🧱 How It Works

1. Click the **📂 Upload Songs** button.  
2. Choose one or multiple `.mp3` files from your device.  
3. Uploaded songs are displayed in the playlist below.  
4. Click on any song to start playback.  
5. Use the controls to play/pause, skip tracks, or adjust volume.

---

## ⚙️ Technologies Used

- **HTML5** – Structure and layout  
- **CSS3** – Styling and animations  
- **JavaScript (Vanilla)** – Dynamic functionality and event handling  
- **HTML `<audio>` API** – Audio playback and progress control  

---

## 🖥️ How to Run the Project

Because browsers block local file access via `file://`,  
you need to **run this project using a local web server**:

### Option 1 — VS Code Live Server
1. Open the project folder in **VS Code**.  
2. Right-click `index.html` → **Open with Live Server**.  
3. The project will open at `http://127.0.0.1:5500/`.

### Option 2 — Python (if installed)
1. Open a terminal in the project folder.  
2. Run:
```

python -m http.server 8000

```
3. Go to:  
```

[http://localhost:8000](http://localhost:8000)

```

---

## 🪄 Future Improvements

- 💾 Save playlist in **localStorage** so songs remain after refresh  
- 🖼️ Allow custom album art per song  
- 🔁 Add shuffle and repeat buttons  
- 🌗 Dark/Light theme toggle  

---

## 👨‍💻 Author

**Indrasena Reddy**  

---

## 📜 License

This project is open-source and free to use for learning and personal use.
