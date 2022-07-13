
Uploading this open source mod from Nexus Mods because it's not on Thunderstore yet.

Developer: [aedenthorn](https://www.nexusmods.com/valheim/users/18901754)

Original mod link: https://www.nexusmods.com/valheim/mods/740

## This mod lets you edit configs in game


This mod allows you to edit settings for BepInEx mods that make use of the BepInEx configuration system from within the game itself via an easy-to-use GUI.  

The GUI is opened and closed by pressing the hotkey (default **F1**). There is also a button to open the config manager on the main menu.  

This is a modified version of the [BepInEx Configuration Manager](https://github.com/BepInEx/BepInEx.ConfigurationManager)﻿ by MarC0 / ManlyMarco. It will disable the original version (including the one installed by Vortex) if it is found.

This mod brings the BepInEx Configuration Manager code up-to-date with the latest BepInEx version and makes it highly customizable:  

-   You can change UI colors
-   You can drag the window around the screen
-   You can resize the window
-   You can change font size
-   You can change text used in the UI

It also adds **Reload From File** and **Reset To Default** buttons to the bottom of each plugin. Reloading and resetting config will not necessarily mean you see the changes instantly. It depends completely on how and when each mod checks its config file.  

Also, you can now edit the manager's settings from within the manager itself. This can lead to problems if you try changing the size or position manually. Just delete the config file and start again if it becomes impossible to use the manager because of a messed up size or position.  

**Known Issues**  

-   It sometimes logs error messages about UI Clips to the console - these are harmless, still not sure the cause.
-   It will also log errors if you edit certain fields and they no longer fit that setting's type (if this happens as you edit them, you can just ignore the error)

## **Configuration**

A config file **BepInEx/config/aedenthorn.ConfigurationManager.cfg** is created after running the game once with this mod.  

You can adjust the config values by editing this file using a text editor or in-game using the [Config Manager](https://www.nexusmods.com/valheim/mods/740)﻿.

## **Github**
https://github.com/aedenthorn/ValheimMods/tree/master/ConfigurationManager