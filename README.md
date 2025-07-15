# Hang-Man-Game-Java-Project
# 🎮 Hangman Game - Java GUI

This is a simple **Hangman game** implemented in Java using **Swing GUI components**. The player guesses letters to complete a hidden word, with a limited number of incorrect attempts allowed.

---

## 📁 Project Structure

- **`HangmanGameGUI.java`**: Main Java class implementing the GUI and game logic.
- **Assets** *(optional)*: You can add images or icons if desired for a more interactive UI.

---

## 🧠 Features

- Graphical User Interface using **Java Swing**
- Random word selection from predefined list
- Letter-by-letter guessing mechanism
- Displays:
  - Hidden word progress
  - Incorrect guesses left
  - Message area for win/loss prompts
- Reset/New Game functionality

---

## ✅ Requirements

- Java JDK 8 or above
- IDE like IntelliJ, Eclipse, or can be compiled via terminal

---

## 🚀 How to Run

### Using Terminal

```bash
javac HangmanGameGUI.java
java HangmanGameGUI
```

### Using IDE
1. Open the `.java` file in your IDE.
2. Run the `HangmanGameGUI` class.

---

## 📝 Example

```
Word: _ _ _ _ _
Guess a letter: A
Word: _ A _ _ _
Incorrect guesses left: 5
...
```

Game ends with either:
- **You Win!** when the word is fully guessed
- **You Lose!** when all attempts are used up

---

## 💡 Customization

- You can extend the word list with a file-based dictionary.
- You can replace text feedback with graphical hangman drawing using `JPanel`.

---

## 📧 Author

**Vignesh**  
 CSE Graduate | Passionate about game dev and GUI projects
