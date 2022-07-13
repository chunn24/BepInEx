Description

This mod makes kilns and smelters suck up coal, wood and ore from the ground and nearby containers.

The default range is 10 meters, so you can just

a) put coal, wood, or ore in a nearby container and the furnace and kiln should suck it up, or
b) drop coal, wood, or ore on the ground near kilns or smelters.

I think this mod also works with other stations as well (many things are considered smelters, including kilns).

Doesn't work with fireplaces, torches, cooking stations yet.


Config

A config file BepInEx/config/aedenthorn.AutoFuel.cfg is created after running the game once with this mod).

You can adjust the config values by editing this file using a text editor

There are two prevent lists in the config:

FuelDisallowTypes - specifies types of consumables like wood and coal that are disallowed (does not apply to kilns, as kilns considered wood an ore)
OreDisallowTypes - specifies types of ore (anything that is transformed into something else) that are disallowed.

You can optionally set a hotkey to toggle the behaviour on and off, and you can adjust the ranges for containers and ground pulling (default 10 meters each).

You can reset the config by opening the in-game console (F5) and typing autofuel reset and pressing Enter.


Install

To install this mod, the easiest way is to just use Vortex, the Nexus Mods mod manager. It should take care of all dependencies.


Technical

Code is at https://github.com/aedenthorn/ValheimMods.
