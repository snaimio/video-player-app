<div align="center">

# 🎥 VideoPlayerApp
### Native iOS SwiftUI Media Player Suite & Audio Loader

[![iOS](https://img.shields.io/badge/iOS-17.0%2B-000000?style=for-the-badge&logo=apple&logoColor=white)](https://developer.apple.com/ios/)
[![Swift](https://img.shields.io/badge/Swift-5.9%2B-F05138?style=for-the-badge&logo=swift&logoColor=white)](https://swift.org/)
[![SwiftUI](https://img.shields.io/badge/UI-SwiftUI-0071E3?style=for-the-badge&logo=swift&logoColor=white)](https://developer.apple.com/xcode/swiftui/)
[![AVKit](https://img.shields.io/badge/Framework-AVKit%20%26%20AVFoundation-FF2D55?style=for-the-badge)](https://developer.apple.com/av-foundation/)
[![License](https://img.shields.io/badge/License-MIT-CEFF00?style=for-the-badge&logoColor=black)](LICENSE)

<br/>

**A native iOS media playback suite featuring custom video streaming viewports, local audio loading, custom playback controllers, and responsive SwiftUI layout architecture.**

</div>

<br/>

---

## 📌 Technical Overview
**VideoPlayerApp** is an iOS application built to demonstrate advanced media handling in SwiftUI using Apple's **AVKit** and **AVFoundation** frameworks. It provides asynchronous loading of local and remote video/audio assets, background audio playback handling, and interactive scrubber controls.

### 💼 Technical Highlights
- **AVPlayer & VideoPlayer Integration**: Embeds native high-performance video streaming with custom overlay controls.
- **AudioLoader & Playlist Engine**: Decoupled service layer (`AudioLoader.swift`, `VideoLoader.swift`) for asynchronous media file parsing and queue management.
- **Modern SwiftUI Navigation**: Structured with multi-tab media browsing (`MainView.swift`, `AudioListView.swift`) and modal player transitions.
- **Audio Session Configuration**: Configures `AVAudioSession` categories for playback persistence.

---

## 📁 Project Structure
```
MediaPlayerApp/
├── Models/
│   └── Audio.swift          # Audio entity model & metadata
├── Loaders/
│   ├── AudioLoader.swift    # Asynchronous audio asset parsing
│   └── VideoLoader.swift    # Video URL management & streaming
├── Views/
│   ├── MainView.swift       # Root media dashboard
│   ├── AudioListView.swift  # Audio playlist & queue interface
│   ├── VideoPlayerView.swift# High-definition video player viewport
│   └── AudioPlaceholderView.swift
└── MediaPlayerAppApp.swift
```

---

## 🚀 Setup & Run
1. Clone the repository:
   ```bash
   git clone https://github.com/snaimio/VideoPlayerApp.git
   cd VideoPlayerApp
   open MediaPlayerApp.xcodeproj
   ```
2. Build and run via Xcode (`⌘ + R`).

---

## 📄 License
This project is licensed under the [MIT License](LICENSE).

---

## 👨‍💻 Author
**Sheikh Naim**  
*Mobile & Full-Stack Web Developer*  
- **LinkedIn**: [linkedin.com/in/snaimio](https://www.linkedin.com/in/snaimio)  
- **GitHub**: [@snaimio](https://github.com/snaimio)  
- **Portfolio**: [snaimio.github.io](https://snaimio.github.io)
