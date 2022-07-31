# Tic-Tac-Toe Game


Implementation of the classic game of Tic-Tac-Toe using Reinforcement Learning with minimax algorithm & used Alpha-beta pruning to increase the efficiently of AI agent. 

<br>
In this game, the opponent is a "minimizing" agent. In practice, however, we may encounter a sub-par opponent that makes silly moves. When this happens, the algorithm's assumption deviates from the actual opponent's behavior. In this case, it still leads to the desired outcome of never losing. However, if the deviation  goes the other way (e.g. suppose we employ a "maximax" algorithm that assumes that the opponent wants us to win), then the outcome would certainly be different.
<br>
<br>

### Environment 

<br>
There are two main files in this project:
  1. runner.py : contains all of the code to run the graphical interface for the game.
  2. tictactoe.py: contains all of the logic for playing the game, and for making optimal moves. Here, we defined three variables: X, O, and EMPTY, to represent possible moves of the board.
<br>
<br> 

### Play Instruction

```
run python runner.py
```
to play against the AI. 
