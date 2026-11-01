# Tic-Tac-Toe AI

A simple yet polished Tic-Tac-Toe game built with Python and Tkinter, where the player competes against an unbeatable AI opponent. The game uses the Minimax algorithm to evaluate the board and choose the strongest move available.

## Features

- Interactive graphical board built with Tkinter
- Human vs. AI gameplay
- Unbeatable AI using the Minimax algorithm
- Automatic win, loss, and draw detection
- Instant AI response after each player move
- Clean interface and reset between rounds
- Object-oriented Python implementation

## How the Game Works

- The player always plays as X.
- The AI plays as O.
- After each move, the game checks whether the player has won or if the board is full.
- If the game continues, the AI evaluates all possible moves using Minimax.
- The AI chooses the move that leads to the best possible outcome.
- The game then resets automatically after a win, loss, or draw.

## Project Structure

```text
.
├── README.md
├── tic_tac_toe.py
└── .gitignore
```

## Requirements

- Python 3.x
- Tkinter (usually included with Python on most systems)

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/morshed11s/Simple-Tic-Tac-Toe-with-AI.git
```

2. Navigate to the project folder:

```bash
cd tic-tac-toe-ai
```

3. Run the game:

```bash
python tic_tac_toe.py
```

If Python is not linked as `python` on your machine, try:

```bash
python3 tic_tac_toe.py
```

## Gameplay

- Click any empty square on the board to place your X.
- The AI will respond with its move as O after a short delay.
- The game ends when either side completes a row, column, or diagonal, or the board fills up.
- A message box appears to announce the result, and the board resets for a new round.

## Technologies Used

- Python
- Tkinter
- Object-Oriented Programming
- Minimax Algorithm
- Game state evaluation

## Future Improvements

- Difficulty levels
- Highlight the winning line
- Score tracking across rounds
- Player name customization
- Sound effects
- Dark mode
- Undo move option

## Learning Goals

This project demonstrates:

- Python GUI development with Tkinter
- Event-driven programming
- Game logic and state management
- Artificial intelligence through minimax decision-making
- Clean object-oriented design in a small project

## Author

Sumaiya Morshed

Computer Science Graduate

Feel free to explore the project, try the game, and share feedback or ideas for improvement.
