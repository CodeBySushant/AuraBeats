# 🎵 My Music App - Flutter Starter Project

A minimal, clean, and beginner-friendly music player app built using **Flutter**. This app supports local audio playback with a sleek UI, making it a perfect starting point for building your own Spotify-like application.

---

## 🚀 Features

- 🎧 Play local MP3 files using `just_audio`
- 🖼️ Custom song image and metadata (title, artist)
- 📱 Clean Home Screen with song list
- 📀 Music Player screen with play/pause controls
- 💡 Dark Theme UI (ThemeData.dark())

---

## 📁 Project Structure

my_music_app/
│
├── lib/
│   ├── main.dart                # App entry point
│   ├── data/
│   │   └── song_data.dart       # Song metadata list
│   └── screens/
│       ├── home_screen.dart     # Song list UI
│       └── player_screen.dart   # Music player UI
│
├── assets/
│   ├── songs/
│   │   └── song1.mp3            # Local audio file
│   └── images/
│       └── song1.jpg            # Cover image for the song
│
├── pubspec.yaml                 # Dependencies and asset declarations
└── README.txt                   # You're here!

---

## 📦 Dependencies

dependencies:
  flutter:
    sdk: flutter
  just_audio: ^0.9.33
  provider: ^6.0.5
  cached_network_image: ^3.2.3
  flutter_svg: ^2.0.7

> Run `flutter pub get` after modifying `pubspec.yaml`.

---

## 🧪 How to Run

1. **Clone or Download this repo**
2. Open the project in **Android Studio** or **VS Code**
3. Run `flutter pub get`
4. Connect your emulator/device
5. Run the app:
   flutter run

---

## 🎯 What's Next?

This is only the beginning. Next steps could include:

- 🎙️ Microphone listening for mantra count
- 🔥 Firebase Authentication
- ☁️ Cloud Firestore for user playlists
- 🌐 Online music streaming (YouTube or custom API)
- 💚 Like/Favorite songs
- 🎨 Theme switching and animations

---

## 🧑‍💻 Author

**Sushant**  
Built with ❤️ using Flutter  
[Connect on LinkedIn](https://www.linkedin.com/sushantsharma14) 

---

## 📄 License

This project is open-source and available under the MIT License.
