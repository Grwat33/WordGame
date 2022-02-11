# WordGame

Like many, I have become obsessed with Wordle, and one word per day is just not enough for me. I typically have the word of the day completed before I get out bed in the morning, and can just never really seem to get enough. I wondered if there was a way to play the game more than once a day, and I ultimately decided to code a way.

The rules are simple. You have 6 guesses to guess a 5-lettered word. You learn if each guess shares similar letters to the correct word, and if your similar letters are in the correct spot. If you are able to guess the correct word within 6 guesses, you win! If not, your streak ends, and you move onto the next word.

Here is my attempt at Wordle through Python in a Jupyter Notebook using a 5-lettered words .txt file from Stanford University.

Despite more simple aspects of my code such as for loops, if statements and local/global variable declarations, I was able to learn how to use the PyEnchant library. This library will check a string and return True if the string is found to be an actual word. 

When I thought I had completed the game, I had found that some of the 5 letter words in the Standford University .txt file weren't familiar to me, and they apparently weren't familiar to the PyEnchant library either. Dropping falses took the .txt file from 5757 words to 5280 words, and I have found myself to be more familiar with the words I am attempting to guess.

I hope that adding statistics and visualizations to game performance makes it more interesting! Simply insert your 5-lettered word guess in between the quotes in the guess() function in the bottom cell to get started! Insert your next guess into the same cell over your previous guess, and just keep editing and running that cell for as many Wordle games in one day as you choose!
