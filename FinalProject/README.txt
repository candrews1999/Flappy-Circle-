I included a singular html file in my final project. 

In the head of the HTML, I included links to D3 library and to a special Google Font called Jockey One.

Then I created an embeded style sheet whih set the font for the project and dealt with aesthetic issues such as padding or font heirarchy. I styled my buttons also and gave them a color change animation on hover.

In my body, I built the heading part of the project, including the title of the game, the restart button and an optional ability to enter a player name into a text box and submit that name to the highscrore board.

In the script, I then began by setting variables for my game such as the begining score or gameOver being false. I also used setInterval to create a timer for my game animation to run on. I then seperated my code by model data which would be responsible for changing the data of the game such as the birds height as time ticked on. I also kept counters so that some changes to the data didn't happen with every tick but were spread out im. This was done with the falling of thd circle because if it fell with every tick the circle would fall way too fast and the game would not feel like flappy bird. Lastly, I coded the view code which handles the actual graphics for the game and draws each of the pipes and circle at their current positions. If the game has ended (which is tested for in the model data code), I instead draw the score board with all the previous scores and player names in the current game session.

