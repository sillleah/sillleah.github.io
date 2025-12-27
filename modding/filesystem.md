[Back to Modding Tutorials](https://sillleah.github.io/modding.html)

In this tutorial, we'll cover the Night of 100 Frights filesystem and which files you'll be getting familiar with to mod the game.

If you followed the [Extracting Game Files](https://sillleah.github.io/modding/extracting-the-game.html) tutorial, you should have a set of extracted game files, which we'll be delving into this tutorial.

## The 'files' folder

First let's jump into the 'files' folder.
This folder contains... well, almost all of the important game files for Night of 100 Frights.

![The files folder](/assets/filesystem.png)

### 'fmv' / Cutscenes

The 'fmv' folder contains all of the game's cutscenes. (For the unaware, Night of 100 Frights' cutscenes are prerendered videos on Gamecube and Xbox.)  
You'd be very unlikely to touch this folder during modding.

### Level Folders

All other folders in the 'files' folder other than 'fmv' are folders containing the game's .HIP level files.  
The level files are roughly grouped into these different folders - for instance, the 'B0' folder contains the four 'Who's Yella in the Cellar?' levels.  
It can be difficult to identify a level based purely on its .HIP filename, since the filenames are generic - for instance, 'Coast for Some Ghosts' Part 3 is internally named L014.HIP. As such, I've created a guide to internal level filenames available [here](https://sillleah.github.io/modding/level-names.html) for your use.

You'll get to know these well during modding - since naturally, a large part of modding is level editing. For those who aren't aware, almost all of Night of 100 Fright's scripts and events are within the levels themselves and not the game's code - so level editing gives a huge amount of control over the game compared to modding other games.

### boot.HIP

boot.HIP is a file you'll use inside Industrial Park, the level editor, alongside your actual level files - this contains a bunch of generic game objects and data that is needed in almost every level, such as Scooby's animations, invention models and particle effects.

### font.HIP

font.HIP contains font textures for the game.

### SD2GCBanner.tpl and SD2GCIcon.tpl

These files store the game's banner and icon images. If you want to change them for whatever reason, you can use a TPL image editor such as the one included in [CTools](https://horizon.miraheze.org/wiki/CTools#ImageTool_/_TPL_Editor).

### opening.bnr

This file is present in any Gamecube game and provides the banner and game data to the Gamecube BIOS - it doesn't have any effect ingame, but if you want to change it, I would look into a tool like [bnrtool](https://github.com/xchellx/bnrtool).

### sd2.ini

This is a configuration file that contains a few game settings you can alter, such as changing Scooby's speed values or bypassing the main menu. You can learn how to edit this file in the [INI File](https://sillleah.github.io/modding/ini-file.html) tutorial.

## The 'sys' folder

The 'sys' folder is a bit less interesting.

- main.dol - This is the game's main executable file, containing the code and some hardcoded data such as level names. Editing this file is difficult, as there is currently no ongoing decompilation project for this game, but it is possible with knowledge of decompilation tools like Ghidra.
- The other files in this folder contain fragments of the Gamecube BIOS and software, and are effectively useless for modding to my knowledge.


In simple terms, most of your Night of 100 Frights modding will involve the game's .HIP files, and potentially the main.dol - but knowing where everything in the game is stored is useful information to have. You should refer back to this tutorial anytime you need to.  

Now that you have an understanding of the file system, you should move on to the [Basics of Industrial Park](https://sillleah.github.io/modding/industrial-park.html) tutorial. Industrial Park is the .HIP editor for Night of 100 Frights (and any other games made by Heavy Iron Studios) and will allow you to actually start making changes to the game! 
