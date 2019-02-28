``
Disclaimer: Mr. H gave permission to do this on his workshop page. Being a nice guy, he deserves every second of the respect that is about to be given. I will be helping his work move along in the coming months. This is quite literally my favorite mod.
Especially since we operate as NAVY Seals @ https://devgru.club/site
``

### COMING SOON: MORE INFORMATION REGARDING THE MODIFICATIONS
### FOR NOW, ENJOY SOME COPYPASTA OF THE STEAM WORKSHOP DESCRIPTION
Description
This mod adds a satellite to Arma 3.
## Features:

**New features**

_The mod now includes two new objects:_
*The Trivec Avant Satcom Antenna*
*The Universal Tactical Display*

Both objects work together and allow for a lighter use without the need for the backpack, however when accessing the satellite from the UTD you won't have access to the fullscreen mode and its advanced options, those remain only available from a console deployed from the backpack or created from the editor.

## To use:
If you have the antenna in your gear you will have the option to unfold the antenna, either from the scrollwheel menu, or if using ace from ace self interactions>>equipment.
This will deploy the antenna in front of you. If you have ace3 enabled you can move and drag the antenna around.

You need to connect the UTD to the antenna to receive a signal, to do so, with the utd in your inventory you will get a scrollwheel interaction when facing the antenna to connect it. Ace 3 users will have the interaction through the ace interaction menu.

Once this is done you can bring up the UTD interface by pressing CTRL+U (default, can be changed in addon options), ace users can also do it from the self interaction menu>>equipment. Of course you need to have the UTD in your inventory.

The signal will get weaker as you move further from the antenna, beyond a 100m you will lose connection from the antenna and will need to return to its position to reconnect the UTD. Also note that the further you are from the antenna the more statics you will get on your UTD screen, and the harder the image will be to read.
The utd interface can be moved around on your screen by dragging it. Close it by pressing the on/off button or the escape key.

You can fold and pick up the antenna at anytime(scrollwheel or ace interaction), once folded you will of course lose connection to the antenna (ACE users might get a small delay before the game detects that the antenna has been deleted and might still be able to access the sat for a short while)

## Operational Status

- Satellite backpack that can be put on the ground and used to deploy a satellite controle console.

- Satellite interface with computer like interface and fullscreen view.

- Pip view of what the satellite is viewing on any screen.

- Ability to move the satellite live, on small distances through configurable keybinds.

- Possibility to move the satellite on long distances by clicking on a built-in map.

- Satellite is unavailable during long distances travel, unavailability time is calculated depending on speed/distance.

- Grid coordinates and terrain elevation are displayed.

- Normal and thermal view.

## Fullscreen mod offers extended actions:

- Detection of heat sources (vehicles and units) within satellite viewrange.

- Included inventory object: Blufor transponder, any unit having the transponder in its inventory will appear with a green square on the satellite.

- Names and role description of units having the transponder will be shown on the view.

- Hovering with the mouse over a unit having a blufor transponder will display it's speed and bearing.

- Laser targeting

- Tracking: after clicking on the tracking button double click on a unit and the satellite will follow it automatically.

- Tracking will display target's speed and bearing.

**Target following and lasering will continue globaly even after exiting interface if you don't stop them.**

## For mission makers:

- Optional "satellite" module, you can define the satellite's initial position by placing the module where you want it on the map.

- From the module you can also define the satellite's moving speed ( default is 100km per hour). This will only impact long distance movement.

- You can make any object a satellite control console by putting "[this] call MRH_fnc_IsSatelliteConsole;" in its init box, if you do not want to give players access to the backpack.

- You can make any screen object display the satellite feed by putting "[this] call MRH_fnc_IsSatMonitor;" in its init box.

- You can disable access to: Fullscreen view, lasering,tracking and target detection from the addon options settings.

- You can set the satellite's max height through options (default is 300m max is 1000) this setting might require users to further view distance in graphics options.

## Languages: The mod is available in both French and English, if you wish to offer help to translate it to another language please contact me.
Spanish localization by [ESP] YoSoyGroot:
http://steamcommunity.com/id/rusete46
German localization by [GNF] Laumi
https://steamcommunity.com/profiles/76561198049400865

## Multiplayer compatibility: Yes, server key is included.
## Pvp compatibility: No, as of yet all sides have access to the same satellite.

## Known issues: This is a first release, the mod has been through very limited testing but it does the job so far, you might have some issues when displaying the satellite feed on a screen in MP.

## FAQ's PIP MUST BE ENABLED on the clients graphics settings for the mod to work properly.

** Please report any bug you find, it always helps! **

## Requirements:
- CBA_A3
- No longer requires Ace3 if ace 3 is enabled you will get the awesome ace 3 interactions, if not the bleak vanilla scrollwheel actions.

## Topic on bis forums:
https://forums.bohemia.net/forums/topic/215009-release-satellite-mod/

## Legal stuff
You may use this anyway you see fit, redistribute in your unit's homemade mod is okay, tweeking the code is okay, modifying to suit your needs is okay, as long as you give me proper credit.
**YOU MAY NOT however use this mod on a monetized server, monetizing free content is EVIL.**

## My mate RedBelette (don't ask!) is developping a nice framework to give new tools to mission makers.
- You can have a look here: http://steamcommunity.com/sharedfiles/filedetails/?id=1226877632&searchtext=red+framework

## Check out TILk's cool ballistic missiles mod here:
 https://steamcommunity.com/sharedfiles/filedetails/?id=1383958112


