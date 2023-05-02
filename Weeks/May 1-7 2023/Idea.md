# Minesweeper in Roblox

## Description
For my first week, I'll be making a Minesweeper clone in Roblox, a platform and game engine I've gotten used to developing on ever since I started learning to code on February 20th, 2021. The idea is to create a basic functioning minesweeper board which exists in 3D space, and the player will interact with it by walking or jumping on cells. The game will be multiplayer, since it's trivial to set up in Roblox.

### Completion Criteria
- must be able to generate a random minesweeper board
- must be able to customize the size and mine density of the board
- each grid cell must indicate how many mines it has next to it
- player must either start on a non-mine cell or have the ability to choose any cell to start on
- must be able to flag cells
- after choosing a grid cell:
    - if it was a mine, the player dies and the game is lost
    - if it was a mine and it was flagged, do nothing
    - if it was not a mine, reveal it
        - if it had no mines next to it, reveal all cells next to it
    - if it was not a mine and it was flagged, do nothing
- must be able to win the game once all safe cells are revealed
- must be able to play multiplayer

### Stretch Goals
- seconds counter
- mine counter displaying how many mines remain
- chord by jumping on a safe cell
- board animations
    - mines blowing up
    - cells celebrating after winning
    - chord shockwave
    - cell reveal
- sounds on various events
- mobile support
