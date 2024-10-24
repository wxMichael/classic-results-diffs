crash-2024-08-28-16-56-30 kushy58.log -> AUTOSCAN REPORT GENERATED BY CLASSIC v7.30.3 
# FOR BEST VIEWING EXPERIENCE OPEN THIS FILE IN NOTEPAD++ OR SIMILAR # 
# PLEASE READ EVERYTHING CAREFULLY AND BEWARE OF FALSE POSITIVES # 
====================================================

Main Error: Unhandled exception "EXCEPTION_ACCESS_VIOLATION" at 0x7FF62675FD1E Fallout4.exe+189FD1E

Detected Buffout 4 Version: Buffout 4 v1.28.6 
* You have the latest version of Buffout 4! *

====================================================
CHECKING IF LOG MATCHES ANY KNOWN CRASH SUSPECTS...
====================================================
# Checking for Mesh (NIF) Crash.............. SUSPECT FOUND! > Severity : 4 # 
-----
# Checking for Particle Effects Crash........ SUSPECT FOUND! > Severity : 4 # 
-----
# Checking for Player Character Crash........ SUSPECT FOUND! > Severity : 3 # 
-----
# Checking for Animation / Physics Crash..... SUSPECT FOUND! > Severity : 5 # 
-----
# Checking for *[Save Crash]................. SUSPECT FOUND! > Severity : 1 # 
-----
# Checking for *[Looks Menu Crash]........... SUSPECT FOUND! > Severity : 1 # 
-----
* FOR DETAILED DESCRIPTIONS AND POSSIBLE SOLUTIONS TO ANY ABOVE DETECTED CRASH SUSPECTS *
* SEE: https://docs.google.com/document/d/17FzeIMJ256xE85XdjoPvv_Zi3C5uHeSTQh6wOZugs4c *

====================================================
CHECKING IF NECESSARY FILES/SETTINGS ARE CORRECT...
====================================================
* NOTICE: FCX MODE IS DISABLED. YOU CAN ENABLE IT TO DETECT PROBLEMS IN YOUR MOD & GAME FILES * 
[ FCX Mode can be enabled in the exe or CLASSIC Settings.yaml located in your CLASSIC folder. ] 

# ❌ CAUTION : The Achievements Mod and/or Unlimited Survival Mode is installed, but Achievements is set to TRUE # 
 FIX: Open Buffout 4's TOML file and change Achievements to FALSE, this prevents conflicts with Buffout 4.
-----
✔️ Memory Manager parameter is correctly configured in your Buffout 4 settings! 
-----
# ❌ CAUTION : Looks Menu is installed, but F4EE parameter under [Compatibility] is set to FALSE # 
 FIX: Open Buffout 4's TOML file and change F4EE to TRUE, this prevents bugs and crashes from Looks Menu.
-----
❌ FCX Mode is disabled, skipping game files check... 
-----
====================================================
CHECKING FOR MODS THAT CAN CAUSE FREQUENT CRASHES...
====================================================
[!] FOUND : [FE158] True Nights
    - Has an invalid Image Space Adapter (IMAD) Record that will corrupt your save memory and has to be manually fixed.
    -----
# [!] CAUTION : ANY ABOVE DETECTED MODS HAVE A MUCH HIGHER CHANCE TO CRASH YOUR GAME! #
* YOU CAN DISABLE ANY / ALL OF THEM TEMPORARILY TO CONFIRM THEY CAUSED THIS CRASH. * 

====================================================
CHECKING FOR MODS THAT CONFLICT WITH OTHER MODS...
====================================================
[!] CAUTION : The Fens Sheriff's Department ❌ CONFLICTS WITH : Varied Diamond City Guards
    Both mods heavily modify Diamond City Guards records.
    Use only one of these mods, not both at the same time.
    -----
[!] CAUTION : Soviet Power Armor ❌ CONFLICTS WITH : Open Lexington
    Both mods modify the same location and can cause crashes.
    You can download a compatibility patch here: https://www.nexusmods.com/fallout4/mods/84930
    -----
