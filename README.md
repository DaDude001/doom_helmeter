INFO
This is yet another visor HUD, but this time it actually uses zscript instead an excessive amount of ACS hackery (*cough* UDV *cough cough*)
I made it to try zscript HUDs, and to make a more "modern" visor HUD.
REQUIRES at least GZDoom v4.11, tested in 4.11.3, 4.13.2, and 4.14.0.
Should be compatible with most gameplay mods that are compatible with any custom HUD, although a minor amount of configuration is needed
This has explicit support for Brutal Doom v22.
Tested and proven to work in Rust and Bones, Hellrider v0.9, and Gunslinger Set.
	Although, several elements are disabled due to this HUD not supporting them yet (eg. Hellrider's grenades, GS' weapon fire modes, etc)

Note: Display graphics are kinda ugly. I am not a sprite artist, but I tried my best. 
	If you wish to contribute some better looking graphics, go ahead
	
Features:
	Visor with lights that change color depending on how much armor you have
	HUD and visor react to damage: visor lights flicker when taking any damage, both shake and flicker when taking heavy damage
	Dynamic visor cracking: when taking heavy damage, the visor cracks. If you have less than 5 armor, it will stay on screen until you have at least 6 armor again
	Displays can become glitchy and faulty when the visor is damaged
	Displays flash orange if the number in question is low	
	Helmet that changes brightness with the sector light level
	Cool and definitely-not-stolen death sequence
	
Many features are customizable; you can disable the displays, the damage effects, etc, along with the opacity of several things

+ and - show and hide the visor, you can hide the displays in the options if you want "immersion"

Supports HUD scaling (mostly), but I developed and tested this mod with a scale factor of 3 on a 1080p monitor, so that's what I think it looks best at

KNOWN BUGS/ODDITIES
Low warning flashes may not initially appear at full opacity
	This is because the animation is always being played in the background, unless the feature is disabled

CREDITS
HUD Code and Display Graphics by DaCat001, with liberal amounts of help from the ZDoom Wiki
Originally based on a hud by Mithriak and Mike12, although barely any of that remains
Visor graphics by DaCat001, based on NekosHud
A single line of code each for the helmet brightness and the HUD messages taken from Project Brutality
Option tooltip code by ToxicFrog

Visor crack sounds from various Valve games (generic Source glass bullet impact sfx)
Big font: NoughtPointFour by Jimmy, based on a design by id Software
Small font: Cyberfonter Small by TerminusEst13, edited by DaCat001