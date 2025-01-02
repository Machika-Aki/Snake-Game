# Snake-Game
This is a Snake Game that I made! Still needs some work though... especially with the restart button.
I can't seem to get the button to populate after the player dies.
The area where the player is supposed to click is there. Just not the visuals for said button.


UPDATE: I changed it to where you can press any button to restart the game. I also figured out that game loop wasn't rendering the game over screen correctly when the game would end. When the game over condition was met, the game state transitioned to game over, and then the loop would continue without displaying the final score and instructions correctly.
