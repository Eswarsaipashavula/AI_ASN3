# AI Assignment 3: Game Playing

This project implements a Chess-playing AI using the Minimax algorithm with and without Alpha-Beta pruning. It uses the gym-chess environment for simulating chess games.

## 👥 Team Members

- **Pashaula Eswar Sai** - CS24M109
- **Gooty Bharadwaj** - CS24M123

## 📌 Algorithms Implemented

- **Minimax**
- **AlphaBeta Pruning**

## 🧪 Environments Used


### **Chess**
- gym-chess environment: https://github.com/iamlucaswolf/gym-chess

## 💡 Problem Descriptions

The objective is to implement AI agents that can play the game of Chess by exploring future game states using:
- **Minimax**: A depth-limited tree search that selects moves based on minimizing the possible loss assuming an optimal opponent.
- **Alpha-Beta Pruning**: An optimized version of Minimax that prunes branches of the tree that don't affect the final decision, reducing computation time.

An evaluation function based on material balance and piece-square tables is used to assess the quality of board positions.

## 🚀 How to Run
**Minimax_on_chess**
- Running these files is really simple—just upload the `.ipynb` files to Google Colab and execute them directly. After executing cell with import statements, kindly restart the session if prompted to. Modify the depth in function call to play_minimax_game to test for value of your choice.

**AplhaBeta_on_chess**

## 📈 Evaluation Criteria

- **Performance Metrics**: Number of moves, decision time per move, win/loss against random player.
- **Depth Variations**: Agents are tested with depths ranging from 2 to 4.
- **Evaluation function**: Custom evaluation based on material value and piece-square positions.


## 🔗 Useful Links

- Minimax: https://en.wikipedia.org/wiki/Minimax  
- Alpha-Beta Pruning: https://en.wikipedia.org/wiki/Alpha–beta_pruning  
- Piece-square tables: https://www.chessprogramming.org/Simplified_Evaluation_Function  
- gym-chess environment: https://github.com/iamlucaswolf/gym-chess  
- python-chess library: https://python-chess.readthedocs.io/en/latest/
- Recorded Videos: https://drive.google.com/drive/folders/13KwRDZh7ew3a9o-13aEEuG2x0h7yVtsG?usp=drive_link