# [!] CAUTION : FOUND MODS THAT ARE INCOMPATIBLE OR CONFLICT WITH YOUR OTHER MODS # 
* YOU SHOULD CHOOSE WHICH MOD TO KEEP AND DISABLE OR COMPLETELY REMOVE THE OTHER MOD * 

====================================================
CHECKING FOR MODS WITH SOLUTIONS & COMMUNITY PATCHES
====================================================
[!] FOUND : [C3] Beantown Interiors
    - Usually causes fps drops, stuttering, crashing and culling issues in multiple locations.
      Patch Link: https://www.nexusmods.com/fallout4/mods/53894?tab=files
    -----
[!] FOUND : [FE15D] Boston FPS Fix
    - This mod is severely outdated. Either install the PRP patch or switch to PRP entirely.
      Patch Link: https://www.nexusmods.com/fallout4/mods/59021?tab=files
      Better Alternative: https://www.nexusmods.com/fallout4/mods/46403?tab=files
    -----
[!] FOUND : [8A] Functional Displays
    - Frequently causes object model (nif) related crashes and this needs to be manually corrected.
      Advised Fix: Open its Meshes folder and delete everything inside EXCEPT for the Functional Displays folder.
    -----
[!] FOUND : [2A] Looks Menu Customization Compendium
    - If you are getting broken hair colors, install this mod and make sure it loads after LMCC.
      Mod Link: https://www.nexusmods.com/fallout4/mods/18287?tab=files
    -----
[!] FOUND : [7D] Militarized Minutemen
    - Can occasionally crash the game due to a broken mesh on some minutemen outfits.
      Patch Link: https://www.nexusmods.com/fallout4/mods/32369?tab=files
    -----
[!] FOUND : [FE0BD] Natural And Atmospheric Commonwealth
    - If you notice weird looking skin tones with either NAC or NACX, install this patch.
      Patch Link: https://www.nexusmods.com/fallout4/mods/57052?tab=files
    -----
[!] FOUND : [73] Raider Overhaul
    - Old mod that requires several patches to function as intended. Use ONE Version instead.
      Updated ONE Version: https://www.nexusmods.com/fallout4/mods/51658?tab=files
    -----
[!] FOUND : [FE064] Rusty Face Fix
    - Make sure you have the latest 2.0 version installed or try the REDUX Version instead.
      Original Rusty Face Fix: https://www.nexusmods.com/fallout4/mods/31028?tab=files
      Alternative REDUX Version: https://www.nexusmods.com/fallout4/mods/64270?tab=files
    -----
[!] FOUND : [FE0E0] South Of The Sea
    - Very unstable mod that consistently and frequently causes strange problems and crashes.
      Updated Version: https://www.nexusmods.com/fallout4/mods/63152?tab=files
    -----
[!] FOUND : [74] Super Mutant Redux
    - Causes crashes at specific locations or with certain Super Mutant enemies and items.
      Patch Link: https://www.nexusmods.com/fallout4/mods/51353?tab=files
    -----
# [!] CAUTION : FOUND PROBLEMATIC MODS WITH SOLUTIONS AND COMMUNITY PATCHES # 
[Due to limitations, CLASSIC will show warnings for some mods even if fixes or patches are already installed.] 
[To hide these warnings, you can add their plugin names to the CLASSIC Ignore.yaml file. ONE PLUGIN PER LINE.] 

====================================================
CHECKING FOR MODS PATCHED THROUGH OPC INSTALLER...
====================================================
[!] FOUND : [30] Tales from the Commonwealth
[!] FOUND : [32] Settlers Of The Commonwealth
[!] FOUND : [B8] Gunners Plaza Interior
[!] FOUND : [E3] Fourville (Vault 4)
[!] FOUND : [BC] Lost Building of Atlantic
[!] FOUND : [B5] More Xplore
[!] FOUND : [F7] Sector V

