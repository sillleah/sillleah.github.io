[Back to Modding Tutorials](https://sillleah.github.io/modding.html)

This tutorial will show you the more advanced aspects of inspecting a level in Industrial Park and viewing objects.  
It essentially serves as a second part to the [Basics of Industrial Park](https://sillleah.github.io/modding/industrial-park.html) tutorial, so I highly recommend you view that tutorial first.

If you don't already have it open, open Industrial Park and open a level as shown in the last tutorial. For the purposes of this guide, I'll be opening The Mystery Machine, but you can open any level you like.

## The Archive Editor Windows

When you load a level in Industrial Park, you probably notice the extra windows that pop up - one for your level .HIP, and one for boot.HIP.
I call these windows **Archive Editor Windows** - and they provide information on objects and data within a level that can't be determined purely by visuals.

![Archive Editor window](/assets/archive-window.png)

If you've closed an Archive Editor Window, you can easily reopen it from Industrial Park's top bar by going to Archive Editor > the name of the .HIP you wish to reopen the window for.  
You can generally close any Archive Editor Window that you aren't currently using, if you'd like to keep tidy.

## Inspecting Objects

When you click on an object in a level, it'll be highlighted in red, and will also be highlighted as an entry in the level's Archive Editor Window - as with this snack in the screenshot below.

![A highlighted object](/assets/view-object.png)

We won't be making any edits to objects in this tutorial (we'll save that for the [Basics of Level Editing](https://sillleah.github.io/modding/level-editing.html) tutorial), but let's take a closer look. Right-click on the object entry in the Archive Editor Window (SNACK 50 in the case of my screenshot) and click 'Edit Data'.  
This will bring up the Data window for that object, containing all the different information and parameters of that object - position, rotation, visual flags, any object-specific data, etc.

## Finding Objects In The Archive Editor Window

You can also use the Archive Editor window to help find certain objects.
Let's take a hypothetical scenario for now - say that you want to edit the text shown by a specific clue in the level, or more specifically, let's say I want to edit the text of the clue next to the Hedge Key in Mystery Machine.
The Archive Editor window can help you easily find this text.

First, make sure the Archive Editor Window is set to the right layer, which is usually Layer 04: DEFAULT.

![Selecting a layer](/assets/layer-default.png)

Then, you can look for the appropriate asset type, which would be Text in this case. Now the Archive Editor Window only shows text objects.

![Selecting an asset type](/assets/asset-type.png)

Or, you can even use the Find box next to the Type dropdown to search for an object by name, although names aren't always consistent with the object's function.
A guide to the different layers and asset types in most .HIPs is available [here](https://sillleah.github.io/modding/layers-assets.html).

## Saving

I haven't told you to make any actual changes in Industrial Park yet - but once you do, you'll obviously want to save them.
You can save in Industrial Park by using the top bar to navigate to Tools > Save All Open HIPs.



Now you should have a good grasp of viewing and finding objects inside of Industrial Park. Next I recommend you visit the tutorial on [Testing the Game](https://sillleah.github.io/modding/testing.html), since this is the last important building block to learn before you're ready to start actually modifying the game!
