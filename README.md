# Rock-Paper-Scissors

## Description
For Morning Exercise, we will build Rock-Paper-Scissors to practice using JavaScript and implementing more complex logic. 

You will need to design logic for the game so that one person can play against the computer multiple times and update a scoreboard that will keep track of how many wins each "player" has. 

**Note:** I did not design the HTML and CSS for this exercise. 

## Desired Functionality
The flow of this app should be:

1. User selects Rock, Paper, or Scissors by clicking on a button.
2. After clicking a button for either Rock, Paper, or Scissors several things need to happen in your JS file
	1. The user's selection must be stored so it can be compared later to the computer's selection
	2. The computer must make it's selection. To do this, generate a random number and use an if/else statement to "choose" either Rock, Paper, or Scissors
	3. Compare the two choices to determine a winner and then...
		1. Display the winner's "name" on the screen
		2. Display which "value" each side chose
	4. Update the scoreboard that shows how many times each player (human or computer) has won 
3. Now that the first game has been resolved, the user can make another selection that will clear out the winner text from Step 2.3 and start the process over again

## bonus
generate a random img inside random-img class