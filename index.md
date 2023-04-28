Candy Land Platformer
=====================
![platformer screenshot](https://user-images.githubusercontent.com/114741234/231753262-28fbd598-ebcb-4fa4-8854-465b4af02807.png)
Game Features
----------------
 *  movement with gravity and friction
 *  no friction on ice
 *  if you touch the purple blob enemies, you lose health
 *  gain health by touching the pink hearts, but you cannot touch the same heart two times in a row
 *  if you have more than 0 hralth left at the end of the game, you win

Game Preview Video
------------------
video

Special Features and Code
-------------------------
 *  this code makes the player not teleport up or through walls

~~~python
if self.is_touching_any_sprite_with_tag('ldtk_ground'):      
  if self.x_speed >= 0:
    while self.is_touching_any_sprite_with_tag('ldtk_ground'):
      self.x -= 1
  else:
    while self.is_touching_any_sprite_with_tag('ldtk_ground'):
       self.x += 1 
       self.x_speed = 0
~~~

Tools That I Used
 *  [ldtk](https://ldtk.io/)
 *  [vscode](https://code.visualstudio.com/)
 *  [pycat](https://bitbucket.org/dwhite0/pycat.git)
 *  [Kenney assets](https://www.kenney.nl/assets)

Lunar Lander
============
[click here to play](/eloise_lunar_lander_wedgl_v1/index.html)
