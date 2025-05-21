# Helmeter
This is yet another visor HUD, but this time it actually uses zscript instead an excessive amount of ACS hackery (*cough* UDV *cough cough*)

I made it to try zscript HUDs, and to make a more "modern" visor HUD.

### REQUIRES at least GZDoom v4.11, tested in 4.11.3, 4.13.2, and 4.14.0.

Note: Display graphics are kinda ugly. I am not a sprite artist, but I tried my best. 

If you wish to contribute some better looking graphics, go ahead

It probably is not the most well optimized either; I am terribly sorry

## Features
+ Armor overlay that changes with your armor amount
+ HUD and visor react to damage: visor lights flicker when taking any damage, both shake and flicker when taking heavy damage
+ Dynamic visor cracking: when taking heavy damage, the visor cracks. If you have less than 5 armor, it will stay on screen until you have at least 6 armor again
+ Displays can become glitchy and faulty when the visor is damaged
+ Displays flash orange if the number in question is low	
+ Helmet that changes brightness with the sector light level
+ Blood stains that appear on the visor as your health gets lower
+ Startup and death sequences
+ Dynamic HUD swaying as you move around, with a simulated parallax effect
+ Custom pickup message display, styled to match the rest of the HUD

#### Many features are toggleable in the options menu - be sure to check there before playing!

Plus and minus keys show and hide the visor, you can hide the displays in the options if you want "immersion"

Supports HUD scaling[^exception], but I developed and tested this mod with a scale factor of 3 on a 1080p monitor, so that's what I think it looks best at
	
## Compatibility
Should be compatible with most gameplay mods that are compatible with any custom HUD, although a minor amount of configuration is needed

This has explicit support for Brutal Doom v22.

Tested and proven to work in Rust and Bones, Act of Violence, Beautiful Doom, and several other mods.

Although, several elements are disabled due to this HUD not supporting them yet (eg. Hellrider's grenades, GS' weapon fire modes, etc)

You are free to make your own versions with compatibilty; I myself will make a Project Brutality-compatible version soon

Any mod-specific versions should be made as their own separate fork/build, to prevent bloat
	
## Known Bugs/Oddities
+ Visor cracks disappear when changing maps
+ Low warning flashes may not initially appear at full opacity
+ Custom message display does not support line breaks (multi-line messages)

## Credits
+ HUD Code and Display Graphics by DaCat001, with liberal amounts of help from the ZDoom Wiki
+ Visor graphics by DaCat001, based on NekosHud
+ Many of the more advanced features' code was made while taking peeks at Project Brutality's HUD, by generic name guy
+ Option tooltip code by ToxicFrog
+ Full list of sound credits can be found in SNDINFO, but they're mostly stock sounds from pixabay
+ Big font: NoughtPointFour by Jimmy, based on a design by id Software
+ Small font: Cyberfonter Small by TerminusEst13, edited by DaCat001

[^exception]:Broken visor effect that appears on death is not fixed in size, and will look odd on smaller sizes
