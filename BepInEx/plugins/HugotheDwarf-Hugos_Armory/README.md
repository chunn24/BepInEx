Adds 34 new weapons to Valheim (10 of which are visual variants). With practical damage numbers to match Valheim.
These weapons also have their own visual look while on Item Stands.
Also includes a WIP attack Speed change for Two Handed Axes, Swords, and Clubs/Maces/Hammers.


Public Localization File (will Update Embedded files with changes here each update): Google Sheet https://docs.google.com/spreadsheets/d/1BNJyY4WQeEIOUJoJgG2WuWlBpQTveS86C_h-4SW4FDg/edit#gid=195398755
You can also download the file as a .tsv and drop it in the "Valheim\BepInEx\config" path to update it yourself if you do not wish to wait for a the mod to update and then delete your old "htd.armory_localization.tsv" file to regenerate from the embedded data.


Installation:
Move the "ValheimHTDArmory.dll" into your Plugins folder.
Also Download "MorePlayerClothColliders.dll" and move that into your Plugins folder as well. (This is mainly for the armor set it's not required for the mod to function)


Config:
A config file is generated that will allow you to enable/disable the recipes for each one, tweak their damage stats, the Name, and Description (temporary means of localization), and where it is crafted, the min level of the station, and the max level the weapon can be upgraded to.
Can also set a Hotkey to use the weapon's 3rd attack, default is "mouse 3" which would be the 4th button on your mouse if it has such.
Also the base Config has options to disable the Attack Speed changes, Disabled light effects for the Silver Battleaxe, and disable the particles for the Flametal Greatsword.


Console/Cheats/Configs Item IDS:
- Buck and Doe ::: DeerFistsHTD
- Bronze Knuckles ::: BronzeFistsHTD
- Iron Knuckles ::: IronFistsHTD
- Silver Claws ::: SilverFistsHTD

- Bronze Greatsword ::: BronzeGreatSwordHTD
- Bronze Battleaxe ::: BronzeBattleaxeHTD
- Bronze Sledge ::: BronzeHammerHTD
- Bronze Crowbill ::: BronzeCrowbillHTD

- Iron Greatsword ::: IronGreatSwordHTD
- Heavy Iron Great Sword ::: IronHeavyGreatSwordHTD
- Dragon Slayer ::: DragonSlayerSwordHTD

- ﻿Core Mace ::: CoreMaceHTD
- Core Mace Green ::: CoreMaceGreenHTD
- Core Mace Blue ::: CoreMaceBlueHTD

- Great Core Mace ::: CoreGreatMaceHTD
- Great Core Mace Green ::: CoreGreatMaceGreenHTD
- Great Core Mace Blue ::: CoreGreatMaceBlueHTD

- Core Axe ::: CoreAxeHTD
- Core Axe Green ::: CoreAxeGreenHTD
- Core Axe Blue ::: CoreAxeBlueHTD

- Great Core Axe ::: CoreGreatAxeHTD
- Great Core Axe Green ::: CoreGreatAxeGreenHTD
- Great Core Axe Blue ::: CoreGreatAxeBlueHTD

- Silver Greatsword ::: SilverGreatSwordHTD
- Great Silver Mace ::: SilverGreatMaceHTD
- Silver Battleaxe ::: SilverBattleaxeHTD

- Black Metal Greatsword ::: BlackMetalGreatSwordHTD
- Black Metal Greatsword Foreign ::: BlackMetalGreatSwordAltHTD
- Black Metal Battleaxe ::: BlackMetalBattleaxeHTD

- Grasp of Undying ::: BoneGreatMaceHTD
- Body of the Devoted ::: BoneGreatSwordHTD

- Moder's Sorrow ::: ObsidianGreatSwordHTD
- Moder's Sorrow Red ::: ObsidianGreatSwordRedHTD
- Flametal Greatsword ::: FlametalGreatSwordHTD

- Boar Berserker Headdress ::: ArmorHelmetBoarHTD
- Boar Berserker Chest ::: ArmorChestBoarHTD
- Boar Berserker Skirt ::: ArmorLegsBoarHTD
- Boar Berserker Scarf ::: ArmorShoulderBoarHTD

ChangeLog:
V7.0.0 => 7.0.1
- Fixed a error between client and server regarding recipes.
- Adjusted Scale and rotation of the Boar Berserker Headdress

V 6.1.0 => 7.0.0
- Added One-Handed Core Maces
- Added Great Core Axes
- Added One-Handed Core Axes
- Added early game armor set + set effect
- Added WIP attack speed system for Two Handed Weapons (Axes, Swords, Clubs/Maces/Hammers)
- Re-Balanced weapon stats and weights (won't affect  existing configs, only new installs/config generations)
- Added some Sheathes to the Iron, Silver, and Blackmetal Exotic(alt) Greatswords
- Recoded Recipe material lookup, can now find materials from other mods now.
- Added sync-able Armor config
- Added Config option to disable the attack speed stuff in case of conflicts with other mods that do the same.
- Some stuff that I forgot about but was probably  bug fixes or visual adjustments that will be show up in time I guess.

V 6.0.0 => 6.1.0
- Added Config value to turn off light effect from silver battleaxe (for those that may be sensitive to flashing/flickering light)
- Added "Enabled" to weapons in the itemData config, setting this to false will have the weapons damage be set to 0. This is for instances where you may wantt to disable the recipe and weapon so you'll never see it on your server, and
   if someone does bring said weapon(s) in from another world/save/character it will be useless
- Finally fixed the error when logging out to main menu if you are using mods that include RockerKitten's new cooking pieces (error was on my end, not hers)
- Tweaked some more code to hopefully be more optimized, my mod's load time is rather quick now (it was decent before, but should be better now).
- Slimmer Greatswords will be held like the battleaxe is (silver greatsword, iron, and blackmetal exotic as well) Will possibly create config settings to toggle the over the should look, or battleaxe in the future.

V 5.0.2 => V 6.0.0
- Added Bronze weapons to fill out missing two handed classes (Axe, Sword, Club)
- Added suggested one handed weapon Bronze Crowbill (other material grades to come)
- Added Silver Claws to continue the Fist weapon progression
- Tweaked particles for Grasp of Undying and Body of the Devoted
- Added some effect animation for Grasp of Undying and Body of the Devoted

V 5.0.0 => V 5.0.1
- Renamed ALL Prefab names, effectively "deleting" all weapons from saves, sorry.
- Updated to latest Valheim (Hearth and Home)
- Updated ServerSync (by Blaxxun) this is responsible for well syncing config data from server to clients
- Fixed all visual errors with maces and axes (was rotated oddly since H&H dropped)
- Revamped and added visual effects for various weapons
- Added a Red version of Moder's Sorrow
- Added a Blue version of the Great Core Mace (now you can have a mace for each color of standing iron torches)
- Made some Two Sided Shaders, will play a major role later, but currently just used for fist weapons so you can't see through them when viewing them the right way
- Fist Weapons now use the Attach_Override of "Hands" this should make them work with the Monk class from Valheim Legends, currently this means they're not attached to your hip like before when sheathed (for now)
- Tweaked all colliders, don't think they were an issue before, but they are redone.


Code: Github https://github.com/Hugo-the-Dwarf/ValheimMoreTwoHanders