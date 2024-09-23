# Project 3 Random Number Guesser HINTS

Here is a description of all steps required:
- Import the random library
- Create a random number between 0 and 100
- Create an infinite loop and ask the user for a guess inside the loop
- Check inside the loop if the guess equals the random number. If so print "Hurraaa you won! {guess} was the correct guess."
    - At this point you can optionally ask the user if they want to play again. If they answer yes then overwrite the random number with a new random number
    - If they don't want to play again or you don't want to implement the option to play again: break the loop
- Else if the guess is larger than the random number print "Go lower!"
- Else print "Go higher!"