# 2048-Game
- This is my version of 2048 Game originally developed by Gabriele Cirulli. I have made this game as a Application based problem of Ather Energy coding challenge.</br>
- I have used vanilla JavaScript, HTML and CSS (no canvas) with the help of VSCode to make this game.</br>
- The game has a 4×4 grid and starts with two numbers either 2 or 4 generated at random place.</br>

</br>
## Working</br>
- User can control using input 1,2,3,4 for left, right, up and down movements respectively.</br>
- Each time you slide, a new tile will randomly appear in an empty spot on the board. Tiles slide as far as possible in the chosen direction until they are stopped by either another tile or the edge of the grid.</br>
- If two tiles of the same number collide while moving, they will merge into a tile with the total value of the two tiles that collided. The resulting tile cannot merge with another tile again in the same move.</br>

- If user gets to 2048 in one of the tiles a 'You WIN' message gets displayed.</br>
- If all the tiles get filled up i.e. no zeroes left in any tile then a 'You LOSE, Hit refresh to Play Again' message get Displayed.</br>
- I have also added console.log commands to see the step by step output in console.</br>
- User have to click refresh to restart the game.</br>
- I have added little comments with each function for what they are performing.</br>
## I have used following JavaScript Methods:</br>
* querySelector()</br>
* getElementById()</br>
* createElement()</br>
* appendChild()</br>
* push()</br>
* Math.floor()</br>
* Math.random()</br>
* length</br>
* innerHTML</br>
* parseInt()</br>
* filter()</br>
* Array()</br>
* fill()</br>
* concat()</br>
* keyCode</br>
* addEventListener()</br>
* removeEventListener()</br>
* setTimeout()</br>
* clearInterval()</br>
* setInterval()</br>
</br>

I got little with struck with random numbers in creating random numbers only either 2 or 4. I take help from stack overflow to get over it.</br>
** Game Link: https://abhishek-pratap.github.io/2048--Game/index.html **</br>