* FOR PATCH REPOSITORY THAT PREVENTS CRASHES AND FIXES PROBLEMS IN THESE AND OTHER MODS,* 
* VISIT OPTIMIZATION PATCHES COLLECTION: https://www.nexusmods.com/fallout4/mods/54872 * 

====================================================
CHECKING IF IMPORTANT PATCHES & FIXES ARE INSTALLED
====================================================
✔️ Canary Save File Monitor is installed!

✔️ High FPS Physics Fix is installed!

❌ Previs Repair Pack (PRP) is not installed!
This is a highly recommended mod that can vastly improve performance.
Link: https://www.nexusmods.com/fallout4/mods/46403?tab=files

✔️ Unofficial Fallout 4 Patch is installed!

✔️ Nvidia Weapon Debris Fix is installed!

❌ Nvidia Reflex Support is not installed!
This is a highly recommended mod that can improve performance on Nvidia GPUs.
Link: https://www.nexusmods.com/fallout4/mods/64459?tab=files

====================================================
SCANNING THE LOG FOR SPECIFIC (POSSIBLE) SUSPECTS...
====================================================
# LIST OF (POSSIBLE) PLUGIN SUSPECTS #
- ih_lv_cars_have_loot.esp | 4
- sup_f4se.dll | 1

[Last number counts how many times each Plugin Suspect shows up in the crash log.]
These Plugins were caught by Buffout 4 and some of them might be responsible for this crash.
You can try disabling these plugins and check if the game still crashes, though this method can be unreliable.

# LIST OF (POSSIBLE) FORM ID SUSPECTS #
- Form ID: 000938F3 | [Fallout4.esm] | 1
- Form ID: 000E8DC9 | [Fallout4.esm] | 1
- Form ID: 001AD529 | [Fallout4.esm] | 7
- Form ID: 00205E54 | [Fallout4.esm] | 1
- Form ID: 2000003D | [IH_LV_Cars_Have_loot.esp] | 2
- Form ID: 2000097D | [IH_LV_Cars_Have_loot.esp] | 2

[Last number counts how many times each Form ID shows up in the crash log.]
These Form IDs were caught by Buffout 4 and some of them might be related to this crash.
You can try searching any listed Form IDs in xEdit and see if they lead to relevant records.

# LIST OF DETECTED (NAMED) RECORDS #
- (char*) "FEVHoundBehaviour.hkb/SwapTemplateState" | 1
- Name: "AnimObjectR3" | 1
- Name: "Base01" | 1
- Name: "ElevatorButton01" | 2
- Name: "IronSightsFolded_Lo" | 1
- Name: "ObjectLODRoot" | 1
- Name: "P-Receiver" | 1
- Name: "RArm_Finger51" | 1
- Name: "RArm_Finger52" | 2
- Name: "RArm_Finger53" | 1
- Name: "RArm_Hand" | 1
- Name: "RArm_UpperTwist1" | 1
- Name: "RArm_UpperTwist2_skin" | 1
- Name: "shadow scene node" | 1

[Last number counts how many times each Named Record shows up in the crash log.]
These records were caught by Buffout 4 and some of them might be related to this crash.
Named records should give extra info on involved game objects, record types or mod files.

FOR FULL LIST OF MODS THAT CAUSE PROBLEMS, THEIR ALTERNATIVES AND DETAILED SOLUTIONS
VISIT THE BUFFOUT 4 CRASH ARTICLE: https://www.nexusmods.com/fallout4/articles/3115
===============================================================================
Author/Made By: Poet (guidance.of.grace) | https://discord.gg/DfFYJtt8p4
CONTRIBUTORS | evildarkarchon | kittivelae | AtomicFallout757 | wxMichael
FO4 CLASSIC | https://www.nexusmods.com/fallout4/mods/56255
CLASSIC v7.30.3 | 24.10.11 | END OF AUTOSCAN 
