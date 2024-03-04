# Section 2 - Bugs
## 1. No restart button after the game concludes.(Lose)
### Description

After the player loses the game there is no button to restart the game.

### Steps
1. Player navigates to website: https://eviltester.github.io/TestingApp/games/buggygames/the_coloured_square_game/colouredsquarechanger.html
2. Player plays the game and loses the game.
### Expected Results
A restart button should be present to restart the game after the game ends.

### Actual Results
There is no button present when the game ends.

### Severity
High

## 2. Delay in reflecting lives lost
### Description

When the player loses a life, the counter for the lives lost does not immediately reflect.

### Steps
1. Player navigates to website: https://eviltester.github.io/TestingApp/games/buggygames/the_coloured_square_game/colouredsquarechanger.html
2. Player plays the game.
3. Player gets a press incorrect.
### Expected Results
Lives lost counter should immediately display when the player loses a life.

### Actual Results
When the player gets a press incorrect the lives lost counter does not immediately reflect.

### Severity
High

## 3. No text displayed when the button color is black
### Description

When the button color is black the text that reads "It is ...black" is not visible.

### Steps
1. Player navigates to website: https://eviltester.github.io/TestingApp/games/buggygames/the_coloured_square_game/colouredsquarechanger.html
2. Player observes the button change color to black.
### Expected Results
Button text should be visible when the button color is black.

### Actual Results
Button text is not readable when button color is black.

### Severity
High

## 4. The game speeds up after not playing for 10 minutes.
### Description

When you leave the game window open without making a selection for 10 minutes the games speeds up.

### Steps
1. Player navigates to website: https://eviltester.github.io/TestingApp/games/buggygames/the_coloured_square_game/colouredsquarechanger.html
2. Player does not play the game for at least 10min.
### Expected Results
Game should remain at the initial starting speed and only speed up while playing the game.

### Actual Results
Game speeds up without any player interaction.

### Severity
Low

## 5. No border around color square
### Description

When the square color goes white the square appears to disappear.

### Steps
1. Player navigates to website: https://eviltester.github.io/TestingApp/games/buggygames/the_coloured_square_game/colouredsquarechanger.html
2. Player observes color square turns white.

### Expected Results
There should be a border to outline when the square is white.

### Actual Results
White square does not show on page.

### Severity
Low

## 6. Grammar errors in title.
### Description

There are grammatical errors in title "The Coloured Square Changing Game"

### Steps
1. Player navigates to website: https://eviltester.github.io/TestingApp/games/buggygames/the_coloured_square_game/colouredsquarechanger.html
2. Player observes title on the site.
### Expected Results
The title and description should read "**The Colored Square Changing Game**".

### Actual Results
The title and description reads" page The Coloured Square Changing Game".

### Severity
Low

## 7. Grammar errors in Description.
### Description
There are grammatical errors in the description of the game site.
"The aim of the game is to Press the [It is ...] button, when the square is the same colour as the button, to score a point.  Get it wrong and lose a life".

### Steps
1. Player navigates to website: https://eviltester.github.io/TestingApp/games/buggygames/the_coloured_square_game/colouredsquarechanger.html
2. Player observes description on the site.

### Expected Results
The description should read "**The objective of the game is to press the "It is..." button when the square matches the color of the button in order to score a point.  Make a mistake, and you will lose a life.**"

### Actual Results
"The aim of the game is to Press the [It is ...] button, when the square is the same colour as the button, to score a point.  Get it wrong and lose a life".

### Severity
Low

## 8. There is no clear winning condition

### Description
There is no way to beat the game and the game does not have a clear winning condition or does not state that the game does not end.

### Steps
1. Player navigates to website: https://eviltester.github.io/TestingApp/games/buggygames/the_coloured_square_game/colouredsquarechanger.html
2. Player presses the color correctly.

### Expected Results
A clear winning condition should be described.

### Actual Results
The game continues until the player loses.

### Severity
High

## 9. The button size does not remain uniform

### Description
The size of the button changes size when the text changes.

### Steps
1. Player navigates to website: https://eviltester.github.io/TestingApp/games/buggygames/the_coloured_square_game/colouredsquarechanger.html
2. Player observes the button change colors and text.

### Expected Results
The button should have a uniform size when the text changes.

### Actual Results
The size of the button changes when the text changes.

### Severity
Medium

## 10. The game over message does not read well

### Description
After the game ends in a loss the game over message does not read well.

### Steps
1. Player navigates to website: https://eviltester.github.io/TestingApp/games/buggygames/the_coloured_square_game/colouredsquarechanger.html
2. Player plays the game and loses the game.

### Expected Results
The "score [int]" and "live [int]" is not needed
The game over message should read: "**Status: Game Over! You Scored [int]**".

### Actual Results
The game over message reads "Status: Game Over! You Scored [int] score [int] lives [int]".

### Severity
Low

## 11. Color square does not immediately change when getting it correctly

### Description
When correctly pressing any color right other then pink and red the color still remains the same color for short while 
without changing allowing for the player to get the same color right multiple times.

### Steps
1. Player navigates to website: https://eviltester.github.io/TestingApp/games/buggygames/the_coloured_square_game/colouredsquarechanger.html
2. Player presses correctly.
3. Player observes the button change but the color square does not change.

### Expected Results
Color should immediately change when getting it correctly.

### Actual Results
Color square remains the same color for a short while.

### Severity
High