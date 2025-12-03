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
