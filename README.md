# WebGL Puzzle Game

## Purpose
For the class CS328 (Fundamentals of Game Design) we were prompted to make a game using Unity and building to WebGL.

## Story of Game
A knight and fairy are trapped in a dungeon and they must work together to escape. Swap between the knight and the fairy to pull levers, move objects, and more to solve each of the four rooms.

## Build Version
This is version 0.4

There are still currently issues that will be fixed before the final version to be presented in class. Current bugs include but are not limited to:
- Lighting works in Unity and Desktop builds, but not WebGL
- Movement glitches of the knight
- Being able to 'lose' the box in room 1 by throwing it outside of the scene
- Room 2 is close to impossible to solve due to placements of spikes and poor design of the room
- Room 4 is not properly scaled

--- THE FINAL VERSION OF THIS GAME WAS UPLOADED TO A DIFFERENT SITE FOR EASE OF USE DURING THE CLASS DEMO. THIS REPOSITORY WILL NOT HOLD THE FINAL GAME ---

## Controls
### Knight
```
Left Arrow - move left
Right Arrow - move right
Up/Down Arrows - move up and down the ladder in room 2
e - pick up/drop boxes, switch levers
```
### Fairy
```
Left Arrow - move left
Right Arrow - move right
Up Arrow - move up
Down Arrow - move down
```
### Other
```
Space - swap between characters
```

## Character Abilities
The knight can:
- Pick up heavy objects
- Push heavy objects by running into them
- Switch levers
- Stand on pressure plates

The knight can't:
- Jump
- Move through tight/small spaces

The Fairy can:
- Move through tight/small spaces
- Fly
- Push small buttons
- Cut ropes on certain rooms

The fairy can't:
- Move objects
- Use pressure plates
