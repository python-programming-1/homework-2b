# Homework 2B

# Let's Make A Game! 
## Can you make rock paper scissors?

For this assignment you'll make a rock paper scissors game!

1. git clone this repository like you did in homework-2a
2. create a file named rock_paper_scissors.py
3. Your program should print "make a move! (r/s/p)"
4. Your program should accept 6 inputs: 'r' for rock, 'p' for paper, 's' for scissors and 'y' for yes and 'n' for no, 'sc' for score.
5. Your program should randomly select a move. See https://docs.python.org/3/library/random.html for reference.
5. Your program should output the following line with one of the options (rock, paper, scissors) for the computer and yourself:
'You chose 'rock/paper/scissors' and the computer chose 'rock/paper/scissors'. You Win/Lose!
6. After a game, the computer should ask you 'Do you want to play again? (Y/N)?' If you enter 'y' the game should start over, if you enter 'n' the program should exit after saying "thanks bye!".
7. If a player inputs 'sc' return a score like: 'human: X, computer: Y'
8. Bonus: Can you make the computer smarter? Instead of a random move, have the computer make a move based on the player's history of moves.
So if the player has played scissor three times, the computer may try to play rock.

Sample output:

>>Make a move! (r/s/p)
r
>> You chose rock and the computer chose scissors. You win!
sc
>> human: 1, computer: 0
>> Do you want to play again? (Y/N)
n
>>Thanks bye!
