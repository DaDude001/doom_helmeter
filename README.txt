INFO
This is yet another visor HUD, but this time it actually uses zscript instead an excessive amount of ACS hackery (*cough* UDV *cough cough*)
I made it to try zscript HUDs, and to make a more "modern" visor HUD.
Should be compatible with most gameplay mods that are compatible with any custom HUD, although a minor amount of configuration is needed
Tested and proven to work in vanilla, Brutal Doom v22, Rust and Bones, and Gunslinger Set
	Although, several elements are disabled due to this HUD not supporting them yet (eg. BD stamina, GS' weapon fire modes, etc)
Note: Display graphics are kinda ugly. I am not a sprite artist, but I tried my best. 
	If you wish to contribute some better looking graphics, go ahead
Features:
	Visor with lights that change color depending on how much armor you have
	HUD and visor react to damage: visor lights flicker when taking any damage, both shake and flicker when taking heavy damage
	Dynamic visor cracking: when taking heavy damage, the visor cracks. If you have less than 5 armor, it will stay on screen until you have at least 6 armor again
	Displays flash orange if the number in question is low	
Many features are customizable; you can disable the displays, the damage effects, etc, along with the opacity of several things

+ and - show and hide the visor, you can hide the displays in the options if you want "immersion"

Supports HUD scaling (mostly), but I developed and tested this mod with a scale factor of 3 on a 1080p monitor, so that's what I think it looks best at

KNOWN BUGS/ODDITIES
Visor cracks reset upon loading save
Low warning flashes only update when exiting the menu, unlike all the other options
Low warning flashes may not initially appear at full opacity
	This is because the animation is always being played in the background, unless the feature is disabled
HUD messages have the % (percent) and & (ampersand) symbols swapped
	This is an error with the font itself
	
CREDITS
HUD Code and Display Graphics by DaCat001, with liberal amounts of help from the ZDoom Wiki
Originally based on a hud by Mithriak and Mike12, although barely any of that remains
Visor graphics by DaCat001, based on NekosHud
A single line of code for the HUD messages taken from Project Brutality
Option tooltip code by ToxicFrog

Visor crack sounds from various Valve games (generic Source glass bullet impact sfx)
Big font: NoughtPointFour by Jimmy, based on a design by id Software
Small font: Enlightening Small also by Jimmy, from Darkening E2
