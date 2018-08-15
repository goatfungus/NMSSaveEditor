# Change Log

## 1.5.16 - Update (15 August 2018)

- Added Repair All Slots / Technology menu item.
- Added more logging messages to debug output.
- Updated file saving method to use the same filename instead of switching between auto/manual saves.
- Added detection for when the game updates a save file while it is open for editing, includes an auto-load feature.

## 1.5.15 - Update (10 August 2018)

- Updated items list for NMS 1.55
- Fixed issue where procedural tech could not be moved to technology-only inventory.
- Added an auto-update process via the launcher executables.

## 1.5.14 - Update (8 August 2018)

- Added procedural products to the items list.
- Added ability to add procedural generated Tech / Products through the Add Item dialog.
- Fixed an issue where only the first 4 or 5 bases were showing in the base dropdown list.

**PLEASE NOTE:**

- Procedurally generated names for technology / products still do not show in the editor as I haven't worked out the algorithm.

## 1.5.13 - Update (6 August 2018)

- Added Atlas language to known words list.
- Updated broken slot repair to handle salvaged ships in NEXT.

## 1.5.12 - Update (5 August 2018)

- Rolled back change to so-called "improved" font scaling, as it didn't work properly.
- Added "InventoryFontScale" value to config file to allow text on inventory items to be scaled up or down. Default is 0.75.
- Updated "Use Old Models" to "Use Old Colours" in ships tab, as it only seems to affect colours.
- Fixed Change Stack Size button to take into account item multipliers.
- Increased maximum health to 200, as various shield tech increased maximum health beyond the previous maximum (100).

## 1.5.11 - Update (4 August 2018)

- Added checkbox to allow ships to use old (pre-NEXT) models.
- Improved font scaling, so editor should look he same regardless of O/S scaling.
- Fixed stack size issues for various items (eg: Projectile Ammunition) which affected the Add Item, Move Item, and Change Stack Size functions.

## 1.5.10 - Update (3 August 2018)

- Updated data from game files (NMS 1.53).
- Added double click handling to Item Move dialog.
- Added "On Mission" status indicator to frigates view.
- Updated delete function so that it should no longer break missions in progress.
- Added ability to change Galaxy using Coordinate Viewer.
- Added new executables to increase memory available to the editor (with -4G suffix) for those who are encountering out of memory errors.

## 1.5.9 - Update (1 August 2018)

- Fixed issue where incorrect tabs were being enabled/disabled after editing raw JSON.
- Added the ability to modify item quantity and procedural id through the item viewer.
- Added the ability to repair damaged frigates.
- Added an Unlearn All button for learned words.

## 1.5.8 - Update (31 July 2018)

- Changed Known Words Learn All function to only learn the words that are actually used by each race.
- Fixed issue where edits made to Frigate stats don't save when you select the next frigate.
- Updated the frigate trait list to show which traits are beneficial or not in the dropdowns.
- Removed formatting from item descriptions in the item viewer.
- Fixed issue where primary trait was not being updated on frigate type change.

## 1.5.7 - Update (30 July 2018)

- Updated frigate management to filter traits based on frigate type.
- Set limit on number of frigates to 30 (this is the in-game limit).
- Changed Copy button to create frigates with new random seed value and no name.

## 1.5.6 - Update (30 July 2018)

- Added ability to manage frigates and their stats.
- Added home system seed field to freighters.

## 1.5.5 - Update (29 July 2018)

- Added a save file recovery feature for saves that are corrupted in-game.
- Added a check to ensure that an invalid ship index produced by the game doesn't impact the editor.

## 1.5.4 - Update (28 July 2018)

- Added Delete Ship button (BE CAREFUL!).
- Updated item viewer to show the correct ID for procedural technology.
- Updated the planetary base backup/restore function to support NEXT bases.

**PLEASE NOTE:**

- Players who previously backed up their bases pre-NEXT should be able to restore their bases from file (choose "All" in the file selection dialog). This will automatically create a new main room structure, a teleporter, a doorway/ramp, and a few windows where things used to be in your old base.
- The base restore function does not support terrain modifications (yet), so there is still an issue where terrain can bleed through the floor, especially with bases built underground.

## 1.5.3 - Update (27 July 2018)

- Updated for NMS 1.51.
- Updated the items database and fixed item categories.
- Updated NPC races list to detect new models.
- Added base selection box to the Base Information tab, to allow users to view all bases, not just the first one.

## 1.5.2 - Update (26 July 2018)

- Updated exosuit and ship health to new max levels (was changed in NEXT).
- Temporarily removed freighter NPCs from editor.

## 1.5.1 - Update (26 July 2018)

- Added procedural technology to the items list (tech bought from vendors and installed).
- Temporarily disabled the base backup/restore functionality (work in progress).


## 1.5.0 - First release for NEXT

- Updated items database for No Man's Sky 1.5 (NEXT).
- Added Nanites and Quicksilver fields to Exosuit tab.
