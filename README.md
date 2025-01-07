# CatAndMouseGame
An example using Hill Climbing to develop optimal policies for both players in the cat and mouse game. 

In this game, we have two players, the cat and mouse, placed on an n x m grid, similar to a chess board, but where it is possible to have any number of rows and any number of columns. Either the cat or mouse may move first, and they then take turns until there is a winner. At each step, they must move either left, right, up, or down; they cannot remain in the same cell, and cannot move diagonally. So, they generally have four possible moves, though if at an edge will have only three, and if in a corner, only two. 

The cat wins if it's able to capture the mouse, which is achieved by moving to the same cell the mouse is on. The mouse wins by evading capture for sufficiently long.

This provides a set of notebooks that are described in the Medium article, Using optimization to solve adversarial problems.

## Notebooks

**Version_1** provides a solution that trains both the cat and mouse. This assumes a known, fixed, and reasonably small board size. It develops a policy for each player based on the location of the cat and location of the mouse on the board.

**Version 2** provides a more general solution, which can handle any board size. However, for simplicity this trains only the cat, and only for situtations where the cat and mouse are close to each other on the board (including where the cat may be close to cornering the mouse). 


