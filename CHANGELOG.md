# Change Log

## 1.3.31 - Update (16 Jul 2018)

- Added editable name field for planetary bases.
- Fixed a few minor issues in base backup/restore functions.

## 1.3.30 - Update (16 Jul 2018)

- Implemented planet / freighter base backup/restore functions.
  This allows you to easily restore your preferred base layout to another planet or freighter, including bases from other game modes (ie: Creative).
  1. In the editor, click the backup button to backup your current base structure to a file.
  2. In the game itself, find a new base location, claim it, save, then exit to mode select.
  3. Reopen the editor and click the restore button to restore from a file.
  4. Reload your save in game, and voila!

## 1.3.29 - Update (6 Jul 2018)

- Increased the cap for units to match in-game maximum (~4 billion).
- Updated the maximum units stat to reflect any changes made in units.
- Added better detection for corrupted saves (instead of crashing).

**PLEASE NOTE:**

- Units over ~2 billion are saved in the file as a negative value (in both the game and save editor), so this may look a little strange when viewing the raw JSON.
- The maximum units stat only goes up to ~2 billion, so the editor will cap the stat at this value.

## 1.3.28 - Update

- Added automatic update for the version number when saving an old save file to a new slot.
- Added more support for modded save files.

## 1.3.27 - Update

- Added ability to reduce stack size, providing it doesn't clash with existing stacks.
- Added "Save As" function, to allow saving to other slots.

## 1.3.26 - Update

- Further tweaks for save file changes introduced in NMS 1.38 (Experimental), works with Oct 2 release.

## 1.3.25 - Update

- Further tweaks for save file changes introduced in NMS 1.38 (Experimental).

## 1.3.24 - Update

- Updated editor to support save file changes introduced in NMS 1.38 (Experimental).

## 1.3.23 - Update

- Fixed bug where seed value was not saving correctly on shorter seeds (0x01, etc).
- Fixed bug where editor was not saving a field value when using CTRL-S.

## 1.3.22 - Update

- Added ability to view glyph and galactic coordinates using "Coordinate Viewer" menu item.
- Added ability to warp to other systems (in ship) with the new coordinate viewer.

## 1.3.21 - Update

- Added check to allow breaking of slots ONLY on inventories that are valid (ship & multitool).
- Fixed issue where grenade launcher and boltcaster were not being recharged using the "Recharge All" feature.
- Fixed issue with permadeath saves introduced in 1.3.20.

## 1.3.20 - Update

- Added ability to "Break" inventory slots (right-click menu), for those who like to make things more difficult for themselves!
- Fixed issue where moving items could result in the items landing on "Broken" slots. Now they can only be moved to fully usable slots.
- Added "Build Cost" field to Item viewer dialog.
- Added compression for backup files, and changed the save process to target the oldest file name (same as in-game save process).

## 1.3.19 - Update

- Added "Recharge Base Planters" menu item.
  NOTE: This will only recharge the planters that have been recharged once before, solution to this is in progress.
- Updated for NMS 1.35.

## 1.3.18 - Update

- Added Ship Health field (only editable for primary ship).
- Improved data checks in JSON editor, with better error messaging.
  You can now delete the contents of a selected block, and it will delete it rather than trying to set it to no value.
- Added "Milestones / Reputation" tab.
- Added steamid lookup for directory names.

## 1.3.17 - Update

- Improved Find dialog in JSON Editor (CTRL-F).
- Added IDs to the lists in the Discovery tab.
- Updated various font sizes to be more consistent with operating system settings.

## 1.3.16 - Update

- Reformatted all images to reduce the overall download size (now 30% what it was).
- Added "Change Stack Sizes" button to inventory view.
- Added ability to merge stacks of the same item together using drag & drop.
- Added icons to known technology / products lists.

## 1.3.15 - Update

- Added "Expand All Inventories" and "Enable All Slots" functions to the Edit menu.
- Added tooltip for inventory items on mouse over (displaying full name of item).
- Added new sidebar to JSON editor.
- Added ESC hotkey to close common dialogs.
- Updated datafiles for NMS 1.33 release (changes to known words list).

## 1.3.14 - Update

- Updated all remaining inventory containers to use 8x6 maximum size.
- Renamed some of the Substance categories to match in-game values.
- Added categories and sorting functionality to "Discovery" boxes.
- Added "Rechange All Technology" and "Refill All Stacks" functions to the Edit menu.
- Added CTRL-drag feature for duplicating items in inventory.

## 1.3.13 - Update

- Added Known Words section to "Discovery" tab (renamed from "Technology").
- Increased limits on multitool inventory size to 8x6.
- Fixed display issue in Add Item dialog.
- Changed stat save process to add the stats in if the ID doesn't exist (should fix issue with freighters pre-1.3).

## 1.3.12 - Update

- Visual improvements to many of the editor dialogs.
- Added debugging option to startup, along with new .bat file. This option causes the editor to dump all output to a file "debug.log".
  This file can be used to report problems with the editor.

## 1.3.11 - Update

- Fixed issue where freighter stat was not being saved properly on freighters bought prior to NMS 1.3.

## 1.3.10 - Update

- Changed the File Open dialog to be more intuitive. This now lets you see your save files and select them individually.

## 1.3.9 - Update

- Added buttons for random seed generation.
- Added freighter NPC race and seed values.
- Added base NPC seed values (hired NPCs only).
- Fixed issue with Freighter stats not being copied to all locations in the save.

## 1.3.8 - Update

- Added fix for multiple menuitems attached to same shortcut key.
- Added debugging for when the editor "flashes" an error message and won't start up.

## 1.3.7 - Update

- Minor adjustments to the UI (inventory selection and expansion buttons).
- Increased the max size of tech inventory on suit, ships, and freighters to 8x6.
- Added Fill/Recharge menu item to context menu, and removed the amount from the Item Viewer dialog.
- Added ability to revert to old saves using the Filename dropdown (sorted in most recent order).

## 1.3.6 - Update

- Added Portal Glyphs to Technology tab.
- Fixed bug in JSON Editor window when closing.

## 1.3.5 - Update

- Added the ability to add/delete items from inventory.
- Added the ability to expand the width and height on certain types of inventory.
- Fixed issue with unexpected number formats in save file causing read errors (possibly due to other mods).
- Changed "Show JSON" menu item to "Edit Raw JSON", and made the dialog editable (be careful when using this!).
- Added icons for inventory items.

## 1.3.4 - Update

- Removed add all function from technology and products list, and replaced with a single/multi selection dialog to give more control. Also added a removal button to each list.
- Added the ability to move items into other inventory containers (with some restrictions), using right-click menu. Items are restacked as needed.
- Fixed issue with Exotic Ships reverting to Shuttle when opening a save.

## 1.3.3 - Update

- Fixed bug where "ghost freighters" were being added to save files where a freighter hadn't been bought yet.
- Added ability for app to remember last save directory on startup.
- Added class and stats to freighters.

## 1.3.2 - Update

- Increased the maximum for multitool and ship stats.
- Added freighter types (be careful changing this if you are currently in your freighter).
- Added ability to add all technology and products to the known lists.

## 1.3.1 - Update

- Fix for inventory out of bounds on some save game files.
- Added ability to edit health, shield, and energy of the player.
- Added ability to edit class and base stats of the multitool.
- Added ability to edit type, class, and base stats of ships.

## 1.3 - First public release

- Support for No Man's Sky 1.3 (Atlas Rises).
