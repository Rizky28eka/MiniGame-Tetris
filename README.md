# Tetris Flutter 🎮

![Tetris Flutter Banner](assets/banner.png)

A professional, modern, and high-performance Tetris game built with **Flutter**. This project implements classic Tetris mechanics with a premium design, smooth animations, and cross-platform support.

## 🚀 Features

-   **Modern Game Mechanics**:
    -   **SRS (Super Rotation System)**: Advanced rotation logic for wall kicks and floor kicks.
    -   **7-Bag Random Generator**: Ensures a fair distribution of tetromino pieces.
    -   **Ghost Piece**: Preview where your piece will land for better planning.
    -   **Hold System**: Swap and save pieces for strategic use.
    -   **Leveling System**: Difficulty increases as you clear more lines, inspired by the classic Game Boy frame rates.
-   **Premium Aesthetics**:
    -   Neon-styled tetrominoes and a sleek dark theme.
    -   Smooth block animations and transitions.
    -   Responsive layout that works on Mobile (Touch) and Desktop (Keyboard).
-   **Highly Performant**: Built using `ChangeNotifier` and `Provider` for efficient state management.

## 🕹️ How to Play

### Keyboard (Desktop)
| Action | Key |
| :--- | :--- |
| **Move Left / Right** | `←` / `→` |
| **Soft Drop** | `↓` |
| **Hard Drop** | `Space` |
| **Rotate Clockwise** | `D` |
| **Rotate Counter-Clockwise** | `A` |
| **Hold Piece** | `↑` |
| **Restart Game** | `Esc` |

### Touch (Mobile)
| Action | Gesture |
| :--- | :--- |
| **Move Left / Right** | Swipe Left / Right |
| **Soft Drop** | Swipe Down |
| **Hard Drop** | Quick Swipe Down |
| **Rotate Clockwise** | Tap Right Side of Screen |
| **Rotate Counter-Clockwise** | Tap Left Side of Screen |
| **Hold Piece** | Swipe Up |

## 🛠️ Built With

-   [Flutter](https://flutter.dev/) - UI Toolkit for cross-platform apps.
-   [Provider](https://pub.dev/packages/provider) - State management.
-   [Collection](https://pub.dev/packages/collection) - Dart collection utilities.

## 📦 Installation

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/rizky28eka/Tetris_flutter.git
    cd Tetris_flutter
    ```
2.  **Install dependencies**:
    ```bash
    flutter pub get
    ```
3.  **Run the application**:
    ```bash
    flutter run
    ```

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
Made with ❤️ by [Rizky Eka](https://github.com/rizky28eka)
