# SeaBattle

Sea Battle works a lot like a traditional game from the time of the Soviet slot machines, where the player shoots enemy boats by torpedoes.
The game has following features:
-	The player can turn a sight left and right.
-	The player has only 6 torpedoes/shots per game.
-	Each torpedo needs 3 seconds for loading
-	Play time is only 1 minute.
-	Boats appear from left and right sides and have random speed. Added explosion of damaged boat.
-   Damaged boat explodes.
-	On the center of screen there are island behind which boat is defended.

Goal of the game
-----------------------
- Easy mode - within one minute, a player with 6 torpedoes must sunk 3 enemy boats.
- Medium mode - within one minute, a player with 6 torpedoes must sunk 4 enemy boats.
- Hard mode - within one minute, a player with 6 torpedoes must sunk 5 enemy boats.

The game keeps track of and displays number of sunk boats and the time remaining until the end of the game.

The game ends when win score is reached or the last torpedo is used or time is over. At that point, the game displays a message if player won or defeat. When the player chooses to close the message, the game returns to the main menu.
If a player clicks the play button on the main menu, the game lets them select a difficulty level (Easy, Medium, or Hard), then starts a game at the selected difficulty level.

The game has the following menus:
-------------------------------------
- Main Menu: Lets a player pick play, help, or quit
- Difficulty Menu: Lets a player pick Easy, Medium, or Hard for the game
- Help Menu: A single page that displays brief game instructions
- Pause Menu: A menu displayed if a player pauses a game in progress. Provides options to resume the game or quit to the main menu

The game stores important game configuration information in a file it reads in at runtime. This approach supports tuning patches later as necessary. WebGL builds don’t seem to read from the csv file even though it’s included in the build.

During gameplay, sound effects are used to indicate when a torpedo is loading, when it has been spawned and when a torpedo has collided with the boat. Finally, appropriate sounds are played when a torpedo is lost and the game is lost or won. The only menu sound effect is a click when a menu button is clicked.

Some screens of game:
------------------------------

<img src="https://github.com/aTasja/SeaBattle/blob/master/Start.png"  height="500" width="900">
