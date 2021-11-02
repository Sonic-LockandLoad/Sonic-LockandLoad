# Welcome to Sonic: Lock and Load! ![GitHub all releases](https://img.shields.io/github/downloads/SpeedStriker243/sonicdoom/total)
*Sonic: Lock and Load* is a DOOM mod for the GZDoom source port based on Sonic the Hedgehog.
Includes player classes, weapons, items and certain techniques.

I eventually plan to make this mod available as a standalone game.

## Playing the git (unstable) version
### Using `git clone`
You should have `git` installed. (You can also use [`gh-get`](https://github.com/That1M8Head/gh-get).)

#### Downloading
Run `git clone https://github.com/Sonic-LockandLoad/Sonic-LockandLoad` or `gh-get Sonic-LockandLoad Sonic-LockandLoad`.<br>
Then run the newly cloned folder with GZDoom.

#### Updating
Run `git pull` inside the folder.

### If you don't want to install `git`
At the top of the page, click `Code`, then `Download ZIP`.<br>
Run `Sonic-LockandLoad-main.zip` with GZDoom.<br>
Optionally, you can rename `Sonic-LockandLoad-edge.zip` to `Sonic-LockandLoad-edge.pk3`.<br>

***Be warned that unless you un-nest the folder inside the ZIP, you will not be able to edit maps.***

## Playing a pre-release version
All pre-release versions are [here](https://github.com/Sonic-LockandLoad/Sonic-LockandLoad/releases).

These are pre-releases from *ages ago,* so they are almost fundamentally different to the current unstable version -- it's recommended you play the unstable version.

## Does this mod support multiplayer?
No, for multiple reasons:

- The purpose of this mod is single player only.
- The weapons are way too unbalanced for multiplayer. Try it and see.
- The ACS crap I've done makes multiplayer hard to achieve.
- Every character will just look like Doomguy, because I haven't bothered to make sprites for the player character.
- This mod uses ZScript, so it's incompatible with Zandronum.
- GZDoom is not intended for multiplayer.

## Known issues
- **Sonic's Boost/Homing Attack/Light Speed Attack feels sluggish and goes slower than it should**
    - This probably means you set compatibility to `Doom (strict)`. Change it to `Default`. If this doesn't fix it, leave a GitHub issue.
- **The mod displays a message about an incompatible mod**
    - [Then don't run this mod with Brutal Doom.](https://forum.zdoom.org/viewtopic.php?t=47678)
- **Some things don't show up in the Side Levels or Tutorials**
    - These levels contain monsters from Doom II. At the moment, you will have to play with Doom II, or an alternative such as Freedoom: Phase 2.
- **Sonic is super slow, I can't kick, and dying crashes the game**
    - Your game is borked. Delete your config and reconfigure GZDoom all over again.
- **Textures and things are broken when editing maps**
    - This is usually because you downloaded a ZIP with a nested folder. (Thanks, GitHub.) You should [switch to using the `git clone` method](https://github.com/Sonic-LockandLoad/Sonic-LockandLoad#using-git-clone) if you wish to edit maps for this mod.

## Copyright
Sonic: Lock & Load is a fan-made Doom mod. All copyrights go to their intended holders.<br>
Sonic the Hedgehog is property of SEGA. DOOM is property of id Software.

This mod uses assets from [Realm667](https://www.realm667.com) and other games.
