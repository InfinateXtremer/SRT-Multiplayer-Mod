# SRT-Multiplayer-Mod
A mod that adds some multiplayer functionality to the PC version of *Spyro: Reignited Trilogy*

## Release
We have created a compiled pack for basic multiplayer functionality which can be obtained [here](https://github.com/InfinateXtremer/SRT-Multiplayer-Mod/releases). **This pack is no longer the representation of the latest updates to this repo** Please read its details before downloading to know what its purpose and is capable of.

## 8/25/20 Update
With recent discovery, we can take advantage of the config files to create a pseudo-modular system. Currently a dictionary format is used to label and load an avatar onto a list. Originally the list was thought to be only hardcoded and would seen as a problem to create a lot of blank slots. Now the list is extendable externally which makes it more useable and less cumbersome.

It works like this:
Inside `Game.ini`
```INI
[/Game/Multiplayer/Blueprints/Overrides/MultiplayerInstance.MultiplayerInstance_C]
AvatarEntries=(("Avatar One", /Game/path/to/asset1.asset1), ("Avatar Two", /Game/path/to/asset2.asset2))
```
There are other formats that Unreal Engine supports when using their `Game.ini` file but this one is more elegant despite the strictness of having it all on one line. We are still looking into it's usablility beyond this point.

## Contribute
If you are willing to improve on this mod, depending on our decision, we can either take pull-requests or directly add you to have access to the repository.

## Disclaimer
Spyro Reignited Trilogy belongs to Activision Publishing, Inc.

For capture the flag: All maps belong to their respective owners, They are not affiliated this with project.  
 
