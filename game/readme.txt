Hello this is Ashy and this is a template designed for Dota 2 But modes, which were inspired by Baumi.

To modify content in this mod follow these easy rules:

to modify text within the mod: go to resource then addon_english.txt, all text should be placed within this file to load it during the mod, I have only added the text for the gamemodes name currently.

to modify gamerules simply edit settings.lua within the scripts>vscripts folder.

to add brand new abilities, items, heroes and units, there is 2 ways to achieve this, either use lua or create them "datadriven", the basic rule of thumb is: datadriven can achieve alot of things however for more complex abilities etc lua is the only reliable way to go, once you decide which ability simply go into scripts>npc>npc_whatufancy_custom.txt and add it to bottom of the document (if you're having issues: use one of the highly valuable guides I have placed below).
http://moddota.com/forums/discussion/14/datadriven-ability-breakdown-documentation
https://moddota.com/forums/discussion/4/datadriven-items
https://moddota.com/forums/discussion/224/datadriven-units

however if you choose the path of lua:
http://moddota.com/forums/discussion/135/beginners-guide-to-dota-scripting
https://developer.valvesoftware.com/wiki/Dota_2_Workshop_Tools/Scripting/API

and to modify already existing abilities,items,units etc simply change their values within scripts>npc>npc_whatufancychanging_custom.txt (I have placed all current abilities, items, heroes and units into these files)

lastly to test your gamemode and publish it, place this whole folder into your "*\steamapps\common\dota 2 beta\game\dota_addons" folder and rename it, then you can load into it via dota 2 workshop tools and when loaded in workshop tools you may test the gamemode via the console (to open: type `) then type dota_launch_custom_game <nameofyourmodsfolder> dota


good luck and have fun, if you have any questions or issues whatsoever simply send me a pm via my steam: https://steamcommunity.com/id/luppylupan

credit goes to the individuals who made those awesome guides above and dota barebones.