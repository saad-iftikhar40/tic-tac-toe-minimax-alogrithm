# Tic-Tac-Toe with AI (Minimax Algorithm)

A classic Tic-Tac-Toe game with a perfect-playing AI opponent built using the **Minimax algorithm** — the computer will **never lose** (it either wins or forces a draw).

Made with **Python** + **Pygame** for a nice graphical interface.

https://github.com/yourusername/tictactoe/assets/123456789/abcdef12-3456-7890-abcd-ef1234567890  
*(replace with your own screenshot/GIF later if you record one)*

## Features

- Beautiful retro-style graphical interface using Pygame
- Play as **X** (first) or **O** (second)
- Unbeatable AI using the Minimax algorithm (with alpha-beta pruning possible in future versions)
- Clean win/tie detection
- "Play Again" button after game ends
- Smooth gameplay with short thinking delay for realism

## Screenshots

*(Add 2–4 screenshots here later – title screen, mid-game, win screen, tie screen)*

## How to Play

1. Choose whether you want to play as **X** or **O**
2. Click on an empty cell to make your move
3. The computer will respond automatically
4. When the game ends → click **Play Again** to restart

## Requirements

- Python 3.6+
- Pygame (`pip install pygame`)

## Installation & Running

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/tictactoe.git
cd tictactoe

# 2. (Recommended) Create virtual environment
python -m venv venv
source venv/bin/activate    # Linux / macOS
venv\Scripts\activate       # Windows

# 3. Install dependencies
pip install pygame

# 4. Make sure you have the font file
#    → OpenSans-Regular.ttf should be in the same folder as runner.py
#    (or change the fontpath in runner.py if you prefer another font)

# 5. Run the game
python runner.py
