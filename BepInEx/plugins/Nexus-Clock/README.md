This mod adds a simple but highly configurable time display to the game.


Config

You can set:
the clock's position on the screen either in pixels or percent (it defaults to top-middle).
the font name to use (see below)
the font size of the clock text
the color and transparency of the clock text
a hotkey to toggle the clock display and an optional modifier key (e.g. "left shift")
the time format (either something like HH:mm:ss or set to fuzzy to use specified time strings)
the actual displayed string to surround the the time with (including simple html tags)

You can also customize the fuzzy strings, which are used to divide the day up into custom intervals.

Clock format follows this syntax:

https://docs.microsoft.com/en-us/dotnet/standard/base-types/custom-date-and-time-format-strings


To change the mod's settings, edit the file BepInEx/config/aedenthorn.Clock.cfg (created after running the game once with this mod) using a text editor.

To reload the config from the config file while in the game, open the console (F5) and type clockmod reset then hit Enter.

Fonts

By default, the mod now uses the game's UI font, AveriaSerifLibre-Bold. If you want to use a different font, here's a list of fonts currently available in the game:

Arial

AveriaSerifLibre-Light
AveriaSerifLibre-Regular
AveriaSerifLibre-Bold
AveriaSerifLibre-Italic
AveriaSerifLibre-BoldItalic

AveriaSansLibre-Light
AveriaSansLibre-Regular
AveriaSansLibre-Bold
AveriaSansLibre-Italic
AveriaSansLibre-LightItalic
AveriaSansLibre-BoldItalic

OpenSans-Light
OpenSans-Regular
OpenSans-LightItalic
OpenSans-Italic
OpenSans-BoldItalic
OpenSans-SemiBold
OpenSans-Bold
OpenSans-ExtraBold
OpenSans-SemiBoldItalic
OpenSans-ExtraBoldItalic

Norse
Norsebold

prstart
prstartk
rune

Just change ClockFontName to one of these.

If you want to use a font installed on your OS (this is untested), set ClockUseOSFont to true and provide the name of your font file, e.g. Arial.ttf. Let me know if it doesn't work.


To install this mod, the easiest way is to just use Vortex, the Nexus Mods mod manager. It should take care of all dependencies.

To install manually, place the dll file in the BepInEx/plugins folder. You will need BepInEx.

Code is at https://github.com/aedenthorn/ValheimMods.

Changelogs
Version 1.1.1
Fixed showing when no hud
Version 1.1.0
Added text alignment
Fixed drag size
Version 1.0.0
Hide when hud hidden
Version 0.9.0
Made draggable
Version 0.8.4
Fix for update check
Version 0.8.3
Fixed toggling key
Version 0.8.1
Fix for hotkey when console open
Version 0.8.0
Added ability to show on press when show on change is active
Version 0.7.0
Added option to only show time on change then fade out
Version 0.6.1
Fixed position to be float
Version 0.6.0
Added option to use percent values for clock position
Version 0.5.0
Fixed default fuzzy string, added optional modifier toggle key
Version 0.4.1
Added console command to reload config from file
Version 0.3.4
Fixed custom clock font
Version 0.3.3
Fix for new BepInEx
Version 0.2.0
Added ability to use other fonts