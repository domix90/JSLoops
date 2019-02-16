# JSLoops
Example codes of loops I created


Every scripts.js file has a comment of what the program does. Please read the script.js files


while () { /* If the condition is False the code never runs */
}

do { /* If the condition is false the code runs at least once before the condition is checked */
} while ()


You can use a 'break' statement to break out of the loop. 

while (guessCount < 10 ){
  guess = prompt('I am thinking of a numer from 1 to 10. What is it? )
  guessCount += 1;
  if (parseInt(guess) === randomNumber ) {
    correctGuess = true;
    break;
  }
}
