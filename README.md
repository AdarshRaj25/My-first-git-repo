# My-first-git-repo
<br>
author:Adarsh
🕹️ Obstacle Dodging Game (C • Windows 11 Compatible)

A fast-paced lane-based obstacle dodging game written in pure C for the Windows console.
The game was updated to fully support Windows 11, add sound effects, dynamic speed, levels, and a proper score system.

🚀 Features

✔ Three-lane dodging gameplay

✔ Windows 11 compatible (no broken ASCII characters)

✔ Smooth arrow key movement (← and →)

✔ Optional A/D movement keys

✔ Randomized obstacles (# or X)

✔ 3 Lives system

✔ Level progression (every 10 dodges)

✔ Speed increases with each level

✔ Sound effects

Movement

Collision

Level Up

Game Over

✔ Scoreboard showing:

Lives

Level

Speed

Total Dodged

🎮 Controls
Key	Action
←	Move Left
→	Move Right
A	Move Left
D	Move Right
🖥️ Gameplay Preview
LIVES: 3   LEVEL: 1   SPEED: 110ms   DODGED: 0
|--- --- ---|
|     #     |
|           |
|           |
|           |
|           |
|           |
|           |
|           |
|           |
|     @     |

🔧 Compilation (GCC / MinGW / WinLibs)
gcc main.c -o obstacle.exe


Run:

obstacle.exe


Works on:
✔ Windows 10
✔ Windows 11
✔ CMD, PowerShell, VSCode Terminal, CodeBlocks

📂 Project Structure
/Obstacle-Dodger
 ├── main.c        // Updated Windows 11 compatible version
 ├── ORIGINAL.c    // Original ASCII-based version (optional)
 └── README.md

🛠️ Improvements Over Original Version

Removed unsupported ASCII characters (1 and 6)

Added reliable symbols (@, #, X)

Added sound effects

Added lives and collision system

Added level-up system

Added dynamic speed

Enhanced obstacle logic

Full screen refresh and smooth rendering

📄 License

Free to use, modify, and learn from.
(You may add MIT License if you want.)

👤 Author

Adarsh Raj
🕹️ Obstacle Dodging Game — C Programming Project

This repository contains my Obstacle Dodging Game written in C for the Windows console.
The project demonstrates concepts such as functions, structures, keyboard input handling, randomization, and game loop logic.
It also includes Windows-friendly improvements like sound effects, dynamic speed, and level progression.

📂 Folder Structure
Obstacle-Dodging-Game/
│
├── ORIGINAL.c        // Original version (ASCII-based)
├── main.c            // Updated, Windows 11 compatible version
└── README.md

🎯 Project Objectives
🧩 Objective — Create a Console-Based Obstacle Dodging Game

This project focuses on learning and applying:

Keyboard input handling (_kbhit(), getch())

Randomized obstacle generation

Game loops & frame-based animation

Collision detection

Use of structures (struct Obstacle)

Sound integration using Beep()

Dynamic difficulty scaling (levels + speed)

Clean console rendering using system("cls")

🕹️ Game Features
✔ Windows 11 Compatible

Replaced unsupported ASCII characters and improved console rendering.

✔ Player Movement

Move left or right across 3 lanes using:

Arrow keys

A / D keys (optional)

✔ Obstacles

Random lane

Random symbol (# or X)

Smooth falling animation

✔ Scoreboard

Shows:

Lives

Level

Speed

Total dodged obstacles

✔ Sound Effects

Move

Hit

Level Up

Game Over

📄 Files Description
main.c

The final Windows-compatible version that includes:

Sound effects

Levels and speed system

Collision handling

Scoreboard

Improved obstacle logic

ORIGINAL.c

The first simple implementation:

Single ASCII character obstacle

No sound

No levels or lives

Basic movement

Included to show progress and improvement.

⚙ How to Compile and Run
✅ Using GCC (MinGW / WinLibs / TDM-GCC)

Open the game folder, then run:

gcc main.c -o game.exe


Then start the game:

./game.exe

🖥️ Gameplay Output Preview
LIVES: 3   LEVEL: 1   SPEED: 110ms   DODGED: 0
|--- --- ---|
|     #     |
|           |
|           |
|           |
|           |
|           |
|           |
|           |
|           |
|     @     |
