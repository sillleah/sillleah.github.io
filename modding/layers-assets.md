[Back to Modding Tutorials](https://sillleah.github.io/modding.html)

## Layers and Asset Types

### Layers

Usually, most .HIP levels use the following format/rules for layers:

- **TEXTURE** layer: This layer stores textures, self-explanatory. Textures go on this layer, and nothing else should go here, or the game may crash.
- **BSP** layer: This layer stores BSP data which contains the level geometry and environmental textures. You generally shouldn't touch this layer.
- **MODEL** layer: This layer stores object models. Models go on this layer, and nothing else should go here, or the game may crash.
- **DEFAULT** layer: Anything that doesn't belong specifically on another layer goes here.
- **SRAM** layer: This layer stores audio data. Sounds and sound streams go on this layer (but *not* SFX), and nothing else should go here, or the game *will* crash.
- **SNDTOC** layer: This layer stores some miscellaneous data. You shouldn't ever need to touch it.

### Asset Types

Here are most asset types you will encounter while modding:

- **Animation**: A singular animation.
- **Animation List**: A list of animations.
- **Animation Table**: A table of animations.
- **BSP**: BSP data containing level geometry and environment textures.
- **Camera**: A specific camera configuration (position, facing angle, etc.)
- **Conditional**: An object that checks a condition and then only executes certain links if that condition is met.
- **Cutscene Manager**: An object that initiates a cutscene.
- **Destructible Object**: An object that can be destroyed in some form.
- **Dispatcher**: An object that only exists to receive and run links.
- **Environment**: An object that defines environmental and climate data for a level.
- **Fog**: A fog object.
- **Group**: A group of multiple objects to be used interchangably in some way (such as playing a random sound from a selection).
- **Light**: An object that produces light.
- **LobMaster**: An object that handles the "lobbing" animation of other objects.
- **Marker**: An object that marks a designated point in the level to be used by other objects.
- **Model**: A model.
- **Model Info**: Stores info and data on specific models.
- **Morph Target**: I'm not actually entirely sure what these are for. Seems to modify level geometry for digging flowers?
- **Particle Emitter**: An object that creates particles.
- **Particle System**: Essentially a group of settings for a particle emitter to use.
- **Pickup**: A collectible object like a key or a snack.
- **Platform**: A basic collision object.
- **Player**: Scooby.
- **Portal**: A loading zone to a location.
- **Projectile**: A projectile of some sort.
- **SFX**: A sound effect definition containing volume, location, etc.
- **Simple Object**: A basic object with no special properties.
- **Sound**: A sound.
- **Sound Stream**: A looping sound.
- **Surface**: An interactable surface with different movement properties.
- **Surface Mapper**: An object that maps surfaces to the level geometry.
- **Text**: A piece of text.
- **Texture**: A texture to be mapped to a model. Belongs on the TEXTURE layer.
- **Timer**: An object that waits a certain amount of time after being triggered, then executes links.
- **Trigger**: An invisible area that triggers links whilst Scooby is inside.
- **User Interface Font**: A UI object showing a text object in a certain font.
- **Villain**: An enemy.
- **Volume**: A certain area with specific properties.
