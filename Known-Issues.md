# Known Issues

Issue: Long load/startup times.

Loading to the main menu will take some time (expect to measure in minutes). Load time performance improvements is a long term goal.

Issue: Cluttered crafting menu.

Please make use of SkyUI's sorting/filtering options (top right of the crafting menu).

Issue: Sometimes NPCs are missing their clothes when I load into an area.

Open console -> Click the NPC -> toggle them using "disable" and then "enable" commands. If that doesn't work, try using the "resetinventory" command (WARNING: be VERY careful using resetinventory on followers or other NPCs if you have given them stuff to hold).

Issue: Neck seams or strange looking characters during character creation.

Make sure to select a high poly head under face part options. If you are using a preset, check the sculpt tab in RaceMenu to see if the preset has a head morph preset.

Issue: Holes or seams in the landscape.

There are likely a few. I may have made a mistake in the load order and/or something needs a patch. If you find one, please report a bug with a screenshot and location.

Issue: Too much grass.

No plans to patch any grass. You might see improvements over time as the load order changes.

Issue: My follower thinks we're married.

If you are seeing innapropriate dialogue options for a follower (you see spouse dialogue when you are not married, for example), use the console to manually modify the relationship rank (see: setrelationshiprank https://en.uesp.net/wiki/Skyrim:Console).

Issue: There are soft incompatabilities between followers that have dialogue/reactions to main quests and mods that modify the main quests.

No plans to address these.

Issue: I am stuck in an animation while interacting something (e.g. looting a chest)

If you are stuck because of the QuickLoot menu (https://www.nexusmods.com/skyrimspecialedition/mods/21085), simply move the camera away from the object so the menu closes. If you are stuck for another reason, open the console -> click on your character -> type "pushactoraway 14 1".

Issue: My dodge button isn't working and/or some menu controls don't appear to be working correctly.

Be sure to disconnect your gamepad during play. Gamepad is not fully supported.

Issue: Bruma road textures don't integrate well with landscape.

I will try to address this at some point.

CTD related to character skeletons.

These crashes happen occasionally and I don't believe they can be reliably reproduced. Crash logs and feedback on this are appreciated.

Issue: There are spell and perks that are incompatible with Experience (i.e. a perk that gives +10% experience with one-handed weapons)

If possible, avoid these spells/perks for now. I have not decided what to do with them yet.

Issue: Better Vampire's night eye not working correctly