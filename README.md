1. Generate a random number between 1 and 100
2. Guess the number in 10 turns
3. After each try, let player know if their guess is right or wrong
  3a. If they are wrong, let them know if the guess was too low or too high
  3b. Also tell what numbers they previously guessed
4. End game once the player guesses corectly
  4a. Or once they run out of turns
5. When the game ends, give option to start playing again


1. Generate a random number between 1 and 100.
2. Record the turn number the player is on. Start it on 1.
3. Provide the player with a way to guess what the number is, up to 10 times.
4. Once a guess is submitted, record it somewhere so the user can see their previous guesses.
5. Check whether it is the correct number.
6. If it is correct:
  6a. Display congratulations message.
  6b. Stop the player from being able to enter more guesses.
  6c. Display control allowing the player to restart the game.
7. If it is wrong and the player has turns left:
  7a. Tell the player that they are wrong.
  7b. Tell the player whether the guess was too low or too high
  7c. Allow to enter another guess.
  7d. Increment the turn number by 1.
8. If it is wrong and the player has no turns left:
  8a. Tell the player it is game over.
  8b. Stop the player from being able to enter more guesses.
  8c. Display control allowing the player to restart the game.
9. Once the game restarts, reset the game logic and UI, then go back to step 1