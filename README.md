# 🐍 Snake Game - JavaFX Edition 🎮

A **classic Snake Game** built using **JavaFX**, featuring smooth gameplay, a custom game icon, and an interactive start menu. 🚀

---

## 📌 Features

✅ **Custom Game Icon** (Set from `snake.png`)
✅ **Modern UI Design** with hover effects
✅ **Start Menu** with "Start Game" & "Exit" buttons
✅ **Grid-Based Movement System**
✅ **Dynamic Snake Growth**
✅ **Score Tracking & High Score System**
✅ **Game Over & Restart Mechanism**
✅ **Future Features** (Power-ups, Obstacles, Levels, etc.)

---

## 🎮 How to Play

- Use **Arrow Keys** (⬆️⬇️⬅️➡️) or **WASD** to move the snake.
- Eat the **red food** 🟥 to grow longer and increase your score.
- Avoid colliding with the **walls** or **your own tail**.
- Try to beat your **High Score**! 🏆

---

## 🛠️ Technologies Used

- **Java 17+** (Core logic)
- **JavaFX** (UI & Graphics Rendering)
- **FXML** (Layout management)
- **Maven** (Dependency Management)

---

## 📂 Project Structure

```
SnakeGame/
│── src/main/java/com/example/snakegame/    # Java source files
│── src/main/resources/com/example/         # Game assets (Icons, images)
│── target/                                 # Compiled files
│── .gitignore                              # Git ignored files
│── pom.xml                                 # Maven dependencies
│── README.md                               # Project documentation
```

---

## 🚀 Installation & Setup

1️⃣ **Clone the repository:**  
```bash
Download all the files!
```

2️⃣ **Run using IntelliJ IDEA or any Java IDE:**  
- Open the project
- Run `SnakeGame.java` inside `com.example.snakegame`

3️⃣ **Using Terminal (Maven Build & Run):**  
```bash
mvn clean install
mvn javafx:run
```

---

## 🎯 Code Breakdown

### 🏁 `SnakeGame.java` (Main Game Logic)
- Initializes the **JavaFX Application**.
- Handles **game start, pause, and restart**.
- Sets **window properties** and **game icon** (`snake.png`).

### 📜 `GameController.java`
- Controls **snake movement & direction**.
- Manages **collision detection**.
- Handles **food spawning & score updates**.

### 🎨 `UIController.java`
- Controls **menu buttons & hover effects**.
- Manages **scene transitions**.

---

## 🔥 Future Improvements

- 🌟 Add different **difficulty levels**
- 💾 Implement a **persistent high-score system**
- 🏁 Introduce **new game modes** (Time Attack, Endless Mode)
- 🎨 Improve UI & animations for a better experience

---

## 🤝 Contributing

Contributions are welcome! Feel free to **fork** this repository and submit a **pull request**. 🚀

---

## 📜 License

This project is **open-source** under the **MIT License**.

---

👨‍💻 Developed by **Injabin** | Follow me on **GitHub**: [Injabin](https://github.com/Injabin) 🚀
