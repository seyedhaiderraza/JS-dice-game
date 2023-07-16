# JS-dice-game
1. # Project summary
----------------

This is a Javascript only Project using HTML5/CSS3 to show a Dice Game app consisting of - 
new game
rolling the dice,
current player turn score handling, 
player turn change on dice random vlaue 1
player score add up on turn change

2. # Project URL
----------------

https://js-dice-game-three.vercel.app/

4. # Technology Stack used
-----------------
HTML5/CSS3
JavaScript: 📜 
  - DOM Manipulation,
  - EventListeners and handling
vercel deployment

5. # Functional Requirements/Acceptance Criteria
-----------------
#### new game
GIVEN: dice game page loads
WHEN: user press new game
THEN: roll button enables
AND: one player enabled

### rolling the dice
GIVEN: new dice game starts
WHEN: roll button pressed
THEN: dice value added to current score of current player


### current player turn score handling
GIVEN: roll button pressed
WHEN: dice shows any number except 1
THEN: score gets added to current


### player turn change on dice random value 1 with current score lost
GIVEN: roll button pressed
WHEN: dice shows  1
THEN: current score gets lost
AND : player turn changes



### player turn change on hold press current score not  lost
GIVEN: player turn going
WHEN: player presses hold
THEN: current score adds to total score
AND: current score turns 0 with player turn change



6. # Test Data(if any)
-----------------
N/A

7. # Screens
------------------
### Before New Game
![image](https://github.com/seyedhaiderraza/JS-dice-game/assets/129282622/53a0975f-39b1-48fe-a237-461f2413a32d)

### After New Game Click
![image](https://github.com/seyedhaiderraza/JS-dice-game/assets/129282622/cb927734-87d1-4cd5-9c4c-2a9b96c37f27)

### Player current score
![image](https://github.com/seyedhaiderraza/JS-dice-game/assets/129282622/42d5ac02-415d-44b4-9504-3fcc9ee6209a)

### Player turn change
![image](https://github.com/seyedhaiderraza/JS-dice-game/assets/129282622/1f125b0e-6a71-4c67-9bb4-d6f015135b7f)












