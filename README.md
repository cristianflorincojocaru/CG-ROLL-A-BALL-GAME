# Computer Graphics - ROLL-A-BALL GAME


### DESCRIPTION :
**"Roll-A-Ball"** is a **simple game** developed using **Unity**, where the player controls a ball that must collect objects in a **3D environment**. The goal of the game is to gather all the objects on the map in the **shortest time possible**, while **avoiding obstacles** and **interacting with various mechanics**.


## TECHNOLOGIES USED
The **main technologies** used for this project / game are :

**UNITY** - The game engine used to develop the game.

**C#** - The **programming** language used for scripting and game logic.



## GAME CONTROLS

|          **ACTION**        	        |  **BUTTON** |                **DESCRIPTION**          	|
|:------------------------------:     |:---------:	|:-----------------------------------:	    |
|           **JUMP**                  |  **SPACE BAR**  |    help the **player** get out of trouble by jumping    |
|         **HORIZONTAL (+)**        	|    **d**   	| move the **player** - to the right |
|         **HORIZONTAL (-)**        	|    **a**   	|  move the **player** - to the left	|
|         **VERTICAL (+)**          	|    **w**   	|    move the **player** - forward  	|
|         **VERTICAL (-)**  	        |    **s**    |     move the **player** - back    	|



## GAME FEATURES
Throughout the tutorial, we've developed quite a few **game features**, such as :
- **Player movement :** The player moves using the **W - A - S - D keys**, allowing movement in any direction without special actions like jumping or flying.

- **Enemy movement :** The **enemy chases the player** based on **specific patterns**, attempting to stop the player from collecting all the pick-ups or interfering with their progress.

- **Pick-ups :** These represent the **main objective of the game**, with the player needing to collect **all 12** before the **timer runs out to WIN**.

- **Scoring system :** Tracks how many pick-ups the player has collected and displays a message indicating whether the player **wins or loses** based on their performance.

- **Dynamic obstacles :** These obstacles shift positions on the map, adding difficulty for both the player and the enemy while collecting items.


In addition to the features mentioned earlier, which were implemented based on the tutorial, I personally added **new functionalities** to leave **my mark** on this project. These include :
- **Timer :** The timer is set at **1 minute and 30 seconds**, and if it runs out or if the player is caught by the enemy, it's a **GAME OVER**.

- **Jump ability :** The jump ability allows the player to overcome obstacles and collect pick-ups from high places or evade the enemy.
  
- **Pills :** Pills temporarily make the **enemy disappear for 5 seconds**, but they do not count toward the player's score.
  
- **Restart button :** The **restart button** allows the player to **restart the game** after a **win or loss** without needing to close and reopen it.
  
- **Pause button :** The **pause button** lets the player **pause the game** at any time to avoid **losing progress** if they need to step away.



## KEY FILES FOR THE PROJECT
In this project, **several files** were required to make the game run properly.

The first one, ***"CameraController.cs"***, is the file that helps the camera follow the player across the map. 
The second, ***"Rotator.cs"***, helps the pick-ups, of any kind, rotate in the air like "prizes".

***"PlayerController.cs"*** is the file that handles several things, from helping the player move around the map to enabling jumping, making the enemy disappear, and working in parallel with the files that manage the pause and restart button functionalities.
***"EnemyMovement.cs"*** is the file that 'teaches' the enemy to follow the player and prevent them from winning.

***"GameController.cs"*** is the file that handles the restart button, which works based on win or lose conditions, making it a crucial part of the project. ***"PauseMenu.cs"***, as the name suggests, helps make the pause button function properly.


> [!CAUTION]
> Being a **simple** project, there are no **'unimportant'** files.
> 
> All files in the project are considered **important**, and deleting any file will lead to **permanent damage** to the game.


## TESTING METHODS
If you simply want to play the game and test the final project, you can download the archive from the **'GAMEBUILD'** folder. Once you extract the files from the initial archive, you can easily access the executable file **"Roll-a-Ball Game.exe"** and play indefinitely. 

- **Minimum requirements** – **40 MB** of free space for download.

If you'd like to see the process behind the scenes, you're invited to download the **3 archives** from the **'PROGRAM FILES'** folder, which contain the original files behind the creation of the project. With these, you can make modifications to the project I have already completed, as you wish.


## CONTRIBUTIONS 
Project created by **Cristian Florin Cojocaru** (**CSE.2** - **University of Craiova / Faculty of Automatics, Computer Science and Electronics**). Contributions are welcome ! If you have suggestions for improving the code or documentation, please submit a pull request.


## LICENSE
This project is licensed under the [MIT License](LICENSE).

