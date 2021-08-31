# Project 0: Dodge the Creeps

A tutorial implentation by Jacob Cecil

This project follows the [Your First Game Tutorial](https://docs.godotengine.org/en/stable/getting_started/step_by_step/your_first_game.html) for the Godot game engine. 

## Project Report
This project was my one of my first ventures into game programming. 
Armed with knowledge gained from an in-class tutorial via CS315 led by Dr. Gestwicki on a similar project, I was able to easily follow along with this tutorial. 
I was amused by the fact that the tutorial explained how to add in your own image for the background of the game, hence my puppy Mathias is there to greet the player. 
However, I did run into one error.
When a "creep" would colide with the "player", the game over screen would appear, the music would stop, but the score kept increasing, and creeps would keep spawning. 
Removing signals related to "hit" and "body_entered(body:Node)" and re-connecting them to their respective methods appears to have fixed this issue. 
With all my previous programming projects, simply staring at, and editing code was enough to fix most problems. 
Going forward with game programming, I feel that I'll have to come up other, more creative solutions. 

I believe I have met every requirement, as indicated below. 
- [x] D-1: The repository link is submitted before the project deadline.
- [x] C-1: The tutorial has been completed.
- [x] B-1: Your <code>.gitignore</code> file is correctly specified in the repository.
- [x] A-1: The project report is complete as per the instructions.


### Third-Party Assets 

art/House In a Forest Loop.ogg Copyright © 2012 HorrorPen, CC-BY 3.0: Attribution. Source: https://opengameart.org/content/loop-house-in-a-forest

Images are from "Abstract Platformer". Created in 2016 by kenney.nl, CC0 1.0 Universal. Source: https://www.kenney.nl/assets/abstract-platformer

Font is "Xolonium". Copyright © 2011-2016 Severin Meyer sev.ch@web.de, with Reserved Font Name Xolonium, SIL open font license version 1.1. Details are in fonts/LICENSE.txt.