[Back to Modding Tutorials](https://sillleah.github.io/modding.html)

So you'd like to mod Night of 100 Frights, eh?  
Well, you can, and I'm here to help!

As with any game, the first step before we can start modding the game is to have the game files, extracted and ready for modification, as well as a way to edit them.  
This tutorial will walk you through extracting the game files and setting up a basic, tidy modding environment.

## The ISO

First things first, you will need a Scooby-Doo: Night of 100 Frights Gamecube ISO. It is not legal to distribute ISO files over the internet, so I cannot provide you with an ISO or information on where to find one.

## Setting Up Dolphin
*If you already have Dolphin installed and Night of 100 Frights in your game list, you can skip this section.*

Dolphin Emulator is the easiest way to extract the game files from the ISO. You likely already have it, since it's also the easiest way to test and play your game and mods, but you can download it [here](https://dolphin-emu.org/download/?ref=btn) if not.

Open up Dolphin Emulator. If this is your first time opening the emulator, you won't have a games directory set and Dolphin will prompt you to set one, as shown below.

![The main Dolphin interface](/assets/dolphin-games.png)

Double-click and set your games directory to whatever you like, and then place your ISO in this directory and hit Refresh in the top-left of Dolphin.  
If you already have a games directory set and want to change it or add another, go to Config at the top of Dolphin, then Paths, and then hit Add and select a directory.

Now you should see Scooby-Doo: Night of 100 Frights as a playable game on Dolphin's game list.

![Scooby in the Dolphin games list](/assets/dolphin-banner.png)

## Extracting Game Files

Now we need to extract the game files from the Night of 100 Frights ISO.

Right-click on Scooby-Doo: Night of 100 Frights in Dolphin's game list and select Properties.

Under the Filesystem tab, right-click on the disc itself and select "Extract Entire Disc", as shown.

![Extracting entire disc](/assets/extract-disc.png)

You'll be prompted to choose a directory to place the extracted files in.  
I recommend creating a fresh new folder to use as a modding workspace, and then creating a subfolder inside for the extracted files.

For the purposes of these tutorials, I'll be creating a workspace folder called "Tutorial", and inside, another folder called "Extracted Files", which is the folder I'll select here.

If you check the folder you selected, you should see two subfolders inside - 'files' and 'sys'.

And you're done - at least for now! We've extracted the game files.

Next I recommend moving on to the [Filesystem](https://sillleah.github.io/modding/filesystem.html) tutorial, which will explain the game's file structure so you can understand which files we'll be editing.
