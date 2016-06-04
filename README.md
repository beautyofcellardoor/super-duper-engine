# super-duper-engine
Repository for GUI CST 238

**Project Logo:** This is a goat picture I found on the internet.

![logo](http://www.how-to-draw-funny-cartoons.com/image-files/how-to-draw-a-goat-8.gif)

**Description:** I am going to make a match-three, Bejeweled clone game but instead of using jewels, I will be using animals for the objects the player is trying to match. Same as Bejeweled I am going to try to do an 8x8-grid space for the game. On the side, I will have a score, a timer, and a button to go back to the menu. The game will play like any other match-three game, and depending on how much time I have, I may also implement a hint button and an end game if there are no more possible moves. If I still have more time after that, I can add different game modes like puzzles, a timed mode, and having to get a target amount of points in under a certain amount of moves. 

**Technologies:** Qt, QML

**Screenshots:** Here are a couple screenshots from my game.

  ![menu](https://github.com/beautyofcellardoor/super-duper-engine/blob/master/Pictures/menu.jpg)

Here is the menu

![game](https://github.com/beautyofcellardoor/super-duper-engine/blob/master/Pictures/play.jpg)

And here is my game board

**Installation:**
+	Install Qt 5.6
+	Open the project
+ Clean all, run qmake, build all, run

**Contribution Guidelines:** If someone wanted to add something to this project it could be any of the before mentioned things that I said I would add if there was time.

I don’t have a standard set up yet but I think I will be using camelcase for naming variables.

**Bugs:** 
+ The timer starts when you enter the game, not when you go into the play section.
+ When the game board generates sometimes there's already a group of three.
+ I started to implement drag logic, but it doesn't work and is currently not doing what I want.

**To-Do List:**
x Make menu
x Set up a timer, the button to go back to the menu, and an outline for play grid
x Create a basic version of what the game will look like
x Include a place for points on the side and the points meter
+ Get the animal icons in place, be able to select them, and swap them
+ Implement game logic
  + Swap logic
  + Match logic
  + More tiles falling in
  + Matching 4 and creating a sparkly one
+ *Possibly include a hint button and a way to indicate when there’s no more moves
+ *Possibly include other game modes

**Contributor List:** I will be the only person working on this project.

**Inspiration:** My inspiration for creating this game was Bejeweled 2.

**License:** MIT
