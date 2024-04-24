First I import the random module which is used to select a random word from the word bank.
Then I define a list I chose of elements choosing the words
I made the code select a random word from the wordbank using "random.choice(wordbank)" and then I assigned it to the variable "word_to_guess".
I think made the vairables I would be utilizing in the code and printed the welcome message to start the game
starting a loop i made it always display the amount of attempts while giving an input for the user to guess the "word_to_guess" while putting a string titled "display" to represent the current state of the word to be guessed.
It goes through each letter in the word_to_guess and checks if it has been guessed or not. If guessed, it adds an underscore to display, however i couldnt figure out how to not make the letter appear in the word_to_guess so i made the else statement an underscore too which makes it a bit messy but I couldnt figure it out.
i then made the winning conditions which if guesssed letters = word_to_guess player wins and if attempts == 0 game is over
the code will inform the player if the guessed letter is correct but i wasnt able to make it add the guessed letter to the guessed_letters list.
It counts the occurrences of the guessed letter in the word and prints the count to the user and it decreases the attempts count by 1 after each guess.
If the player runs out of attempts or word guesses, it reveals the correct word. I tried to make it end the game and it will display the end game message but it doesnt quite end the game.
lastly it also gives the player the choice to guess the word in its entirety with 3 tries for that.

