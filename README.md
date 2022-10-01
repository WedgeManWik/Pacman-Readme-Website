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
 
### My personal review

#### What went well? 
Managing to include all the features I wished was a big success; Easy controls with an easy-to-understand UI, Animations, A map with wall
collisions, a basic ghost AI, a win/loss mechanic, a high score, Good aesthetic as well as multiple sound effects. Implementing these was quite
the challenge at times, and required several bug fixes and tests but luckily, I was able to use my previous knowledge from coding in JavaScript
to conquer some of the hurdles.<br>

#### What didn’t go so well? 
The Pacman I created wasn’t as unique as I would have loved it to be; I put my own aesthetic twist in the mix by making the wall texture a Minecraft
grass block, and by making pacman explode when you die, however, I would have loved to mix it up a bit by switching up some of the game mechanics more.
For example, different enemies such as zombies or aliens, different collectable items like a speed boost or a random location teleporter, and maybe
even different game modes for the game.<br>

####What Would you do next time?
If I was to make Pacman again, I would definitely add a main menu, where you can create or log in to a new account, open up a high score table,
a customisation feature, different game modes, and a lot more. If I wanted to, I could create multiple game modes, and some could be multiplayer!
For example, a game mode where you and the other players spawn in the same map and whoever eats the most munchies wins, the cherries turn you into
a super ghost so you can eat other players as well as the normal ghosts for extra points, and the normal ghosts try and and kill the pacmen!<br>

#### One key area you felt you learnt a lot about?
I definitely learnt a lot about the map creation, how by using a .txt file you can create the level and just easily edit it by editing the .txt file.
Usually, I would’ve created a 2D array for the map, but in this case, I would’ve had to create a 21x21 array which is extremely big, and would’ve made
 things a lot more confusing. By learning from the Platformer frame work, as well as using the programmer tricks up my sleeve, I was able to create
 a pacman map from a .txt file.<br>

#### One key area you found difficult and want to learn more about?
There was no particular part of the project which I found extremely difficult, the conversion from a .txt file to create a map was something new to me,
but it didn’t take long to understand how it works. However, one thing that was a pain was that the arrays in C++ are static, unlike the dynamic ones
in JavaScript. This made things harder for me, as I find that the dynamic arrays are much easier to work with, and I’m just a lot more used to them.
Another thing, is that Pointers can be extremely confusing for me, I still don’t fully understand them – they’re unlike anything I’ve ever came across
in my programming career.<br>

