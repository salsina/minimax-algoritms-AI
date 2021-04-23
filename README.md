# minimax-algoritms-AI
black jack game. using minimax algorithm to win the computer

<h3>This is a multi agent game, The black Jack game.</h3>
There exists an opponents which cpu_play function plays against us.
our(playes) goal is to win the opponent using the minimax algorithm.

in this algorithm we predict the next 5 moves of the opponents and choose the best move we can do to win the opponent.

The actions we can take during each turn are: drawing a card from deck, erasing our last card we drew, erasing the opponents last card and stop condtinuing.

These actions can also be taken by the opponent against us.

The winner is anyone whose sum of cards is closer to the number 41 and of course his sum of numbers on his cards must be less than 41.

if the player and opponent both have the same score, the result is draw, else the winner is eighter the player or the opponent.

the game is being run 500 times and at last the win rate of the player is printed.

