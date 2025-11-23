# Rock-paper-scissors
Rock Paper Scissors - Python Implementation

A robust, console-based implementation of the classic "Rock, Paper, Scissors" game. This project features a continuous game loop, smart input handling, and a mathematical approach to determining the winner.

🎮 Features

Continuous Play: The game runs in a loop until the user explicitly chooses to exit.

Smart Input Handling: Accepts full words ("rock") or short-hand abbreviations ("r", "p", "s"). It is case-insensitive.

Mathematical Win Logic: Uses integer mapping (-1, 0, 1) rather than long chains of if/else statements to determine the winner.

Error Proof: The game handles invalid inputs gracefully without crashing.

🚀 Getting Started

Prerequisites

Python 3.x installed on your machine.

How to Run

Save the python script as main.py.

Open your terminal or command prompt.

Navigate to the directory containing the file.

Run the command:

python main.py


🕹️ How to Play

When prompted, enter your choice:

Type Rock, Paper, or Scissors.

Shortcuts work too: r, p, s.

The computer will reveal its random choice.

The result (Win, Lose, or Tie) will be displayed.

To quit the game, enter 0.

🧠 Logic Explanation

The game uses a numerical comparison system:

Rock = -1

Paper = 0

Scissors = 1

Instead of checking every combination, the game compares the user's number against the computer's number using logic gates to determine the winner efficiently.
