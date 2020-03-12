How to test deliverables:

To install mod, make a new folder in Quake 4's home directory, and place the file called game000.pk4
inside the folder. When Quake loads, click the mods menu in the bottom left, and select the name of
the folder you just created.

Specific Deliverables:
Permadeath:
To test this, all you need to do is die. You will notice that the save and load buttons are no longer
functional, and you can only go back to the main menu or exit the game. In addition, the load button on
the main menu is also disabled. 


3 Characters:
In order to change characters, press ctrl-alt-~ to open the console and type this command:
character character_name
The three characters that can be chosen are:
marine (default): starts out with medium amounts of health and speed, and uses the machine gun
and shotgun

strogg: starts with lower health and higher speed, and uses the nail gun and lightning gun

heavy: starts with higher health and lower speed, and uses the hyper blaster and the rocket launcher

All characters only have 2 weapons, and are unable to pick up any new weapons during the game.
To make up for this, all weapons have infinite ammo.


5 Different Passive Items:
The player is given 5 random passive items at the start of each level, and can give themselves passives
manually by using the command:
give passive_name
The passive items are:
tougher_times: Gives a chance to block damage on each hit. Stacks diminishingly.

cautious_slug: After not being hit for a short time, the player heals over time. Each slug increases the 
healing per second

goat_hoof: Increases player movespeed by 14% per stack

lens_makers: Give the player a 10% chance to crit, dealing double damage. Each stack increases the 
chance by another 10%

hoppo_feather: Increases the player's jump height by 30% per stack. Does not reduce fall damage.

As noted in their texts, each item can stack indefinitely, increasing their effects.


Random Level Selection:

Upon making a new game or trying to go to a new level via the console, it will instead load the player into
one of 13 possible random levels. Levels that had vehicles or other problematic elements were excluded
from this list


Random Enemy Placement:

Did not finish in time.


Common Deliverables:

Updated GUI:

The GUI now has places at the top of the screen for showing how many of each passive item the player has.
Also, if the player is playing as the strogg character, they will also have the strogg hud instead
of the normal marine hud. The other characters use the standard hud.

In Game Visuals:

When attacking with a hitscan weapon, if it crits, it makes a massive yellow explosion to show that it has
crit. Also, whenever the player is getting healing from a cautious_slug, sparks will spawn around them.

A Readme:

Yes

Auto-Launch Shortcut

Will be shown off in class.

