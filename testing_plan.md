# Test Plan for Simon Says, by Owen Marcus

## Part 1: Game Mechanics

Does the game start when pressing a segment? Does the button light up when you press it? Does it generate a sequence, and does it only let you pass if you get the sequence right, and restart if you fail? Does the game report your score? Do new segments generate when it is the third cycle?

## Part 2: Logic

Does the game accurately save the high score? Does the game accurately depict the current score? Are the sequences truly random? Do the new sequences include new segments?

## Part 3: Edge-Cases

Does the high-score stop reporting at one quadrillion? Does the current score stop reporting at one quadrillion? Are the infinitely thin segments selectable by arrow keys? Does the random sequence behave strangely after an amount of time?

## Part 4: Integration Testing

Does the score appear on the screen? Are all graphics interactable? How does restarting the game due to a loss appear?

## Part 5: Bad Input and Runtimes

Does the game deny inputs when they are too frequent to prevent memory problems? Does it report what state the game is in when an error happens?

## Part 6: Table

I was told not to include the table.
