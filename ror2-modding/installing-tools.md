[Back to Modding Tutorials](https://sillleah.github.io/ror2-modding.html)

This tutorial will guide us through installing all of the different tools we need for modding Risk of Rain 2, and preparing an appropriate mod manager setup to test our mod.

## Risk of Rain 2

Naturally, as a starting point, you need to have Risk of Rain 2 installed.
I don't provide any support for cracked or pirated copies of the game.
None of the DLCs are required in order to mod the game.

Both Steam and Epic should work for modding, but these tutorials assume that you have the Steam version.

## Visual Studio Community 2022

You also need to install Visual Studio Community 2022, which you can find [here](https://visualstudio.microsoft.com/vs/community/).

Inside the installer, make sure to find and tick ".NET desktop development", so that the necessary tools to develop for .NET (which Risk of Rain uses) are downloaded.

## Setting up the Mod Manager

You should also install r2modman, which is the recommended mod manager for Risk of Rain 2. You can find it [here](https://thunderstore.io/package/ebkr/r2modman/). Hit "Manual Download" and then extract and run the installer.
(Please ONLY get R2Modman from either Thunderstore or their GitHub [here](https://github.com/ebkr/r2modmanPlus), any other sites on Google about it are FAKE!)

## Installing Our Mod Base

This might sound strange, but to start modding, we need to install a few mods.

Open r2modman and select Risk of Rain 2.
You'll be prompted to choose a profile - create a new profile and name it something fitting, this will be your 'workspace testing setup'. I named mine 'Workspace'.

Once the profile is created, navigate to the Online tab in the sidebar. You'll want to search for and install the **R2API** mod.
We do need some other mods, but they are dependencies of R2API and hence will be auto-installed for you.

Now we're ready to start actually setting up a proper mod workspace we can program in. We'll be making use of everything we just installed very soon.

I recommend moving on to the [Setting up the Workspace](https://sillleah.github.io/ror2-modding/setup-workspace.md) tutorial, which will set up a basic Visual Studio workspace for our mod.
