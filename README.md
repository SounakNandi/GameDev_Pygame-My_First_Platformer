# Pygame_Platformer (This is my first ever game!!)

A fun and interactive 2D platformer game built using Pygame. Navigate through challenging levels, avoid obstacles, and reach the final door to escape!

## Demo

Check out the demo video to see the game in action:

https://github.com/user-attachments/assets/f47b6bc2-9f91-4dd6-8539-65c5717aa6b7

## Installation

1. Make sure you have Python installed on your system. You can download it from [python.org](https://www.python.org/).
2. Install Pygame by running:
   ```bash
   pip install pygame
   ```
3. Clone this repository using this link or [download](https://github.com/SounakNandi/GameDev_Pygame-My_First_Platformer/archive/refs/heads/main.zip) the ZIP file and extract it:
   ```bash
   git clone https://github.com/SounakNandi/Pygame_Platformer.git
   ```
4. Navigate to the project directory:
   ```bash
   cd Pygame_Platformer
   ```
5. Run the main file:
   ```bash
   python main.py
   ```
6. Enjoy the game!

## File Structure

```bash
Pygame_Platformer
│   .gitignore
│   LICENSE
│   main.py               # Entry point for the game
│   README.md
│
└───Assets                # Game assets and modules
    │   Animation.py
    │   Background.py
    │   Blocks.py
    │   Door.py
    │   Player.py
    │   Settings.py
    │
    ├───Audio             # Game sound effects
    │       highJump.mp3
    │       jump.mp3
    │       openDoor.mp3
    │       run.mp3
    │
    └───Images            # Game images and sprites
       ├───Box
       │       Idle.png
       │
       ├───Door
       │       Closing.png
       │       Idle.png
       │       opening.png
       │
       ├───Enemy
       │   └───Block
       │           Idle.png
       │
       ├───Levels
       │       level1.png
       │       level2.png
       │       level3.png
       │       level4.png
       │
       └───Player
               enterDoor.png
               idle.png
               run.png
               runLeft.png
```

## Credits

Developed by some cool guy [SOUNAK NANDI](https://github.com/SounakNandi)<br>
Built with Pygame
