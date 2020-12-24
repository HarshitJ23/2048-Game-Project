# 2048-Game-Project
The game's objective is to slide numbered tiles on a grid to combine them to create a tile with the number 2048. 

We have 3 functions which will comprise the whole 2048 game which are:- 1) Logics Part, 2) Constants, 3) UI part. 

Create a matrix with 0*4 rows.

Function is created to add new 2 randomly.

Left , right , up and down movements will add up accordingly and the game will not get finished until we have reached 2048.

In the Constant function, I declared what box to be given what color. And what will be the Color of the background of particular tile, board and even numbers. The numbers are also given different numbers, and then we can have different FONT specifically.

We will move up, down,right, left with "wasd" keys.

In the UI part, we have imported tkinter (it's a GUI library) which is basically used for importing Frame, Label and Center and provides fast and easy way to create GUI Applications.

And in this function we will bind the wasd keys with their specific functions.

And for making it a user friendly game , I have added texts like You won when we reach 2048 and You lose when all the boxes are filled and we have no chance of combining 2 tiles further.
