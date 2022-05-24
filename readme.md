TA

Create a constructor() in game.js to declare properties for resetTitle and
resetButton.

-------------------
In the handleElement() method of game.js we will write
code to display the button and text.


Create handleElements() to give position and text / image to resetTitle and reset
Button in game.js.


Create elements for leaderboardTitle,leader1 & leader2.

Assign position and text to leaderboardTitle, leader1 and leader2.

 we need to create a few more properties
for Player class. We need properties to store rank and
score.
If you notice in Player.js, inside constructor(), two more
properties are added and assigned them to 0.


we have to make sure we update these
properties in the database using addPlayer() function and
update() function.
UpdaddPlayer() is modified:


Instead of using a for-in loop to traverse through
allPlayers, we will learn another method, the
Object.values(). This method returns an array of a given
object's own enumerable property values, in the same
order as that provided by a for-in loop.
Create showLeaderboard() to display Player’s rank, name & score.

Call this.showLeaderboard() inside the play() method.


****************************************************************************
SA

handleResetButton() in game.js.
----
Call the function handleResetButton() inside play()

---
handeplayerControls() in game.js add these
controls.
To move left we will use the keyIsDown() function and it
will look for the LEFT_ARROW pressed by the user.
We will add the condition using the and operator that
player x position can be given greater than width/3 -50.
(Guide the student to check using console.log and
change accordingly.)
This means if the user goes to the end of the track in the
left direction, it will not move any further.
Similar things we will implement for the right side also
---
update the player’s position in the database using the
player.update() method.
