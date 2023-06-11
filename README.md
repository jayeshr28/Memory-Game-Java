# Memory-Game using SWING

Description –
1.	 Game Setup:
•	The game has a local resource folder that consists of 20 different code snippets, each with its corresponding output.
•	At the start of each game, the program randomly selects six code snippets from those.
2.	User Interface:
•	The graphical user interface presents the code snippets to the player in a grid-like layout, with each snippet displayed on a JButton.
•	The cards are initially face-down, hiding the code snippets and their outputs.
3.	Gameplay:
•	The player's objective is to match each code snippet with its corresponding output.
•	The player can flip two cards that is one question and one answer at a time by clicking on them. When a card is flipped, the code snippet is revealed.
•	If the player successfully matches a code snippet with its output, both cards remain face-up.
•	If the player fails to make a match, the cards flip back face-down, and the player can try again.
•	The player can continue flipping cards until all the matches are made.
4.	Timer:
•	The game includes a timer that starts when the player clicks the "Start" button.
•	The timer gives the player a time limit of 2 minutes to complete the game.
•	If the player fails to match all the code snippets within the given time, the game ends.
5.	Winning Condition:
•	The player wins the game if they successfully match all six code snippets with their corresponding outputs within the time limit.
•	A victory message is displayed to congratulate the player on completing the game successfully.
 
 
 Compilation and Running – 
-	Open the java file (MemoryGame.java) given in the zip file
-	In the given code there are two times where we need to specify path for the photos folder, so edit it according to your folder’s path.
-	If you are using VS code, then just save the code and click on the run button 
-	If you want to run the code with cmd/Terminal then write below commands in terminal – 
o	cd (the folder where your java file is located)
o	javac MemoryGame.java
o	java MemoryGame 
-	The Swing application will get started and you can make it full screen for having clear visuals of the code. Start the timer and Enjoy the game!!
