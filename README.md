# word-guess-cli
A hangman game for the command line, using node

OBJECTIVE

The goal of this particular hangman game is to teach the user all of JavaScript's reserved words. Each possible word is one of the 63 reserved words. 

INSTRUCTIONS

* TO BEGIN, USE COMMAND 'node index.js begin'
- Try to guess the word by typing one letter at a time."
- You get 16 incorrect guesses per round."
* To guess a letter in the game, type '*letter*'"
* To quit the game at any time, type Ctrl + c or Command + c"
* For a list of commands, type 'node index.js commands'"
* To repeat these instructions, use command 'node index.js instructions'"

COMMANDS

* "Access these commands when launching the game with node.");
* BEGIN A GAME: 'node index.js begin'
* LIST COMMANDS: 'node index.js commands'"
* QUIT: Ctrl + c or Command + c"
* INSTRUCTIONS: 'node index.js instructions'"
* FUN FACTS: 'node index.js fun-facts'"
* SHOW WORDS: 'node index.js show-words"

FEATURES
- Game will display the word if player loses
- Instructions and basic commands appear at start of game
- Upon completion of a game, a random fun fact will be presented
- The game can be modified for different words with little change to the actual code. Mostly the word and fun fact arrays would need to be changed.

CREDITS

* Special thanks to FrogBomb (https://github.com/FrogBomb) for suggestions that helped solve a memory leak related to listening events. 