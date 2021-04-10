# Proposal

## What will (likely) be the title of your project?

TODO

## In just a sentence or two, summarize your project. (E.g., "A website that lets you buy and sell stocks.")
A two-player game of Yahtzee.

## In a paragraph or more, detail your project. What will your software do? What features will it have? How will it be executed?

My program will go through the 13 rounds of Yahtzee, and during each round, each player will roll 5 dice for three turns. During each turn, the current player will have the ability to hold or re-roll some of the dice. If the player chooses not to re-roll, they will enter no dice value. Once the current player's third roll is completed, the "possible" scorecard will be generated, showing the points that the current roll can get in each of the 13 scoring brackets. For the 13 scoring brackets, there will be functions set up to determine how many points the current roll will receive. At this point, the current player will be able to pick where they want their current roll to go, and their scorecard will be updated. The bracket that they choose will not be updated for the remainder of the game. Once the 13 rounds are completed, bonuses will be added to the scorecard if the players scored higher than 63 in the upper section. After all scores are calculated, both scorecards will be shown and the winner of the game will be shown. 

## If planning to combine 1051's final project with another course's final project, with which other course? And which aspect(s) of your proposed project would relate to 1051, and which aspect(s) would relate to the other course?

Not planning to combine this final project with another

## If planning to collaborate with 1 or 2 classmates for the final project, list their names, email addresses, and the names of their assigned TAs below.

Not planning to collaborate 

## In the world of software, most everything takes longer to implement than you expect. And so it's not uncommon to accomplish less in a fixed amount of time than you hope.

### In a sentence (or list of features), define a GOOD outcome for your final project. I.e., what WILL you accomplish no matter what?

- 13 full rounds 
- Each player will have 3 turns to roll
- Each player will be able to re-roll the dice they choose
- If the player chooses not to re-roll, they will still go through 3 turns 
- Alternating turns 
- Current roll will be scored for all 13 scoring brackets
- "Possible" scorecard
- Updating Scorecard

### In a sentence (or list of features), define a BETTER outcome for your final project. I.e., what do you THINK you can accomplish before the final project's deadline?

- Allowing the user choose where they want their current roll to be scored (I might just let the program choose for them and choose the highest score for the current roll)
- Taking out bracket if it already has a score 

### In a sentence (or list of features), define a BEST outcome for your final project. I.e., what do you HOPE to accomplish before the final project's deadline?

- show scorecard in a neater way 

## In a paragraph or more, outline your next steps. What new skills will you need to acquire? What topics will you need to research? If working with one of two classmates, who will do what?
Currently, I am done with letting each player go for three turns and choosing whether they want to re-roll or hold their dice. Also, I have completed all functions to calculate the scores for each of the 13 scoring possibilities. Next up is:
- showing the "possible" scorecard after each player's turn (linking functions to a main function)
- refresh myself on dictionary methods
- updating the scorecard 
- "announcing" the winner after the game has finished 
-  learn how to use Tkinter (I might use this for the scorecard)
