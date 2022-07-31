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
<img width="300" alt="1_game_start" src="https://user-images.githubusercontent.com/16225506/182028991-b7fe86a7-22f2-48de-9351-c5cba14ef923.png">

<img width="300" alt="2_game_play" src="https://user-images.githubusercontent.com/16225506/182029002-23a6bff2-d391-4529-babc-0131d788613d.png">

<img width="300" alt="3_game_result" src="https://user-images.githubusercontent.com/16225506/182029007-a3eba774-ff79-46c7-b810-e44f8cef9ccc.png">
<br>
<br>

### Play Instruction

```
run python runner.py
```
to play against the AI. 
