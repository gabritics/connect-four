# Four Wins (Connect Four) – FOPBot

A lightweight **Connect Four** implementation in **Java** using the **FOPBot** simulation framework.
Players drop colored tokens into a grid; the first to align **four** tokens horizontally, vertically, or diagonally wins.
The board is rendered as a FOPBot world; tokens are represented by robots colored with `RobotFamily.SQUARE_BLUE` and `RobotFamily.SQUARE_RED`.

---

## Features

- Grid-based Connect Four board (works with **variable sizes**)
- Token drop animation from the **top row** to its **destination row**
- Win detection for **horizontal**, **vertical**, and **diagonal** sequences
- Simple input handling and clear end-of-game messages
- Clean separation between **game loop**, **board state**, and **helpers**

---

## Tech Stack

- **Language:** Java 17+
- **IDE:** IntelliJ IDEA (recommended)

---

## Getting Started

1. **Clone** or download this repository.
2**Run the game:**
    - Open `Main.java` and run `Main.main()`
    - Alternatively, `new FourWins().startGame()` where provided

---

