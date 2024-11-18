# Battleship Game

Welcome to **Battleship**, a command-line version of the classic game where players strategically place their ships on a grid and take turns guessing the opponent's ship locations. The first to sink all of the enemy's ships wins!

---

## Table of Contents
1. [Features](#features)
2. [How to Play](#how-to-play)
3. [Setup Instructions](#setup-instructions)
4. [Rules](#rules)
5. [Game Flow](#game-flow)
6. [Sample Screenshots](#sample-screenshots)
7. [Credits](#credits)

---

## Features

- **Player vs. Computer Gameplay**: Face off against an AI opponent.
- **Interactive Grid System**: Use rows (`a` to `j`) and columns (`1` to `10`) to play.
- **Randomized Ship Placement**: The computer hides its ships in random locations.
- **Turn-Based Mechanics**: Alternate between shooting at the opponent and defending your ships.
- **Victory Tracking**: Tracks hits, misses, and ships remaining.

---

## How to Play

1. **Place Your Ships**:
   - You'll position 10 ships on your 10x10 grid.
   - Use row letters (`a` to `j`) and column numbers (`1` to `10`) to select positions.
   - Avoid placing multiple ships in the same space.

2. **Take Turns Shooting**:
   - Guess the location of the computer's ships by selecting a grid space.
   - The computer will randomly shoot at your grid.

3. **Winning the Game**:
   - Sink all 10 of the computer's ships to win.
   - Avoid losing all your ships to the computer!

---

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/battleship-game.git
   ```
2. **Navigate to the Directory**:
   ```bash
   cd battleship-game
   ```
3. **Run the Script**:
   Make sure you have Python installed, then run:
   ```bash
   python battleship.py
   ```

---

## Rules

1. **Ship Placement**:
   - Ships are represented by `"x"` on your grid.
   - Each ship occupies one grid space.

2. **Taking a Shot**:
   - A hit is marked with `"x"`, and a miss is marked with `"-"`.

3. **Computer's Moves**:
   - The AI randomly selects grid spaces to shoot at your board.

4. **Victory Conditions**:
   - First to sink all of the opponent's 10 ships wins.

---

## Game Flow

1. **Ship Placement**:
   - Place your ships manually by entering row letters and column numbers.

2. **Player's Turn**:
   - Choose a grid space to shoot at the computer's ships.
   - Receive feedback on hits or misses.

3. **Computer's Turn**:
   - The AI takes a random shot at your ships.
   - Feedback is provided on hits or misses.

4. **Repeat Turns**:
   - Alternate turns until one player sinks all 10 ships.

---

## Sample Screenshots

### Player Ship Placement:
```
  1 2 3 4 5 6 7 8 9 10
a| | |x| | | | | | | |
b| | | | | | |x| | | |
c| |x| | | | | | | | |
...
```

### Gameplay:
- **Player's Guessing Board**:
```
  1 2 3 4 5 6 7 8 9 10
a| | |x| | | | | | | |
b| | |-| | | | | | | |
c| | | | | | | | |x| |
...
```

- **Computer's Attacks**:
```
  1 2 3 4 5 6 7 8 9 10
a| | | | | | | |-| | |
b| | | | | | | | | | |
c| | |x| | | | | | | |
...
```

---

## Credits

- **Developer**: Yassin Fawzy, Omar Ackef
- **Inspiration**: Classic Battleship board game

Feel free to fork and improve the game! Pull requests are welcome. 😊

---

Enjoy sinking those ships! 🚢💥
