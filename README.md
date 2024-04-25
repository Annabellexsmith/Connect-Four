# Connect Four: A Web Based Game
Project completed during Software Engineering Bootcamp at General Assembly.
This version of Connect Four takes place in Seattle. The two players are designated to either sun or cloud tokens. Each player's goal is to place four tokens in a row before thir opponent. Based on who wins Seattle either gets an early spring or extended winter. This game was inspired by Seattle's unpredictable weather. 

Instructions:
<img src="https://i.imgur.com/DmjkMUG.png" alt="welcome screen with instructions">

Board display:
<img src="https://i.imgur.com/0t6nW1D.png" alt="view of board with tokens">

## Getting Started:
Grab a friend and play the game for yourself! You can find the game at:

https://annabellexsmith.github.io/Connect-Four/

This project was created based on requirements for the Browser-Based Game Project. Below you can find the wire frames used to guide the planning process.
<img src="https://i.imgur.com/whh10Gm.png" alt="wire frame of the welcome screen">
<img src="https://i.imgur.com/bhIwqwG.png" alt="wire frame of the playing board with tokens in slots">
<img src="https://i.imgur.com/GOp7VIP.png" alt="wire frame of modal when a player loses">

## Technologies Used: 
- JavaScript 
- HTML
- CSS

## Challenges Encountered During Development:
While coding, I encountered a malfunction where the program was not recognizing Player One's win. I met with the teacher's assitant and looked at individual functions but were unable to find the error. Later on I worked on the bug, noticing that it would recognize Player One's win if they obtained 5 tokens in a row. With this information, I was able to find the syntax error in my initialization function where it logged the first move as a string instead of a number. After revising that function the program was able to recognize Player One's win correctly. 

## Next Steps: 
- Create different options for difficulty levels. As the difficulty increases so will the amount of slots on the board.
- Create an option for player 2 to be a computer. 
