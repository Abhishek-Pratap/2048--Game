# 2048-Game
This is my version of 2048 Game originally developed by Gabriele Cirulli. I have made this game as a Application based problem of Ather Energy coding challenge.
I have used vanilla JavaScript, HTML and CSS (no canvas) with the help of VSCode to make this game.
The game has a 4×4 grid and starts with two numbers either 2 or 4 generated at random place.
User can control using input 1,2,3,4 for left, right, up and down movements respectively.
I have also added console.log commands to see the step by step output in console.

Each time you slide, a new tile will randomly appear in an empty spot on the board. Tiles slide as far as possible in the chosen direction until they are stopped by either another tile or the edge of the grid.
If two tiles of the same number collide while moving, they will merge into a tile with the total value of the two tiles that collided. The resulting tile cannot merge with another tile again in the same move. 

If user gets to 2048 in one of the tiles a 'You WIN' message gets displayed.
If all the tiles get filled up i.e. no zeroes left in any tile then a 'You LOSE, Hit refresh to Play Again' message get Displayed.
User have to click refresh to restart the game.
I have added little comments with each function for what they are performing.
I have used following JavaScript Methods:
querySelector()
getElementById()
createElement()
appendChild()
push()
Math.floor()
Math.random()
length
innerHTML
parseInt()
filter()
Array()
fill()
concat()
keyCode
addEventListener()
removeEventListener()
setTimeout()
clearInterval()
setInterval()

I got little with struck with random numbers in creating random numbers only either 2 or 4. I take help from stack overflow to get over it.
I have hosted the game in About section.
Game Link: https://abhishek-pratap.github.io/2048--Game/index.html


