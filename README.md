# skyrim-gmoh
A Wabbajak modlist for Skyrim SE

# Brief

- This is the beta version of a Wabbajak modlist for Skyrim SE. If you are new to Wabbajack, Mod Organizer 2 (MO2) or Skyrim modding, I recommend starting with an official Wabbajak modlist (https://www.wabbajack.org).

- This list has 3 goals:

    1. Completely overhaul Skyrim. This includes, but is not limited to, the landscape, UI and core gameplay systems.
    2. Give your Dragonborn character more roleplay choices. 
    3. Build a comprehensive modlist that players can use to start modding Skyrim to their tastes.

- Gameplay balance is a far-flung goal of this list. Curently, you will likely feel slightly underpowered at lower levels and overpowered at higher levels.

# Requirements

 - The Steam version of Skyrim: Special Edition. Only English is supported.
 - Anniversary Edition Content (https://store.steampowered.com/app/1746860/The_Elder_Scrolls_V_Skyrim_Anniversary_Upgrade).
 - C++ Redistributable for VS2019 (https://aka.ms/vs/17/release/vc_redist.x64.exe).
 - 1 Terabyte of storage (preferably SSD). This can be distributed across 2 drives.
 - For a stable experience, at least 16GB of RAM and 12GB of VRAM.

# Disclaimer

- Please do not report bugs/issues to individual mod authors. Issues must be reported through the support channels provided {anchor bug report instructions}.
- The list is in beta. You may experience breaking issues during installation or during gameplay.
- This is not a performance friendly list. Expect framerate drops in busy areas.
- With ~2700 mods, expect the installation process to take significant time and bandwidth. 

# Complete Modlist: {Load order library link here}

# Modlist Breakdown

# Gameplay
- Attack & Dodge (MCO|DXP)
- Valhalla Combat
- For Honor in Skyrim
- Vokriinator - Choice Cuts
- Experience and Missives
- Shadows of Skyrim

# Vanilla Questing
- Realm of Lorkhan
- Humble Beginnings
- At Your Own Pace
- BUVARP RE
- More to Say
- Many of the vanilla quest expansions by JaySerpa

# New Quests and Companions
- Beyond Skyrim: Bruma
- Vigilant
- 3DNPC
- EZPG
- Hammet's Dungeons and New Vominheim
- Remiel
- The Wheel of Time
- Katana - Journey in the Shadows
- Song of the Green (Auri)
- Serana Dialogue Addon

# Skyrim Overhauled
- JK's Skyrim
- Northern Roads and Cities of the North
- The great cities, towns and villages series
- Many of the amazing towns and villages by Schlitzohr
- Majestic Mountains Parallax
- Majestic Landscapes Parallax
- Veydosebrom Regions
- Traverse the Ulvenwald
- NAT III
- Rudy ENB for NAT III

# Installation

- Verify the integrity of your Skyrim installation (https://help.steampowered.com/en/faqs/view/0C48-FCBD-DA71-93EB).

# Wabbajak Installation & Configuration

- Download wabbajak.exe from the official Wabbajak site (www.wabbajak.org).
- Download the latest Wabbajak .meta file for GMOH from https://www.nexusmods.com/skyrimspecialedition/mods/106393.
- Create a new folder for Wabbajak close to the root of your drive (e.g. c:\wabbajak). Do not create this folder in a UAC protected folder (e.g. Program Files or My Games). 
- Move wabbajak.exe into the new folder.
- Run the executable and wait for it to update. 
- Select "Install from Disk".
- Configuring your file paths:

    "Target Modlist"
    
    This will be the path to the .meta file you downloaded in the previous step.

    "Installation Location"
    
    This folder will contain the portable Mod Organizer 2 instance.
    *This folder must be located on the same drive as your Skyrim installation.
    *Like the Wabbajak folder, it must created outside of a UAC protected folder.
    
    An example of a good location: "c:\gmoh"

    "Download Location"

    This folder will contain all of the downloaded archive files required for the installation process. By default, it will be placed in the Mod Organizer 2 folder. If storage space is a concern, it is okay to create this folder on a separate drive.

- Click the play button to start the process.

# New game and In-game configuration

- Unplug your gamepad while playing. Leaving it plugged in can lead to UI/gameplay issues.  Gamepad is not fully supported yet.
- After creating your character, you will find yourself in the realm of Lorkhan. If you would like, explore the area and find ways to further customize your character. You can always come back later (use the "Teleport to Realm of Lorkhan" power).
- Interact with the purple shards to leave Lorkhan.
- Most mod configuration steps have already been made through INI files (see the "Mod Config" separator in MO2).
- You will need to manually activate Shadows of Skyrim in the MCM if you want to use it. If you become a lich or are using some other item/perk that provides it's own death alternative, deactivate Shadows of Skyrim in the MCM.

# Controls

Movement/Combat:

Attack/Draw Weapon:         Left Mouse Button                       Skyrim
Block/Attack with Left:     Right Mouse Button                      Skyrim
Heavy Attack:               Middle Mouse Button                     One Click Power Attack (MCM)
Execution Attack*:          Middle Mouse Button on stunned enemies  Valhalla Combat (MCM)
Dual Wield Block Key:       V                                       
Dodge:                      C (double tap for long dodge)           Dodge Framework (MCM)
Sprint:                     Mouse Button 5                          Skyrim
Auto-Move:                  Mouse Button 4                          Skyrim
Sneak:                      Left Ctrl                               Skyrim
Walk/Run Toggle:            Left Shift                              Skyrim
Jump:                       Space                                   Skyrim
Target Enemy:               G                                       True Directional Movement (MCM)
Swap Targets:               (With enemy targeted) Move the camera to swap targets True Directional Movement (MCM)
Camera Shoulder Swap:       K                                       SmoothCam (MCM)
Health Potion:              X                                       Hotkey Potions (MCM)

*Please see the Valhalla Combat mod page to learn more about stamina, parry and stun/execution systems. https://www.nexusmods.com/skyrimspecialedition/mods/64741 

Horse Controls:

Mount:                      E
Dismount:                   Hold E
Wait/Follow:                H
Open Inventory:             H while targeting the horse
Pet:                        Left Shift+E

Additional Controls:

Pet dog:                    Left Shift+E
Pickup animal carcass:      Left Shift+R

# Known issues

https://github.com/postk-dev/skyrim-gmoh/blob/main/Known-Issues.md

# Reporting a bug | CTD

 - I will be unable to provide support if you have made modifications to any part of the list.
 - Please refer to known issues before reporting a bug.
 - Please report bugs on the Discord.
 - When reporting a crash to desktop (CTD), it must be reasonable to reproduce and include a log file. If the report does not meet this requirement, it will likely be ignored. Your crash logs can be found in the user folder "Documents\My Games\Skyrim Special Edition\SKSE". It should look like this: "crash-[datetime of crash].log". Please do not copy paste text from the log file into a report, just attach the file.

# Help, Tips and FAQ

Skyrim's engine has some documented (https://www.youtube.com/watch?v=PJPzMAXSprU) issues with reloading during play. Consider relaunching the game instead of reloading a save. If you are dying alot, consider enabling Shadows of Skyrim.

Avoid saving during combat as there tends to be more scripts running at that time. This can help alleviate save corruption.

Q: I lost my follower. How can I find them again?
A: If they are imported into Nether's follower framework, you should be able to teleport them to you from the Follower Framework MCM. If they are exempt from the framework (for example: Auri, Serana or Lucien), they will typically have a follower tracker quest or a spell to summon them to you. Failing that, lookup the NPC reference ID on UESP (https://en.uesp.net/wiki/Skyrim:People) or use Google, open the game console -> "prid {referenceId}" -> "moveto player". Keep in mind there are some quests/areas that deliberately seperate you from your followers.

Q: I am stuck on a quest. How do I progress?
A: At Your Own Pace (https://www.nexusmods.com/skyrimspecialedition/mods/52704) makes modifications to many of the main quest lines in Skyrim. Check the mod page for info on how you can progress. Failing that, ask in the Discord.

Q: I hit an enemy and my stamina bar went up? What?
A: Check out the Valhalla Combat mod page https://www.nexusmods.com/skyrimspecialedition/mods/64741 to understand how the combat system has changed.

Q: Where are the screenshots I took in photo mode?
A: You can find the .png files in the stock game folder. There is also .dds texture files located in the overwrite folder (located at the very bottom of the modlist in Mod Organizer).

Q: How do I carry an animal carcass using Simple Hunting Overhaul?
A: Shift + R.

Q: How do I reload the original Immersive Equipment Display preset that came with the list?
A: Open IED (shift + F1) -> File tab (top left) -> Default Config -> Import.

Q: The physics on this hair and/or outfit is acting strange. How do I fix it?
A: Open the console -> type "smp reset"

Q: Wtf is GMOH?
A: Giga modlist (of hell).

