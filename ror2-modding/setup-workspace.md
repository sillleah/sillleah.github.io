[Back to Modding Tutorials](https://sillleah.github.io/ror2-modding.html)

This tutorial will show you how to set up a basic workspace in Visual Studio, so that we can start developing our mod.

## Creating the Project

Open Visual Studio. You should be met with a little window asking you what you'd like to do (if you aren't, go to File > Close Solution in the top bar).

Click 'Create a new project' on the right side.

You'll be asked to choose a template - search for "Class Library". You'll see two versions - one for C# and one for Visual Basic. Select the C# version and hit next.
On the next page, you can pick a location and name for your project - I'm going with TestMod.

Finally, you'll be asked to pick a framework - choose .NET Standard 2.1 and then create the project.

## Setting up NuGet

Now, we need to set up NuGet, which is a tool used to retrieve the game's assemblies in a way that grants us additional functionality for modding.

In Visual Studio's Solution Explorer (on the left side by default), you'll see your mod's main .cs file. Right-click and choose Add > New Item, and enter 'nuget.config' as the filename.

W.I.P
