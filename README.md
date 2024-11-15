# 🐍 Snake Game

A modern, dynamic **Snake Game** built for Android using **Kotlin**. This game provides an interactive and exciting experience with intuitive controls, customizable features, and progressive difficulty levels.

---

## 🌟 Features

- **Dynamic Gameplay**: The snake moves and grows as it consumes food. Difficulty increases as the game progresses.
- **Custom Controls**: Navigate the snake using on-screen buttons for UP, DOWN, LEFT, and RIGHT movements.
- **Collision Detection**: Game ends when the snake hits the boundary or itself.
- **Progressive Difficulty**: The snake's speed increases as more food is consumed.
- **Score Display**: Shows the player's current score and the final score when the game ends.
- **Pause and Resume**: Pause the game and resume seamlessly without losing progress.
- **Restart Game**: Quickly restart the game after a game over.

---

## 🛠️ Technologies Used

- **Kotlin**: The primary programming language for the game logic.
- **Android SDK**: For UI and application functionality.
- **RelativeLayout and LinearLayout**: For a clean and organized UI design.
- **ImageView**: To display the snake and food dynamically.
- **Handler**: For managing the game's main loop and updating the UI.

---

## 📱 Screenshots

### Main Game Interface
![Main Game Interface](https://via.placeholder.com/400x300?text=Main+Game+Interface)

### Game Over Screen
![Game Over Screen](https://via.placeholder.com/400x300?text=Game+Over+Screen)

---

## 🎮 Gameplay

### Movement Controls
- **UP, DOWN, LEFT, RIGHT** buttons to control the direction of the snake.
- The snake moves continuously in the current direction until a new direction is chosen.

### Eating Food
- The snake consumes food when its head touches the food item.
- A new segment is added to the snake, and the food spawns at a random location.

### Collision and Game Over
- The game ends if the snake collides with:
  - The boundary of the board.
  - Its own body.

### Score Display
- The current score is displayed in real-time.
- Upon game over, the final score is shown.

### Pause and Resume
- **Pause Button**: Freezes the game and hides the board.
- **Resume Button**: Restores the board and continues gameplay.

---

## ⚙️ How to Run

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/snake-game.git
   cd snake-game
   ```

2. **Open in Android Studio**:
   - Launch Android Studio.
   - Open the cloned project directory.

3. **Build the Project**:
   - Sync Gradle and build the project.

4. **Run the App**:
   - Connect an Android device or start an emulator.
   - Run the app using the "Run" button in Android Studio.

---

## 🗂️ Project Structure

- **`src/main/java/com/example/snakegame`**: Contains the Kotlin source code for the game logic.
- **`res/layout`**: XML layout files for the game's user interface.
- **`res/drawable`**: Images and visual assets (e.g., snake, food).
- **`res/values`**: Resources for colors, strings, and dimensions.
- **`AndroidManifest.xml`**: Configurations for the Android app.

---

## 🤝 Contribution

Contributions are welcome! Here's how you can contribute:

1. **Fork the Repository**.
2. **Create a New Branch**:
   ```bash
   git checkout -b feature-name
   ```
3. **Make Changes** and Commit:
   ```bash
   git commit -m "Added new feature"
   ```
4. **Push to Your Branch**:
   ```bash
   git push origin feature-name
   ```
5. **Submit a Pull Request** for review.

---

## 📜 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## 📧 Contact

For questions, feedback, or issues, please reach out at [your-email@example.com](mailto:your-email@example.com).

---

**Enjoy the game and challenge yourself! 🐍**
