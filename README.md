# Pacman Project

Recreating the Pacman arcade game using C++ and the S2D library in Visual Studio 2019.

![My Pacman Project](https://github.com/WedgeManWik/Pacman-Readme-Website/blob/main/PacmanImg1.PNG?raw=true)

This is the first C++ project I've ever created - so I'm pretty happy with how it went. I tried recreating the fundamentals of the Pacman video game, whilst also trying to add some original aesthetics.

## Game Description 

### Playing the game

#### Some basic rules

You spawn in a maze as Pacman, the goal is to get the highest score you can. You have three lives and can move around the maze using some basic controls; however, there are four scary ghosts trying to kill you! To get points the player may eat pellets, cherries and even ghosts.
After the game ends, the player's score is saved as the new highscore if it's higher than the highscore.

#### The Ghosts

There are four ghosts: Red, Pink, Orange and Blue. They move around the maze using some basic AI and will kill Pacman if they get too close - however, Pacman may eat a cherry and for a short period of time gain the ability to eat the ghosts! After a ghost is eaten, it will respawn in the centre of the map.

#### Player Info & Controls

The player can move around with WASD controls, if the player moves off of the edge on the right or left side of the screen, they will wrap around to the other side of the maze. When the player collides with a ghost, the player will explode and lose a life.

#### The scoring system

Pellets - 1 point each.

Cherries - 10 points each.

Ghosts - 10 points each.
 
