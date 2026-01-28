## Arkanoid Game / (Python, Tkinter, game physics, arcade)

### This is a classic arcade game called Arkanoid, designed to reinforce hands-on Python experience.

![Arkanoid Game](images/Screenshot.jpg)

### In this project, the following were implemented:
- Game loop and event handling system
- Ball physics with bounce mechanics
- Keyboard platform control
- Block destruction system with collision detection
- Score tracking and scoring
- Life system: 3 lives per game
- Dynamic increase in ball speed as blocks are destroyed
- Game state management: start, game, end of game

### Start-up instructions

1. **Clone the repository:**
    ```bash
    git clone <repo-url>
    ```
    ```bash
    cd arkanoid-game
    ```
    ```bash
    python -m venv .venv
    ```
    ```bash
    source .venv/bin/activate # On Windows: .venv\Scripts\activate
    ```
2. **Run the game:**
   ```bash
   python main.py
   ```
3. **Controls:**
   - **A** — move platform left
   - **D** — move platform right
   - **Space** — start new game
