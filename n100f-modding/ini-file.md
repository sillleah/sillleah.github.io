[Back to Modding Tutorials](https://sillleah.github.io/modding.html)

This tutorial details how to edit the sd2.ini file to modify Night of 100 Frights' internal game settings, such as Scooby's speed or the starting level.

Open 'sd2.ini' in the 'files' folder of your extracted game files in a text editor. Notepad will do but I would highly recommend [Notepad++](https://notepad-plus-plus.org/downloads/) or [Sublime Text](https://www.sublimetext.com/).

## Parameters

You can edit almost anything inside the ini file. There's little harm in messing around with it, and much of the file is annotated, but here's a guide to what you can edit and what it does!

- **PATH**: This seems to establish the path to the game files, so you don't want to change it.
- **BOOT**: This is the .HIP file the game will first load into when you start a new game. Usually this is H001 (Mystery Machine) but you can change it to any level filename.
- **ShowMenuOnBoot**: This is usually set to 1. If set to 0, it bypasses the intro sequence and main menu when starting the game, loading straight into the first level. As side effects, this also presents loading screens from appearing, and choosing 'Quit Game' in the pause menu will play the intro sequence.
- **AnalogMin and AnalogMax**: These control the analog stick deadzones for moving Scooby. Reducing these values will make the control stick more sensitive, while increasing them will make the control stick less sensitive.
- **Speed values**: These allow you to modify the initial and maximum speeds of Scooby's different types of basic movement (walking, running, etc.). SpeedWalk controls Scooby's ordinary movement speed, SpeedRun controls Scooby's run speed, SpeedSneak controls Scooby's speed while sneaking with the Slippers & Lampshade / Black Knight Armor, and SpeedAir controls Scooby's aerial speed. SpeedHotsauce is for the unused Hotsauce powerup.
- **AnimSneak and AnimWalk**: These control the animation speed of Scooby's sneak and walk animations.
- **Gravity**: This controls the game's gravity physics. Higher values cause things to fall more quickly while lower values cause things to fall more slowly.
- **JumpGravity**: This seems to have a miniscule effect on the ascent and descent of Scooby's jump. Very high values cause Scooby's jump to quickly lose upwards momentum. Low values make Scooby's jumps slower and floatier.
- **GravSmooth**: This seems to control some sort of smoothing effect on gravity, but I couldn't notice much difference from changing it.
- **FloatSpeed**: I believe this controls the speed at which Scooby descends (or ascends in a gust/fan) while using the Umbrella.
- **ButtsmashSpeed**: This controls Scooby's movement speed whilst in the middle of initiating the Super Smash.
- **TakeDamage**: If set to 0, this essentially gives Scooby infinite health. The name is somewhat misleading, since Scooby can still 'take damage' and be subject to the flinch animation, he just doesn't lose any health in the process. One-hit-kill hazards like water are unaffected.
- **StartSlideAngle and StopSlideAngle**: These control how steep a slope must be for Scooby to start or stop sliding down it.
- **Rot Settings**: These control Scooby's behavior of rotating to match the angle of slopes he stands on. RotMatchMaxAngle determines the maximum angle he can match, RotMatchMatchTime controls the amount of time it takes him to change to that angle (in seconds), and RotMatchRelaxTime controls the amount of time it takes him to return to normal after leaving the slope.
- **Jump Settings**: These control the properties of Scooby's different types of jumps.
  - Jump refers to Scooby's regular single jump, Double refers to the second midair jump from the Springs invention, Bounce refers to the 'jump' from bouncing on a small enemy, and Spring refers to the jump from springboards. These jumps are almost identical under normal circumstances, but this file allows you to differentiate them if you wish.
  - The first parameter controls the height of that type of jump - higher values result in a higher jump, and vice versa.
  - The second parameter essentially controls the 'air time' of the jump - higher values cause Scooby to float for a little bit before falling, while lower values make his jumps feel 'heavy'.
  - The third parameter seems to control how quickly Scooby's vertical speed changes as his jump ascends and descends.
- **Headbutt Settings**: These control the properties of Scooby's charge. HeadbuttSpeedMin and HeadbuttSpeedMax control the minimum and maximum charge speed. HeadbuttAccel controls how quickly Scooby reaches his maximum charge speed. HeadbuttTimeMin controls the minimum time Scooby must charge for before releasing the button ends the charge, and HeadbuttTimeMax controls the maximum time Scooby can charge for before he is forced to stop. HeadbuttTurn controls the maximum turning rate while charging.
- **HeadbuttDistance and HeadbuttTime**: These are unused and have no effect.
- **Fire Settings**: These control the properties of firing soap or gum projectiles. FireDelay determines the delay from pressing the button to actually shooting the projectile. FireRepeat controls how often each shot can be fired in succession. FirePress determines how often a projectile button press can be inputted.
- **Fire Target Settings**: These control Scooby's behavior of slightly rotating to 'aim' at enemies when firing soap or gum. FireTargetYaw and FireTargetPitch control how far Scooby can 'lock on' to an enemy from his current facing angle, horizontally and vertically respectively. FireTargetDist is the minimum distance between Scooby and the target. FireTargetRadius determines the size of the 'bounding box' of the enemy for targeting purposes.
- **Projectile Tracking Settings**: These control how soap and gum projectiles slightly track their target. This mechanic is usually disabled. FireTrack controls the tracking capability of a projectile. FireGumSpeed and FireSoapSpeed control the airspeed of gum and soap projectiles respectively. FireGumTimer and FireSoapTimer determine how long these projectiles travel through the air for before disappearing.
- **Ammo Settings**: AmmoCapacityGum and AmmoCapacitySoap control how much gum and soap ammo Scooby starts the game with. AmmoSceneGum and AmmoSceneSoap set a minimum amount of gum and soap ammo for Scooby to respawn with.
- **Special Moves**: Setting any of these parameters to 1 will cause Scooby to begin the game with the specified powerup. FlowerPot and DivingHelmet are unused and do nothing.
