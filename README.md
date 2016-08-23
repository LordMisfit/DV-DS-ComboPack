DV-DS-ComboPack [Deus Vult Doomspell Edition Combination Package] 

- Includes modified [harder] mapsets for Deus Vult I and Deus Vult II (multiplayer-only monsters are now single-player used) and with a few new in-level scripts, and even a few 'bosses' [things worse than Cyberdemons I mean].
- Can also be ran with Classic Doom 1 & Doom 2 [including TNT, Plutonia, and many megawads designed for both, but not all will work perfectly, and some might not work at all, use with certain megawads at your own discretion].
- Three character classes. Although two of them are basically magic-wielding Marine-type characters with different stat growths.
- The third is an unique mage-like class with a surprisingly powerful melee weapon, causing you to measure risk for reward for putting a 'glass cannon' at close range with monsters.
- RPG mechanics included. Experience points, magic spells, various statistics, variable enemy strengths based on game-wide progress or difficulty level, a 'Psyche Up' mechanic to temporarily make your character stronger in bursts for special situations, etc.
- Monsters can occasionally 'evolve' into stronger versions of their general species, and/or become mostly invisible to the player [although it's not ZDoom-style stealth outright (not anymore)]


HOW TO INSTALL / RUN / ETC:

 - Installing - 1. Make sure you have a designated ZDoom/GZDoom folder. This mod WILL REQUIRE GZDoom due to use of it's various functions and ZDoom on it's own will not look right with it for the most part. You might even want to make a seperate GZDoom folder for this as it uses a very specfic SVN version [see 3.] to run and not a stable 2.8.1 or even the most current SVN version.

 - Installing - 2. Unzip the entire DV-DS-ComboPack FOLDER into the GZDoom folder. The mod is loaded in folder format, so don't put the contents of the DV-DS-ComboPack folder in the main GZDoom folder itself, it won't work. :o

 - Installing - 2 Extra. If you get the DV-DS-CompatPacks stuff, you also need to do the above and unzip the entire DV-DS-CompatPacks folder into your GZDoom folder as well. However discussion for how to run those will be discussed in the Readme on its' respective git repository. :P
- Note: This means DV-DS-ComboPacks and DV-DS-CompatPacks will each be their own folders in your GZDoom folder. Do NOT try to unzip one repo's folder into the other's main folder. You'll have messed things up and have to redo this again. >.>

 - Installing - 3. Go into the EXTRAs subfolder in the DV-DS-ComboPacks folder and extract the contents of "gzdoom-g2.2pre-889-g904a027.7z" into your GZDoom folder itself, as either the proper gzdoom.exe or rename it to something you'll remember. But it's REQUIRED to use this version right now due to various techincal reasons. :V

 - Running - 1. There is no launcher packed with DV-DS-ComboPack, you'll have to rely on command lines for now. My general method is to create a batch [.bat] file and name it something you'll remember. Remember you can right click a .bat file and "edit" them to change the command line used inside.

 - Running - 2. The most basic commandline for playing DV-DS with Doom 2 is "start gzdoom.exe -iwad doom2.wad -file "DV-DS-ComboPack" +hud_scale 0 exit". 
 - Note: DV-DS highly recommends using "hud_scale 0" for HUDs, so keep that in mind if you play this and go back to a different mod and your hud looks odd, you'll likely need to enter "hud_scale 1" or so in your console when you play said other mod. :P
 - Note: Putting "start" and "exit" around a command line makes the CMD prompt that pops up immediately disappear so you don't have to manually close the window after the command runs. However if you're making a shortcut that's not a .bat file, you don't need "start" or "exit" in those command lines.
 - Running - 3. If you want to run DV-DS properly in Doom 1 mode, you'll need to get the DV-DS-CompatPacks git as that has the necessary patch for running complete in Doom1. The command line will be "start gzdoom.exe -iwad doom.wad -file "DV-DS-ComboPack" "DV-DS-CompatPacks/Doom" +hud_scale 0 exit". 
 - Note: Doom 1 mode will chain all four episodes together as a long single experience though [restarting your inventory/stats per episode breaks the point of the mod's RPG mechanics], so you won't be able to select a specfic episode at game load. You start at E1M1 and end at E4M8. :P

 - Running - 4. Plutonia Experiment Command line: "start gzdoom.exe -iwad plutonia.wad -file "DV-DS-ComboPack" +hud_scale 0 exit" 

 - Running - 5. TNT: Evilution Command line: "start gzdoom.exe -iwad tnt.wad -file "DV-DS-ComboPack" +hud_scale 0 exit" 

 - Important: If you're playing in pure Doom 2 or Doom 1 mode [and or using a Doom 1 or 2 mapset], you'll get three "episodes" in the start up menu. The first two are the Deus Vult [1] and Deus Vult 2 "campaigns", and then a third that reflects the game you loaded up. That third episode is for playing Doom 1/2/Plutonia/TNT's actual levels, or the mapset you're loading with it. The DV episodes are named in their own name format and don't conflict with the other stuff, and thus are seperated in their own "episodes".

