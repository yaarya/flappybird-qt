# Flappy Bird Clone - Qt C++ Project

A desktop clone of Flappy Bird, built using Qt's Graphics Framework. The project demonstrates the use of `QGraphicsScene`, `QGraphicsPixmapItem`, and animation via `QPropertyAnimation`.

## 🐦 Features

- Animated bird with dynamic wing flapping
- Infinite pillar generation with randomized gaps and heights
- Collision detection and scoring
- Game-over and restart mechanics
- Keyboard (`Space`) and mouse click controls
- Clean and modular object-oriented structure

## 🖼️ Screenshots
![image](https://github.com/user-attachments/assets/195121e1-6b0a-406c-8177-c6de47aca671)
![image](https://github.com/user-attachments/assets/0d22719f-8958-4ea1-bd15-88d8fdbbec0e)
![image](https://github.com/user-attachments/assets/03748ff9-8037-4c2d-b34c-fdfdb29f1e1f)



## 📁 Project Structure

- `main.cpp` — Application entry point
- `widget.h/.cpp` — Main UI window and scene initialization
- `scene.h/.cpp` — Game logic, score tracking, input handling
- `birditem.h/.cpp` — Player-controlled animated bird
- `pillaritem.h/.cpp` — Moving pillar obstacles
- `resources.qrc` — Contains image assets

## 🚀 Getting Started

### Prerequisites

- Qt 5 or 6
- C++17 compatible compiler
- Qt Creator

### Build & Run (Using Qt Creator)

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/flappybird-qt.git
    cd flappybird-qt
    ```

2. Open the `.pro` file in Qt Creator.

3. Build and run the project.

### Controls

- `Space` key or mouse click — Make the bird jump
- Click **Start Game** button — Begin the game

## 🛠️ To-Do

- Add sounds for flapping and collision
- Mobile port using Qt Quick

## 📜 License

This project is open source and available under the MIT License.

---

Made with ❤️ using Qt
