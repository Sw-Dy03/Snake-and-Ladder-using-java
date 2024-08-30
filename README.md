# SnakeAndLadderDesign

- Format: <player_name> rolled a <dice_value> and moved from <initial_position> to <final_position>

- When someone wins the game, print that the player won the game.
- Format: <player_name> wins the game

## Rules of the game
- The board will have 100 cells numbered from 1 to 100.
- The game will have a six sided dice numbered from 1 to 6 and will always give a random number on rolling it.
- Each player has a piece which is initially kept outside the board (i.e., at position 0).
- Each player rolls the dice when their turn comes.
- Based on the dice value, the player moves their piece forward that number of cells. Ex: If the dice value is 5 and the piece is at position 21, the player will put their piece at position 26 now (21+5).
- A player wins if it exactly reaches the position 100 and the game ends there.
- After the dice roll, if a piece is supposed to move outside position 100, it does not move.
- The board also contains some snakes and ladders.
- Each snake will have its head at some number and its tail at a smaller number.
- Whenever a piece ends up at a position with the head of the snake, the piece should go down to the position of the tail of that snake.
- Each ladder will have its start position at some number and end position at a larger number.
- Whenever a piece ends up at a position with the start of the ladder, the piece should go up to the position of the end of that ladder.
- There could be another snake/ladder at the tail of the snake or the end position of the ladder and the piece should go up/down accordingly.

## Assumptions you can take apart from those already mentioned in rules
- There won’t be a snake at 100.
- There won’t be multiple snakes/ladders at the same start/head point.
- It is possible to reach 100, i.e., it is possible to win the game.
- Snakes and Ladders do not form an infinite loop.

## Sample Input
- 9
- 62 5
- 33 6
- 49 9
- 88 16
- 41 20
- 56 53
- 98 64
- 93 73
- 95 75
- 8
- 2 37
- 27 46
- 10 32
- 51 68
- 61 79
- 65 84
- 71 91
- 81 100
- 2
- Swagnik
- Mayukh
- Dhruba


## Output

Swagnik rolled a 1 and moved from 35 to 36
Mayukh rolled a 4 and moved from 28 to 32
Dhruba rolled a 5 and moved from 75 to 80
Swagnik rolled a 4 and moved from 36 to 40
Mayukh rolled a 5 and moved from 32 to 37
Dhruba rolled a 1 and moved from 80 to 81
Swagnik rolled a 3 and moved from 40 to 43
Mayukh rolled a 2 and moved from 37 to 39
Dhruba rolled a 3 and moved from 81 to 84
Swagnik rolled a 5 and moved from 43 to 48
Mayukh rolled a 4 and moved from 39 to 43
Dhruba rolled a 2 and moved from 84 to 86
Swagnik rolled a 2 and moved from 48 to 50
Mayukh rolled a 3 and moved from 43 to 46
Dhruba rolled a 5 and moved from 86 to 91
Swagnik rolled a 3 and moved from 50 to 53
Mayukh rolled a 4 and moved from 46 to 50
Dhruba rolled a 1 and moved from 91 to 92
Swagnik rolled a 3 and moved from 53 to 56
Mayukh rolled a 2 and moved from 50 to 52
Dhruba rolled a 2 and moved from 92 to 94
Swagnik rolled a 2 and moved from 56 to 58
Mayukh rolled a 3 and moved from 52 to 55

   
