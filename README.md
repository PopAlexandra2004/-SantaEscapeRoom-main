# 🎅 Santa's Escape Room

**Santa's Escape Room** is a grid-based puzzle game where players guide Santa to collect presents, avoid obstacles, and outsmart the Grinch to escape through the chimney.  
This project combines manual gameplay with AI-driven autonomous navigation powered by **Prover9**, a logical theorem prover.

---

## 🌟 Features

- **Manual Gameplay**: Navigate Santa through the grid using arrow keys.  
- **Autonomous Mode**: Activate AI to let Santa solve the puzzle using logic-based navigation.  
- **Dynamic Clues**: Visual indicators like cookie smells, cold breezes, and flour traps guide gameplay.  
- **Randomized Grinch Movement**: The Grinch creates dynamic danger zones.  
- **Win/Lose Conditions**: Collect all presents and escape, or get caught by the Grinch.

---

## 📁 Project Structure

### Core Files

- `main.py` – Entry point for the game. Manages game flow, user input, and component interactions.  
- `config.py` – Configures screen dimensions, fonts, and Pygame settings.  
- `constants.py` – Defines constants like colors, grid size, and legend labels.  
- `grid.py` – Handles grid rendering, visual clues, and legend display.  
- `game_logic.py` – Implements gameplay rules, collision detection, and Grinch movement.  
- `validator.py` – Integrates Prover9 for AI-driven navigation and clue-based logic.  
- `instructions.py` – Displays the rules and controls for the game.

### Prover9 Integration

- `santa_logic.p9` – Dynamically generated input file for Prover9, containing grid relationships and clues.  
- `santa_logic.out` – Output file generated by Prover9 with the results of logical reasoning.

---

## 🕹️ How to Play

### Run the Game

```bash
python main.py
