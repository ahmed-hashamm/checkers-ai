
# Checkers AI with Minimax and Alpha-Beta Pruning

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://python.org)
[![AI](https://img.shields.io/badge/AI-Minimax-orange)](https://en.wikipedia.org/wiki/Minimax)
[![Game](https://img.shields.io/badge/Game-Checkers-red)](https://en.wikipedia.org/wiki/Draughts)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

A console-based Checkers implementation featuring an AI opponent using Minimax with Alpha-Beta pruning.

## Features
- Pure Python implementation
- Console-based interface (focus on algorithms)
- Adjustable AI difficulty
- Full game rules enforcement
- Move validation and error handling

## Installation
```bash
git clone https://github.com/yourusername/checkers-ai.git
cd checkers-ai
python checkers.py

How It Works
The AI uses:

Minimax algorithm with depth-limited search

Alpha-Beta pruning for optimization

Evaluation function considering:

Piece advantage (regular vs kings)

Board position control

Potential forced captures

King safety

Gameplay Example

5,0 to 4,1  # Player move
AI responds: 2,1 to 3,0

Future Enhancements
GUI implementation

Improved heuristics

Move history tracking

Multiplayer mode

Contributing
Fork the repository

Create a feature branch

Commit your changes
Push to the branch
Open a pull request
