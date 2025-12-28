[Back to Modding Tutorials](https://sillleah.github.io/modding.html)

This tutorial will walk you through installing Industrial Park and its basic usage.

## Installing Industrial Park

Download the latest Industrial Park release [here](https://github.com/igorseabra4/IndustrialPark/releases).

Extract the .zip file to a location of your choosing and run IndustrialPark.exe to open Industrial Park.
If this is your first time using Industrial Park, you'll be presented with some popups pointing you to various tutorials. These are great to check out, but you can also simply skip over them and continue following this guide for now if you wish, since we'll cover all the basics.
You'll find yourself sitting at a basic, empty blue screen.

![Industrial Park on startup](/assets/industrial-park.png)

## Using Industrial Park

Let's go through some of the basics of using Industrial Park.

### Opening A Level

To open a level in Industrial Park, use the top bar and go to Archive Editor > Open Level. You'll be met with a slightly scary popup box. Click the 3 dots to the far right of "HIP file", as shown here.

![The open level dialog](/assets/open-level.png)

Select the HIP file of the level you want to open. For the purposes of this test, let's stay simple and open The Mystery Machine. Remember, you can find the filenames of levels using my handy guide [here](https://sillleah.github.io/modding/level-names.html). Mystery Machine's filename is H001, so navigate to your 'files' folder, then the H0 folder, then H001.HIP.  

After selecting your level HIP, Industrial Park should also automatically find your boot.HIP and fill it into the dialog box, leaving you with something like the picture shown.

![The open level dialog](/assets/open-level2.png)

Click 'Open Level' and Industrial Park will open up the selected level.  
A popup will appear asking you to specify the platform of your HIP file. Leave this as 'GameCube' and hit Confirm.  
You'll also likely get a popup about an error loading specific assets - this is completely normal when loading a level, since some animations are stored in other .HIP files and Industrial Park isn't always aware of this, so you can always just ignore these popups and hit OK.  
You'll have to repeat these steps again as Industrial Park loads the boot.HIP - but then a few extra windows should pop up and you should see your level appear inside of Industrial Park. We'll be ignoring these extra windows for now, and you can close them if you like.

(Side note for later - you can open multiple levels inside of Industrial Park at once. Just be aware that all of these levels will be active in the view window at once - likely overlapping with each other and making them difficult to work with. As such, I only really recommend this for copying over assets, which is something we'll learn about much later...)

### Viewing A Level

Now that your level has loaded into Industrial Park, let's go over the basics of taking a look around a level.

![Viewing a level](/assets/view-level.png)

First of all, you probably notice a large amount of colored boxes and spheres covering large parts of your level, and making it difficult to see much. These are mostly sound effect and camera triggers. Luckily, Industrial Park allows you to hide certain types of assets, so we can hide these to more easily get a look at the level.

At the top bar of Industrial Park, go to Display > Asset Types. Here you can hide certain asset types.  
I recommend disabling the SFX, Trigger and Volume asset types anytime you load Industrial Park, since these are the most intrusive.

Now that you have a clearer view of the level, you can take a look around using basic controls.  
Scroll up to zoom in, and scroll down to zoom out.  
Hold down the scroll wheel and move the mouse to pan the camera around.  
Use WASD to move the camera itself through the level.

Alternatively, if you press Z on your keyboard, you will enter a mode in which you can turn the camera simply by moving the mouse, similar to most PC video games. Press Z again to exit this mode.

Now you have a solid idea of how to open and view a level in Industrial Park. You can simply close the program once you are done for now.
I'd now recommend moving on to the [Using the Editor](https://sillleah.github.io/modding/editor.html) tutorial, which essentially serves as a second part to this tutorial by demonstrating how to inspect the level and the objects within by more than just sight.
