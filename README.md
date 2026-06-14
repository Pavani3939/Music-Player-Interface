# 🎵 Music Player Interface

A fully functional, desktop-native music player application built with Java. This application leverages Java Swing for a clean, responsive graphical user interface and the Java Sound API for high-fidelity WAV audio playback and playlist management.


## 🌟 Key Features

* **Advanced Playback Controls:** Seamlessly play, pause, stop, and resume audio tracks with millisecond precision.
* **Playlist Management:** Navigate through multiple tracks using the built-in Next and Previous navigation controls.
* **Smart Track Switching:** Automatically detects the end of an audio file and smoothly transitions to the next track in the playlist.
* **Intuitive GUI Design:** A clean, user-friendly graphical interface engineered with Java Swing components for native OS integration.
* **Robust File Handling:** Securely reads and buffers WAV audio streams directly from the local file system.

---

## 🛠️ Modern Tech Stack & Tooling

* **Core Language:** Pure **Java (JDK 8+)**, demonstrating strong object-oriented programming (OOP) principles.
* **Graphical Interface:** **Java Swing** and **AWT** utilized for event-driven UI components and window management.
* **Audio Engine:** **Java Sound API** (`javax.sound.sampled`) implemented for low-level audio stream processing and playback control.
* **Architecture:** Event-driven architecture utilizing Java ActionListeners to bridge UI interactions with backend audio logic.

---

## 📂 Project Structure

```text
Music-Player-Interface/
├── src/
│   ├── Main.java              # Application entry point and initialization
│   ├── MusicPlayerGUI.java    # Swing UI layout and event listeners
│   └── AudioHandler.java      # Java Sound API playback and stream logic
├── assets/                    # Directory for storing .wav audio files
└── README.md                  # Project overview and system documentation
```

---

## 🚀 Setup & Launch Instructions

To compile and run this application locally on your machine:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Pavani3939/Music-Player-Interface.git
   ```
2. **Add Audio Files**
   - Ensure you have valid `.wav` audio files. Place them inside the `assets/` directory (or update the file paths in the source code).
3. **Compile and Run**
   - Navigate to the `src` directory in your terminal:
   ```bash
   javac *.java
   java Main
   ```
