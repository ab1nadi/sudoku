# Sudoku
Just a fun little website, that generates playable sodoku puzzles from easy to evil. The puzzles are generated utilizing a solver to createa puzzle with a unique solutions, then it digs holes in that solution based on the wanted difficulty . The algorithms I used for digging holes in the puzzle can be viewed here:  http://zhangroup.aporc.org/images/files/Paper_3485.pdf. 
The game is playable at: https://ab1nadi.github.io/sodoku/.

# Building the project
I didn't use any frameworks for this project but I did use the webpack bunder. So the index.html page just uses the dist.js that is generated by the bundler.
To bundle the javascript go the the project directory in commmand prompt and then run npx webpack.

* cd project/directory
* npx webpack

# Playing the game
   
 ## Movement
 Movement is as easy as using the mouse, the arrow keys, or using the 'a', 's', 'd', and 'w' keys.
 The square currently being worked on is highlighted.

 ## Note Mode
 Note mode allows you to make notes on square. You can enter note mode by either pressing 'e', pressing  the 'shift' button, or clicking the note mode
 button with the mouse.

 ## Clearing a Square 
 To clear the current highlighted square press the 'q' button or press the 'ctrl' button.


 ## Generating puzzles
 Generating puzzles is kind of self explanitory. Select the difficulty you want from the drop down, then click load. 


