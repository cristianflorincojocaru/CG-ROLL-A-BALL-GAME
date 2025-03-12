# Computer Graphics - ROLL-A-BALL GAME


### DESCRIPTION :
**Roll-A-Ball** is a **simple game** developed using **Unity**, where the player controls a ball that must collect objects in a **3D environment**. The goal of the game is to gather all the objects on the map in the **shortest time possible**, while **avoiding obstacles** and **interacting with various mechanics**.


## TECHNOLOGIES USED
The **main technologies** used for this project / game are :

**UNITY** - The game engine used to develop the game.

**C#** - The **programming** language used for scripting and game logic.


## FEATURES
### 1. Player movement - **BALL**
> **EXPLANATION** : The player / **ball** can move in **any direction** by pressing the **W, A, S, D** keys on the **keyboard**, without any **special actions** like ***jumping*** or ***flying***.

### 2. Enemy movement - PARALLELEPIPED
> **EXPLANATION** : The **enemy**, created according to the code it follows, will **chase you across the map**, trying to **stop you** from collecting all the **pick-ups** or attempting to interfere with your progress so that you lose over time.

### 3. Object / PICK-UP collection
> **EXPLANATION** : These represent your **objective** in the game. You must collect all **12** of them *BEFORE* **time runs out** to **WIN** the game against the enemy.

### 4. TIMER 
> **EXPLANATION** : It represents the **time** you have to **COMPLETE** the game, normally **one minute and 30 seconds**. If the timer runs out and the player hasn’t collected all the pick-ups, it will be considered a **GAME OVER**.

### 5. Scoring system & player feedback
> **EXPLANATION** : It represents the **functionality that tracks** how many pick-ups you've collected up to that point. When you've collected them all, **you win**. If **you lose** for any reason—whether you **haven't collected all the pick-ups**, you've been **caught by the enemy**, or **time has run out** — you lose. For each outcome, **victory** or **defeat**, the player will receive a display message saying **'YOU WIN'** or **'YOU LOSE'**.

### 6. JUMP ability
> **EXPLANATION** : One of the game’s requirements, due to **obstacles of various shapes**, is that the player must jump in order to collect pick-ups from high places or to **escape from the enemy**.

### 7. PILLS collection
> **EXPLANATION** : These represent the **player’s SECRET weapon**. Similar to the normal pick-ups in nature, they cause the enemy to **disappear** for a period of **5 seconds**. To avoid interfering with the required pick-up score for victory, the pills **do not count ** toward the score, ensuring the final score remains **unaffected**.

### 8. DYNAMIC obstacles
> **EXPLANATION** : To make winning a bit more challenging, the map features **dynamic obstacles** that force the player to hit them in order to collect the pick-up. Once hit, these obstacles **change their position** on the map and can become **inconvenient** for both the player and the enemy.

### 9. RESTART button
> **EXPLANATION** : To make the game more **practical**, I have implemented a **restart button**. When the player wins or loses, they will have the option to restart the game and play again without having to close and reopen the game every time, if they want a longer gaming session.

### 10. PAUSE button
> **EXPLANATION** : This has been implemented to **assist the player in key moments**, allowing them to pause the game if they can’t continue for any reason, without closing the game and **losing their progress**.



