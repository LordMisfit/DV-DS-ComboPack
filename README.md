DV-DS-ComboPack ["Aetherius"]

- Can also be ran with Classic Doom 1 & Doom 2 [including TNT, Plutonia, and many megawads designed for both, but not all will work perfectly, and some might not work at all, use with certain megawads at your own discretion].
- Can also be ran with Heretic, Hexen and Strife [though this requires the "DV-DS-iDTech1" repo as well.
- Three character classes. Although two of them are basically magic-wielding Marine-type characters with different stat growths.
- The third is an unique mage-like class with a surprisingly powerful melee weapon, causing you to measure risk for reward for putting a 'glass cannon' at close range with monsters.
- RPG mechanics included. Experience points, magic spells, various statistics, variable enemy strengths based on game-wide progress or difficulty level, a 'Psyche Up' mechanic to temporarily make your character stronger in bursts for special situations, etc.
- Monsters can occasionally 'evolve' into stronger versions of their general species, and/or become mostly invisible to the player [although it's not ZDoom-style stealth outright (not anymore)]


HOW TO INSTALL / RUN / ETC [if you downloaded the "*-master.zip" file(s)]:

 - Installing - 1. Make sure you have a designated ZDoom/GZDoom folder. This mod WILL REQUIRE GZDoom due to use of it's various functions and ZDoom on it's own will not look right with it for the most part.

 - Installing - 2. Unzip the entire "DV-DS-ComboPack-master" FOLDER into the GZDoom folder you designated. The mod is loaded in folder format, so don't put the contents of the DV-DS-ComboPack folder in the main GZDoom folder itself, it won't work. :o

 - Installing - 2 Extra. If you get the DV-DS-CompatPacks stuff, you also need to do the above and unzip the entire "DV-DS-CompatPacks-master" folder into your GZDoom folder as well. However discussion for how to run those will be discussed in the Readme on its' respective git repository. :P
- Note: This means "DV-DS-ComboPack-master" and "DV-DS-CompatPacks-master" will each be their own folders in your GZDoom folder. Do NOT try to unzip one repo's folder into the other's main folder. You'll have messed things up and have to redo this again. >.>

 - Installing - 2 Extra 2. If you get the DV-DS-iDTech1 stuff, you also need to do the above and unzip the entire "DV-DS-iDTech1-master" folder into your GZDoom folder as well. However discussion for how to run those will be discussed in the Readme on its' respective git repository. :P
- Note: This means "DV-DS-ComboPack-master" and "DV-DS-iDTech1-master" will each be their own folders in your GZDoom folder. Do NOT try to unzip one repo's folder into the other's main folder. You'll have messed things up and have to redo this again. >.>

 - Running - 1a. There is no launcher packed with DV-DS-ComboPack, you'll have to rely on command lines for now. My general method is to create a batch [.bat] file and name it something you'll remember. Remember you can right click a .bat file and "edit" them to change the command line used inside.

 - Running - 1b. The most basic commandline for playing "Aetherius" with Doom 2 is "start gzdoom.exe -iwad doom2.wad -file "DV-DS-ComboPack-master" exit". 
 - Note: Putting "start" and "exit" around a command line makes the CMD prompt that pops up immediately disappear so you don't have to manually close the window after the command runs. However if you're making a shortcut that's not a .bat file, you don't need "start" or "exit" in those command lines.

 - Running - 1c. If you want to run "Aetherius" properly in Doom 1 mode, you'll need to get the DV-DS-CompatPacks git as that has the necessary patch for running complete in Doom1. The command line will be "start gzdoom.exe -iwad doom.wad -file "DV-DS-ComboPack-master" exit". 
 - Note: Doom 1 mode will chain all four episodes together as a long single experience though [restarting your inventory/stats per episode breaks the point of the mod's RPG mechanics], so you won't be able to select a specfic episode at game load. You start at E1M1 and end at E4M8. :P

 - Running - 1d. Plutonia Experiment Command line: "start gzdoom.exe -iwad plutonia.wad -file "DV-DS-ComboPack-master" exit" 

 - Running - 1e. TNT: Evilution Command line: "start gzdoom.exe -iwad tnt.wad -file "DV-DS-ComboPack-master" exit" 
 
 - Running - Alternative-1a. If you don't want to use a command line, the best recommendation is to get "ZDoom Executor" (@ http://zdexe.sourceforge.net/ ), as unlike "ZDL", you can check off folders in a list instead of being forced to enter folders as part of ZDL's commandline. Make sure to set up your intended GZDoom version and game modes to play. Use the 1-10 tabs for multiple setups, which can also be saved as external files.
 
 - Running - Alternative-1b. If using ZDoom Executor, you will want to add the "DV-DS-ComboPack-master" folder to the "External Files" window, and check it off. If you get "DV-DS-iDTech1" as well, you want to add the game folder inside of that folder for the game you're planning to play [i.e. the "Heretic" subfolder for playing Heretic] and check that folder off as well. If you get "DV-DS-CompatPacks" as well, you want to make sure to load the proper subfolder for whatever mapset you plan to play. Most are self contained and don't require extra files [i.e. "Epic2" is all of the mapset and its resources, so you don't need epic2.wad as well, etc].
 
  - First Steps [In Game]:
  Make sure to set up specfic binds before you start the game for the first time.
  1. Binds > Actions > "Weapon Zoom" [Used for "Focus" and "Spell Alternates"]
  2. Binds > Actions > "Run" [Used for "Focus", "Tension/Psyche-Up" and "Quickspell Assign"]
  3. Set up all necessary "Inventory" related binds.
  4. Set binds for all Aetherius related binds below.
