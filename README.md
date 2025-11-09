🎲 Snakes and Ladders (C++ Console Game)

This is an interactive Snakes and Ladders game built using C++. The game supports 2 to 4 players, features a zig-zag formatted board, snakes and ladders mechanics, and real-time board updates after every move. It runs directly in the terminal/console, making it simple and fun to play.

🕹️ Features

Supports 2 to 4 players

Real-time board visualization in a zig-zag layout (similar to the real board)

Snakes and Ladders implemented using a map for quick lookup

Random dice roll using rand() for realistic gameplay

Prevents overshooting above 100

Detects win condition and allows restarting the game

Simple and clean user interface in terminal

📌 How to Play

Compile and run the program.

Enter the number of players (between 2 and 4).

Enter each player's name.

On each turn:

Press 1 to roll the dice

Press 2 to quit the game

First player to reach exactly 100 wins the game!

If a player lands:

At the bottom of a ladder, they climb up.

On the head of a snake, they slide down.

🛠️ Compilation & Execution
Using g++:
g++ -o snakes_and_ladders main.cpp
./snakes_and_ladders


Make sure the file name matches your .cpp file.

📂 Project Structure
.
├── main.cpp        # Source code
└── README.md       # Documentation

✅ Example Gameplay Screenshot (Console)
Welcome to Interactive Snakes and Ladders!
Enter number of players (2-4): 2
Enter name for Player 1: Alex
Enter name for Player 2: Riya

Board (1-100, L=Ladder, S=Snake, P=Player):
...
Alex's turn. Press 1 to roll, 2 to quit:

📄 License

This project is released under the MIT License — feel free to modify and improve it!

🤝 Contributions

Contributions are welcome!
Feel free to submit issues or pull requests.
