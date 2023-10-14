# Game Development Project Based Learning

I wanted to prepare a list I collected from various websites for those who are bored of watching tutorials and want to do project-based learning but cannot find ideas. 

These game ideas are not dependent on a single game engine; they can be produced using any game engine. 

# 1 - Choose Your Adventure

![alt text](https://i.stack.imgur.com/dTn3V.png")

Based on choose your adventure books, it is basically a simple text adventure game, 
making such a game should teach you to make a gameloop, basic scripting (you can push it and add data structures/make it data-driven instead of hard-coding everything in the program). It is quite simple to implement and easy for a beginner.

#### Sample project:  [C# Console](https://www.youtube.com/watch?v=22Dft29ykKE)

# 2 - Guess the number / Hangman / Mastermind

![alt text](https://code-projects.org/wp-content/uploads/2019/11/Capture.png)

Basic interface, select data from a database, You can make a menu screen, add an end game screen and score.

#### Sample project:  [TypeScript](https://github.com/sajadhsm/mastermind)

# 3 - Tic-Tac-Toe / Rock-Paper-Scissors

![alt text](https://camo.githubusercontent.com/8a6da96b6a31ac6983ebf923ba6a1e3e741ad7b9417d1fd4d7540c7624a77fc2/68747470733a2f2f63616c65622d656c6c69732e6769746875622e696f2f6173736574732f696d672f746963746163746f652e6a7067)

Turn-based gameplay, simple opponent AI or second player.

#### Sample project:  [Godot Engine](https://www.youtube.com/watch?v=w6leMEr1aGo)

# 4 - Breakout / Arkanoid / Pong

![alt text](https://www.hiig.de/wp-content/uploads/2014/11/Pong1.jpg)

Easy game since you don't have much state to worry about, there isn't any AI, and you get to do a little bit of physics to get the ball to bounce correctly. No real needs for sounds. Also: input handling, collisions, stable frame rate, score, levels.

#### Sample project:  [Unity 3D](https://www.youtube.com/watch?v=AcpaYq0ihaM)

# 5 - Flappy Bird

![alt text](https://images.yourstory.com/cs/2/96eabe90392211eb93f18319e8c07a74/Imageg79l-1682602936960.jpg?w=1152&fm=auto&ar=2:1&mode=crop&crop=faces)

Making Flappy Bird is a great opportunity to understand the basic concepts of game programming. During the making of the game, you can learn about basic game programming concepts such as the game engine, graphics, sprite, sounds, and user input.

#### Sample project:  [Rust](https://github.com/deckarep/flappy-rust)

# 6 - Solitaire / Minesweeper

![alt text](https://minesweeper.online/img/homepage/expert.png)

The rules are a bit more complex than Breakout and the interface to it is a lot different. It forces you to think about different methods of implementing a game. i.e, what works in one game isn't necessarily what you would use in another. They're event based rather than "real time".

#### Sample project:  [Python](https://www.youtube.com/watch?v=OqbGRZx4xUc)

# 7 - Tetris

![alt text](https://i.ytimg.com/vi/uccXwNSGDNU/maxresdefault.jpg)

The art is colored rectangles, which even a total klutz can draw in Microsoft Paint. You don't need sound. The programming is relatively simple, but still requires a few key things.  Since it is a very common game, lots of open source clones out there to rip apart if you get stuck. Also: Data structures and how they relate to gaming.

#### Sample project:  [C++](https://javilop.com/gamedev/tetris-tutorial-in-c-platform-independent-focused-in-game-logic-for-beginners/)

# 8 - Asteroids

![alt text](https://images.saymedia-content.com/.image/t_share/MTc0MDE0OTk4MzEyMzk2NjY3/asteroids-by-atari-classic-video-games-reviewed.jpg)

Bullets, space physics, toroid world.

#### Sample project:  [Love2D](https://www.youtube.com/watch?v=z5YR_6D1UlM)

# 9 - 1942 / Space Invaders / Gradius / R-Type / Shoot-em-up

![alt text](https://image.api.playstation.com/vulcan/img/cfn/11307sf9lFZoqVYhEWlac3J01aGlm8vccamuZiOrnl25AeSURkC_X0VLxVkX--gqQU_ZA0AerExSNnzP6eTv4_qqNkcjT5Ao.jpg)

You can probably find some freeware tilesets to make this. Here the background is scrolling, you'll be using techniques  You also tend to have dynamic enemy and bullet spawns, so you'll need to learn to clean up after yourself (i.e. get rid of enemies and bullets that leave the screen).

#### Sample project:  [GameMaker Studio 2](https://www.youtube.com/playlist?list=PLjoLbN1uRJGx5FgCUhYjh5R4lj7gEUtPJ)

# 10 - Simple platformer / pinball game / Super Mario Bros

![alt text](https://raw.githubusercontent.com/ahmetcandiroglu/1G.Super-Mario-Bros/master/docs/Screenshots/In%20game%20screen.png)

The scrolling is under player control and not automatic. You also have to deal with gravity and all the fun collision stuff that goes along with it (like not falling through the floor just because you were a few pixels above in the last frame and want to move to a few pixels below in the next frame). Also note that gravity is conditional: it affects the player and some enemies, but typically not the platforms or floating coins or whatever, which is a bit different from the real world. For an extra challenge: add irregular sloped terrain and parallax.

#### Sample project:  [Java](https://github.com/ahmetcandiroglu/Super-Mario-Bros)

# 11 - Bomberman / Pac-Man / Nibbles / Snake

![alt text](https://img.redbull.com/images/c_limit,w_1500,h_1000,f_auto,q_auto/redbullcom/2013/12/03/1331622889292_3/pac-man-oyunu)

This one is nice because you get to work on a little bit of AI. Having the ghosts follow the player (but not too well - you want the player to have a chance) can be quickly implemented, and you will have a fun little game that you can tweak and show off to friends and family (positive feedback is always a good thing when you are starting out). Also: tile-based movement, complex enemy AI.

#### Sample project:  [Unity 3D](https://www.youtube.com/watch?v=TKt_VlMn_aA)

# 12 - Gauntlet / Zelda

![alt text](https://i0.wp.com/mynintendonews.com/wp-content/uploads/2015/04/lttp.jpg?resize=930%2C620&ssl=1)

Large map scrolling, interaction with the environment, enemy AI, inventory, health.

#### Sample project:  [Love2D](https://www.youtube.com/watch?app=desktop&v=SPAffu3ivIM)

# 13 - Two-player game

![alt text](https://images.crazygames.com/2-player-tag-cover?auto=format%2Ccompress&q=45&cs=strip&ch=DPR&w=1200&h=630&fit=crop)

Of any of the types above (two player inputs).

# Thank You 

 [What are good games to "earn your wings" with? [closed]
](https://gamedev.stackexchange.com/questions/854/what-are-good-games-to-earn-your-wings-with) 

 [7 Easy Games to Code for Beginners](https://www.create-learn.us/blog/easy-games-to-code/) 


# Contributing

Please refer to each project's style and contribution guidelines for submitting patches and additions. In general, we follow the "fork-and-pull" Git workflow.

    1. **Fork** the repo on GitHub
    2. **Clone** the project to your own machine
    3. **Commit** changes to your own branch
    4. **Push** your work back up to your fork
    5. Submit a **Pull request** so that we can review your changes
