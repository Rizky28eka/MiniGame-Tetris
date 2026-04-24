# Tetris Flutter 🎮

Tetris Flutter is a professional-grade, high-performance Tetris game built using the **Flutter** framework. This project implements modern Tetris mechanics with a premium design, smooth animations, and seamless cross-platform support for Mobile and Desktop.

The goal of this project is to showcase the power of Flutter in handling complex game logic and high-frequency UI rendering using efficient state management patterns.

⸻

## 📌 2. Overview / Background

Tetris is one of the most iconic games in history. This project was created to bring back the authentic Tetris experience while integrating modern development standards and a sleek visual style.

**Problem Statement:**
Many open-source Tetris implementations lack critical competitive mechanics such as the _Super Rotation System_ (SRS) or fair piece distribution (7-bag randomization), leading to an inconsistent gameplay experience.

**Offered Solution:**

- Implementation of **SRS** for precise piece movement and "wall kicks".
- Utilization of a **7-Bag Random Generator** to ensure a balanced distribution of tetrominoes.
- A fully responsive and adaptive UI that scales across devices.

⸻

## 📌 3. Main Features

- **Advanced Gameplay Mechanics**:
  - **SRS (Super Rotation System)**: Industry-standard rotation logic allowing for wall kicks and floor kicks.
  - **7-Bag Generator**: Guarantees that players receive every piece within a cycle of seven, ensuring fairness.
  - **Ghost Piece**: A visual preview of where the piece will land to improve precision.
  - **Hold System**: Allows players to save a piece for strategic use later in the game.
  - **Leveling System**: Difficulty scales dynamically as more lines are cleared, adjusting game speed.
- **Aesthetics & User Experience**:
  - **Premium Dark Theme**: A modern neon aesthetic designed for high contrast and readability.
  - **High Performance**: Smooth 60fps animations and transitions.
  - **Universal Input Support**: Optimized for both Keyboard (Desktop) and Touch (Mobile) gestures.

⸻

## 📌 4. Tech Stack

- **Frontend**: Flutter (Dart)
- **State Management**: Provider
- **Utilities**: Collection package for advanced data structures
- **Platforms**: Android, iOS, Web, macOS, Windows, Linux

⸻

## 📌 5. System Architecture

The application follows an **MVC (Model-View-Controller)** architectural pattern integrated with Flutter's **ChangeNotifier** for efficient state propagation.

- **Model**: Handles the game engine logic, block coordinates, collision detection, and scoring.
- **View**: Manages UI rendering, responsive layouts, and granular block animations.
- **Controller (Provider)**: Acts as the bridge between the game engine and the UI, processing user inputs and triggering state updates.

⸻

## 📌 6. Installation Guide

### Requirements

- Flutter SDK (version >= 2.18.6)
- Dart SDK
- IDE (VS Code or Android Studio)

### Step-by-Step

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/rizky28eka/Tetris_flutter.git
    cd Tetris_flutter
    ```
2.  **Install dependencies**:
    ```bash
    flutter pub get
    ```
3.  **Run the project**:
    ```bash
    flutter run
    ```

⸻

## 📌 7. Usage

### User Flow:

1.  **Start**: Launch the application; the game starts immediately on the home screen.
2.  **Gameplay**: Control the falling pieces to clear lines and increase your score.
3.  **Monitoring**: Track your current score, level, and next upcoming pieces in the side panels.

### Controls:

| Action                | Keyboard (Desktop) | Touch (Mobile)           |
| :-------------------- | :----------------- | :----------------------- |
| **Move Left / Right** | `←` / `→` Keys     | Swipe Left / Right       |
| **Soft Drop**         | `↓` Key            | Swipe Down               |
| **Hard Drop**         | `Space` Bar        | Quick Swipe Down         |
| **Rotate Clockwise**  | `D` Key            | Tap Right Side of Screen |
| **Rotate Counter-CW** | `A` Key            | Tap Left Side of Screen  |
| **Hold Piece**        | `↑` Key            | Swipe Up                 |
| **Restart Game**      | `Esc` Key          | -                        |

⸻

## 📌 8. API Documentation

_(N/A - This is a standalone offline application with no external API dependencies.)_

⸻

## 📌 9. Screenshots / Demo

_(Visual previews can be viewed by running the application locally. No external image assets are used in this documentation to maintain a clean, text-based overview.)_

⸻

## 📌 10. Folder Structure

```text
lib/
├── game/
│   ├── board.dart      # Main game board logic & state management
│   ├── level.dart      # Difficulty scaling & speed configuration
│   ├── piece.dart      # Tetromino definitions & shapes
│   ├── rotation.dart   # Super Rotation System (SRS) implementation
│   ├── tetris.dart     # Game UI entry point & layout assembly
│   ├── touch.dart      # Mobile gesture detection & handling
│   └── vector.dart     # Coordinate math & vector utilities
└── main.dart           # Application entry point
```

⸻

## 📌 11. Roadmap / Future Development

- [ ] High Score System (Local Storage & Cloud Sync).
- [ ] Immersive Sound Effects & Background Music.
- [ ] Multiple Color Themes & Custom Block Skins.
- [ ] Real-time Multiplayer Mode via WebSockets.
- [ ] Advanced Particle Effects for line clears.

⸻

## 📌 12. Contributing

Contributions are welcome! If you'd like to improve performance or add new features:

1. Fork the project.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

⸻

## 📌 13. License

Distributed under the **MIT License**. See the `LICENSE` file for more information.

⸻

## 📌 14. Author / Credits

**Rizky Eka**

- GitHub: [@rizky28eka](https://github.com/rizky28eka)

Built with ❤️ using Flutter.
