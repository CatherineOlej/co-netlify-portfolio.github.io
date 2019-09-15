---
layout: post
title: Check out My Game
author: catherine_olejarczyk
date: '2019-09-15 16:39:48'
intro_paragraph: |-
  # Bye Bye Birdy

  This game was created in Visual Studio using MonoGame
categories: MonoGame
---
The game created is named, “Bye Bye Birdy.” It demonstrates collision and player movement with gravity. This game features a spritesheet package of the plane, bullets, and background. Each is image is an individual png file that was used in an array to generate the plane animation. Another spritesheet added is the one of the birds.

However, this one came as a single image including the birds flying movement; the sections were cropped out and inserted into an array to make the animation for the birds to fly. The background appears on every scene of the game. To add a more appealing interface, the scrolling method was added to the background, as well as changing the font color and size. The spritesheets and music was downloaded from the OpenGameArt site. I also used the “AllInOne” project the teacher provided for the class to use for the menu component of the game. 

The purpose of the game is to shoot as many birds possible flying in the direction of the plane, while a score in the corner tracks each kill. The game ends once the player and the bird have collided, or the player has either fallen out of the screen or touched the edge. Music is added to the game for more effect. A background track plays while the game starts and there is shooting effect sounds added when the player shoots. When the game is over, an error like sound will take in effect when the player fails.

![](/assets/img/uploads/mainpage.png)

![](/assets/img/uploads/help.png)

![](/assets/img/uploads/howtoplay.png)

![](/assets/img/uploads/game.png)

![](/assets/img/uploads/gameclassdiagram.png)

**Resources form OpenGameArt:**

* Plane spritebatch: https://opengameart.org/content/free-plane-sprite
* 	(the bullets come with this spritesheet)
* Bird spritebatch: https://opengameart.org/content/animated-birds-32x32
* Game Over sound: https://opengameart.org/content/bad-sound-1
* Background Music: https://opengameart.org/content/battle-in-the-winter
* Shooting sound: https://opengameart.org/content/8-bit-platformer-sfx
