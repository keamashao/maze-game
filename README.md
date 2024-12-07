Maze Game README
Welcome to the Maze Game! This game is a maze-based adventure similar to the classic Pac-Man game. The objective is to navigate through the maze, avoid the enemy monsters, and collect treasures while listening to the jungle sounds in the background.

Table of Contents
Game Overview
Files Description
How to Play
Installation
Game Controls
Sounds and Music
Credits
Game Overview
In this maze game, you control a hero character and attempt to navigate through a maze. Your goal is to collect all the treasures while avoiding the enemy monster (a cyborg) that roams the maze. The game features engaging jungle background sounds, and various sound effects trigger during interactions such as wall collisions and treasure collection.

Files Description
The following files are used in this game:

background.jpg
This image file serves as the background for the maze game. It is used to give the game an immersive, jungle-like atmosphere.

cyborg.png
This image file represents the enemy monster (Cyborg) in the game. The cyborg chases the player through the maze and adds a challenging element to the gameplay.

hero.png
The hero image file represents the player character. This file is used to render the player’s sprite during the game.

jungles.ogg
A jungle-themed background sound that plays continuously while the game is running. It sets the mood and adds an auditory atmosphere to the maze.

kick.ogg
This sound effect plays when the player collides with a wall inside the maze. It adds an extra layer of interactivity to the game.

money.ogg
This sound effect plays when the player collects a treasure, giving auditory feedback that the player has scored.

treasure.png
The treasure item that the player needs to collect throughout the game. This file is used to render the treasure sprite that the player picks up for points.

maze.py
The Python code that runs the entire game. This file links all of the assets together, including the images, sounds, and gameplay logic. It uses Python libraries like pygame to handle the graphical interface and game mechanics.

How to Play
Launch the game by running maze.py.
Move your hero around the maze using the arrow keys.
Your objective is to collect all the treasures in the maze while avoiding the cyborg (enemy monster).
When you collect a treasure, you earn points and hear the money sound.
If you collide with a wall, the kick sound will play, and you will lose time or points.
Keep an eye on the cyborg and try to avoid it as it chases you through the maze.
Installation
To play the Maze Game, you need to have Python installed along with the pygame library.

Install Python:
Download and install the latest version of Python from python.org.

Install Pygame:
Open a terminal or command prompt and run:

Copy code
pip install pygame
Download the Game Files:
Ensure that all the game files (background.jpg, cyborg.png, hero.png, jungles.ogg, kick.ogg, money.ogg, treasure.png, and maze.py) are in the same folder.

Run the Game:
Open a terminal or command prompt, navigate to the folder where the game files are located, and run:

Copy code
python maze.py
Game Controls
Arrow keys: Move the player character (hero) up, down, left, or right.
Esc: Exit the game.
Sounds and Music
The game includes several sound effects and background music that enhance the gaming experience:

jungles.ogg: Plays continuously as background music, giving a jungle-like atmosphere.
kick.ogg: Played when the player hits a wall in the maze.
money.ogg: Played when the player collects a treasure.
Make sure your sound system is on so you can hear all the immersive sounds!

Credits
Game Development: keabetswe
