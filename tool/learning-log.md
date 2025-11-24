# Tool Learning Log

## Tool: **GDevelop**

## Project: **Create a 2d game where the player makes choices and those choices impact what they encounter.**

---
(When I was trying godot)
### 10/5/25 Used [Youtube tutorial to explore 2d](https://www.youtube.com/playlist?list=PLfcCiyd_V9GH8M9xd_QKlyU8jryGcy3Xa)

* You can create a 2d "node" or a 3d "node" by selecting them at the left hand side of the screen.
* You can create a child node by right clicking on the main "node" or clicking the plus sign on the top left. This creates the entity, sprite, camera and many more.
    * When creating a character for example It needs a collsion and that collsion needs a shape.
    * to create that shape on the inspector on the right side of the screen click on the child "node" collsion and click empty option next to shape so you can select any shape available to you.
* You can also click the eye ball so that "node" would be invisible or visible.
![](../Images/visible.png)
* f5 runs the project.
* f6 runs the current scene.
* you could create a folder on the bottom left to store entities, sprite movements and etc. This is for organization.
* To create the sprite you need drag in the sprite sheets into the player file. You do that by right clicking on player folder open in file manager and then have another file explorer that has the sprite sheets and you drag it in. 
    * On godot you could see the sprite sheet and on the Sprite2D node you would drag it to the texture box on the right.
* Depending on how many horizontal sprites and vertical sprites frames you have, you type in the number in the animation tab under the inspector of the sprite node.
* If the sprite looks blurry on the project tab on the top right corner you go to the project settings and find textures so you can set the default filter to nearest.

Making a 2d game on godot looks not so beginner friendly but finding this step by step video on youtube makes it beginner friendly. I have so far created a sprite but haven't tried to make it move. Before I would go further into 2d, I want to explore the 3d verison of godot and potentally explore my back up tool gdevelop. 

### 11/23/25 Used [Youtube tutorial to explore the different options](https://www.youtube.com/watch?v=XxeD_2nTyHI&t=139s)
* When you want to create a sprite you click an plus button at the right side of your screen and you can put in animations, how they move and jump and some extra variables you want to apply.
* You can also add spritesheets so the sprite moves when the sprite moves or stands still.
![](../Images/Gdevelop1.png) 
At the moment this is just the animation of the sprite not moving.
* Out of this screen (I can edit in the movements when I learn them) there is a events tab at the top of the screen. 
    * This events works like those if condition I learned in javascript and java. 
![](../Images/GdevelopEvent.png)
* You can also add another condition like && in javascript and java. At the point there isn't anything I found that as the same action as ||.
* When you create a sprite that the player stands on, you specficly have to click on "Tiled Sprite" and add your sprite from there. 
* Then you would set the tiled sprite to whatever the grid is on the whole screen. On default, it's 32 by 32 but you could change it to 16 by 16 to make it more manageable.
* When you try to expand a tiled sprite at every grid it duplicates the sprite while a regular sprite just becomes bigger. 
<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
