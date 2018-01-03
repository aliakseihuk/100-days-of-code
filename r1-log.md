# #100DaysOfCode Log - Round 1 - [Basecoplan]

The log of my #100DaysOfCode challenge. Started on [January 03, Wednesday, 2017].

## Log

### R1D1
#### First day of the commitment and just another day with word-game

Proceeded to work with my current pet-project which is called [word-game](https://github.com/aliakseihuk/word-game/).
The idea is based on one of the games from Mike Byster's book "The Power of Forgetting: Six Essential Skills to Clear Out Brain Clutter and Become the Sharpest". Two person have words and check after each other if some letter exists in opponent's word. Each participant has to guess the word.

Today I've just implemented ai execution flow:

1. Try to find a new letter if the word has empty letters;
2. Try to shuffle letters if the letters don't produced familiar word from vocabulary
3. Win if the word matches

Of course, there are a lot of improvements and optimizations of the flow and it's a dummy algorithm for a current period of time, but this step allows me to continue.

Great ideas of the day:
 1. Move user and ai substates to nested reducer.
 2. Fill description of the project.

### R1D2
