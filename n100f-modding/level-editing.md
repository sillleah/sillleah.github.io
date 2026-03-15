[Back to Modding Tutorials](https://sillleah.github.io/n100f-modding.html)

This is the first tutorial that will guide you through actually editing levels in Industrial Park.
Making level edits opens up a lot of potential to create unique modded experiences, or to just fill Mystery 1 with crabs if that's something you're interested in.

![Mystery 1 with crabs](/assets/n100f/crabs.png)

Before we can get to the fun stuff, though, we need to cover the basics of making changes to objects in Industrial Park.
If you need a refresher on viewing levels in Industrial Park and selecting objects in the editor, refer back to the [Basics of Industrial Park](https://sillleah.github.io/n100f-modding/industrial-park.html) and [Using the Editor](https://sillleah.github.io/n100f-modding/editor.html) tutorials.

## Deleting an Object

Let's start with something simple. We're going to delete an object from the level entirely.
You can use any level and object you like, but I'm going to be deleting the Hedge Key from 'The Mystery Machine: Part 1' in this example.

First, adjust the camera as necessary and then select the object in the level by clicking on it.

![The selected Hedge Key](/assets/n100f/hedge-key.png)

Then, simply press DEL on your keyboard.
Alternatively, you can right-click on the selected object in the Archive Editor Window and select 'Remove'.

![Deleting the key](/assets/n100f/hedge-key-delete.png)

(Side note: Be careful which objects you delete - if you delete an object that another object in the level relies on to function, you might cause the game to crash. (For example, if you were to delete the text object displayed by a clue.)

## Moving an Object

Now let's cover how to move objects.
When you select an object in Industrial Park, three arrows will appear around it - one red, one blue, and one green.
You can click on these arrows and drag to move an object along that axis.
Pretty simple.

You can press V on your keyboard to cycle through a few different modes for moving objects, such as being able to rotate them.

## Editing Objects

We previously learned in the [Using The Editor](https://sillleah.github.io/n100f-modding/editor.html) tutorial how to inspect an object in the Archive Editor window and view it's Data by clicking 'Edit Data'.
For example, here I select a random snack.

![Data window](/assets/n100f/snack-data.png)

You can edit all sorts of different parameters in this window to manipulate the object.

- For example, if you need to make precise changes to the position of an object or just prefer working with coordinates, you can simply edit the PositionX, PositionY and PositionZ values in this window to move the object.
- You can also change the *rotation* of objects in this way by editing Yaw, Pitch and Roll.
- You can rescale objects by editing ScaleX, ScaleY, and ScaleZ, to make bigger or smaller objects.
- You'll also likely have extra parameters to manipulate depending on the object type you've chosen.

We'll be covering parameters in this data window a lot in future tutorials to do all sorts of things.

Congrats, you've learned the basics of manipulating objects inside of Industrial Park.
Feel free to have a poke around with this new knowledge - maybe move or delete some objects and then Save All Open HIPs (under Tools) and test the game (you can refer back to [Testing The Game](https://sillleah.github.io/n100f-modding/testing.html) if you don't remember how to do that) to see your changes!

In the next tutorial in this mini-series, we'll dive into adding new objects - move on to [Adding Objects](https://sillleah.github.io/n100f-modding/adding-objects.html) when you're ready!


