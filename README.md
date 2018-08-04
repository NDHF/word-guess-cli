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

UPCOMING FEATURES
* Clarify that players guess one word at a time
* Maybe add a 'solve' function
* Add a standard 'hint' console log, suggesting the user try vowels first
* Add another 'hint' console log for the GAME OVER function, reminding them of the "SHOW WORDS" command 
* List all letters guessed so far in a console log
* Make game easier to modify for other word banks
- For example, make functions take arrays as an argument, rather than name the array within the function itself
* Read/write wins and losses to a file, so they don't disappear after quitting
* A simple achievement system, using the read/write method
- Some achievement ideas: correctly guess all the reserve words, winning 10/100/500 rounds.

CREDITS

* Special thanks to FrogBomb (https://github.com/FrogBomb) for suggestions that helped solve a memory leak related to listening events. 