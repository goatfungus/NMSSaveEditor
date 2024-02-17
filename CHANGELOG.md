# Change Log

## 1.15.2 - Update (17 February 2024)

- Added new freighter, multitool, and ship types for Omega.

## 1.15.1 - Update (17 February 2024)

- Added expedition context for save files.

## 1.15.0 - Update (17 February 2024)

- Updated name mappings for NMS 4.51 (Omega).
- Added new season rewards, items, etc.
- Updated to new save file format.

## 1.14.4 - Update (01 September 2023)

- Updated items list.
- Fixed issues with known words section.
- Fixed issues with file paths.

## 1.14.3 - Update (26 August 2023)

- Updated name mappings for NMS 4.40 (Echoes).
- Added new Autophage language to discovery tab.
- Added new Multitool types (Staff, etc).
- Added new season rewards, items, etc.

## 1.14.2 - Update (5 June 2023)

- Improved settlement listing to show only settlements with teleport endpoints.
- Updated settlement perks to allow any number of perks (determined by save file).
- Fixed issue where non-technology items were showing up as broken due to damage factor.
- Fixed highlight color in JSON editor so that it works in dark mode.
- Updated UI colors for positive and negative traits / perks.
- Updated coordinate viewer to allow any first glyph (warp still only goes to space).
- Updated mappings for NMS 4.26
- Removed buildable parts from add item dialog.

## 1.14.1 - Update (5 May 2023)

- Updated logging functionality

## 1.14.0 - Update (4 May 2023)

- Full overhaul of the editor UI, using selectable Look & Feel options (including Dark mode)

## 1.13.10 - Update (3 May 2023)

- Updated techbox icons and text
- Fixed potential issue with icons on discovery tab

## 1.13.9 - Update (1 May 2023)

- Improved Add Item dialog search feature
- Implemented archived technology packages properly in UI
- Removed unused inventory containers from UI
- Updated Move Item dialog to show names of multitool/ship where possible
- Fixed issue with sorters on discovery tab

## 1.13.8 - Update (29 April 2023)

- Another fix for the issue with \uFFFF encodings in JSON Editor (hopefully the last)

## 1.13.7 - Update (28 April 2023)

- Fixed issue with \uFFFF encodings in JSON Editor
- Changed Archived Techs to show encoded product IDs instead of raw data

## 1.13.6 - Update (25 April 2023)

- Updated name mapper to support files that are incorrectly mapped (PS4 Save Wizard)

## 1.13.5 - Update (25 April 2023)

- Fixed issues with JSON Editor

## 1.13.4 - Update (25 April 2023)

- Improved delete/import functionality for multitool/ship/companion lists
- Added missing techboxes and companion eggs to item lists
- Updated stack size rules to match game files
- Tweaked PS4-SaveWizard format to allow for name mappings (if available)

## 1.13.3 - Update (24 April 2023)

- Added base storage container names
- Fixed issues with multitool updates / deletions
- Added support for extended JS string formats in import/export
- Reduced the number of property change events caused by array changes
- Fixed NPE in steam storage

## 1.13.2 - Update (24 April 2023)

- Fixed array removal issue (affecting supercharge, data imports, and account unlocks)

## 1.13.1 - Update (23 April 2023)

- Fixed "invalid token" issue caused by mixed character encodings
- Changed JSON Editor to start from first tree node (PlayerStateData / UserSettingsData)

## 1.13.0 - Update (23 April 2023)

- Overhaul of JSON reader/writer functionality to improve support for unicode
- Improved responsiveness of all file open/save dialogs
- Added missing name mappings
- Added save name / description fields to main UI
- Fixed issue where consumable products were defaulting to stack size 1
- Added platform rewards to Account tab
- Changed NMSSaveEditor.conf format to JSON

## 1.12.0 - Update (9 April 2023)

- Overhaul of export/import functionality for freighters to include more details and inventory data
- Added Horizon Vector NX ship type
- Added Product/Substance export checkbox to ship/freighter backup dialogs

## 1.11.9 - Update (8 April 2023)

- Added maneuverability stat for all ship types
- Updated bases list to include newer base versions
- Re-enabled backup/restore function for bases / freighter bases
- Updated inventory stack sizes to reflect the real container settings

## 1.11.8 - Update (8 April 2023)

- Added Golden Vector and Utopia Speeder to ship types

## 1.11.7 - Update (8 April 2023)

- Added supercharge all slots context menu item
- Added supercharge feature for suit tech inventory
- Fixed potential bug with multitool indexing, blocking saves

## 1.11.6 - Update (7 April 2023)

- Updated name mappings for NMS 4.2 (Interceptor).
- Added new items
- Added new sentinel ship type
- Added missing creature types (spider quads & mini robo)
- Added supercharge feature for tech inventories
- Added sentinel and switch multitools

## 1.11.5 - Update (25 February 2023)

- Updated name mappings for NMS 4.1 (Fractal).

## 1.11.4 - Update (24 February 2023)

- Added new items.

## 1.11.3 - Update (7 December 2022)

- Added new items.

## 1.11.2 - Update (10 October 2022)

- Increased technology inventory sizes for Suit/Ship/Freighter to 10x6.
- Added fix for corrupted account data files.
- Implemented more fixes for save format including metadata.

## 1.11.1 - Update (9 October 2022)

- Added Relaxed and Custom game modes.

## 1.11.0 - Update (9 October 2022)

- Updated name mappings and items for NMS 4.03 (Waypoint).
- Updated inventory structures for Waypoint saves.
- Removed change stack sizes button (test mode).
- Implemented numerous fixes for new save format.

## 1.10.7 - Update (27 July 2022)

- Added missing LandJellyFish and SpaceFloater creature types.

## 1.10.6 - Update (25 July 2022)

- Fixed issue with Living (DeepSpaceCommon) frigates.
- Fixed issue with bases not showing up after update.

## 1.10.5 - Update (22 July 2022)

- Split savegame and account name mapping lists due to conflicts.
- Updated name mappings and items for NMS 3.94 (Endurance).
- Added new living frigate types and fixed a few issues in trait setup.
- Added Freighter Cargo inventory.

## 1.10.4 - Update (1 July 2022)

- Added Leviathan frigate to list of frigate types.

## 1.10.3 - Update (1 July 2022)

- Updated name mappings for NMS 3.91

## 1.10.2 - Update (27 May 2022)

- Updated name mappings and items for NMS 3.90 (Leviathan)

## 1.10.1 - Update (21 April 2022)

- Added Squadron tab with the ability to modify the wingman data.
- Updated name mappings

## 1.10.0 - Update (19 April 2022)

- Updated items list and name mappings for NMS 3.85 (Outlaws)
- Added new Cargo inventory for ships (named "Inflated Sacs" in living ship).
- Added new ship type: Solar.

## 1.9.10 - Update (9 March 2022)

- Added new FontScaling setting in the NMSSaveEditor.conf file for more control over editor font sizes.
- Updated items list and name mappings for NMS 3.84
- Fixed bug in multitool type detection for older saves.

## 1.9.9 - Update (25 February 2022)

- Added new multitool Type field (Standard/Royal)
- Updated name mappings

## 1.9.8 - Update (19 February 2022)

- Updated items list and name mappings for NMS version 3.8 (Sentinel)

## 1.9.7 - Update (31 October 2021)

- Updated name mappings for Expedition 4.
- Added new zip archive for when self-extracting exe is blocked by anti-virus.

## 1.9.6 - Update (21 October 2021)

- Updated items for Expedition 4.

## 1.9.5 - Update (29 September 2021)

- Added support for PS4 Save Wizard storage.
- Added Settlements tab with UI for production.

## 1.9.3 - Update (24 September 2021)

- Fixed bug with save reloading when game is running.
- Added Fleet Coordination stat to freighters.
- Updated name mappings.

## 1.9.2 - Update (23 September 2021)

- Fixed stack sizes for Expedition saves.
- Added more robust detection of invalid saves.

## 1.9.1 - Update (22 September 2021)

- Major overhaul of storage system, which should improve performance and allow the addition of other storage types.
- Added support for MS Game Pass saves.
- Updated frigates tab, and linked stats & traits.
- Increased ship technology max size to 8x6.
- Added ability to add freighter technology to the general slots.

## 1.8.7 - Update (11 September 2021)

- Fixed bug in multitool list, caused by my own haste to get the last few fixes out!
- Updated README.md and screenshots.

## 1.8.6 - Update (11 September 2021)

- Fixed bug in account tab, caused by my own haste to get the last few fixes out!

## 1.8.5 - Update (11 September 2021)

- Fixed bug in companion seed values.

## 1.8.4 - Update (11 September 2021)

- Fixed issue where discovery tab was not loading correctly.
- Fixed issue where some very old saves could not be loaded at all.
- Updated name mappings.

## 1.8.3 - Update (10 September 2021)

- Added creatures to save editor UI.

## 1.8.2 - Update (08 September 2021)

- Added ability to modify account data & unlocks.

## 1.8.1 - Update (07 September 2021)

- Fixed issue where base data wasn't showing up.

## 1.8.0 - Update (06 September 2021)

- Updated items list and name mappings for NMS version 3.6 (Frontiers)
- Added ability to read compressed save files
- Expanded number of save file slots from 5 to 15

## 1.7.7 - Update (03 June 2021)

- Updated items list and name mappings for NMS version 3.5 (Prisms)

## 1.7.6 - Update (26 May 2021)

- Updated items list for NMS version 3.42 (Beachhead)
- Added Normandy frigate type.

## 1.7.5 - Update (6 April 2021)

- Added Expedition game mode to editor.
- Updated name mappings for Expedition save file.

## 1.7.4 - Update (6 April 2021)

- Updated items list and name mappings for NMS version 3.3 (Expeditions)

## 1.7.3 - Update (10 March 2021)

- Updated items list and name mappings for NMS version 3.2 (Companions)
- Added the ability to Export/Import the save file data in JSON format (edit with your preferred text editor)

## 1.7.2 - Update (02 February 2021)

- Updated items list and name mappings for NMS version 3.1 (Next Generation)

## 1.7.1 - Update (28 September 2020)

- Added missing technologies that apply to all ships/vehicles.
- Fixed issue where vehicles tab was no longer accessible on some saves.

## 1.7.0 - Update (27 September 2020)

- Updated items list and name mappings for NMS version 3.0.

## 1.6.14 - Update (7 August 2020)

- Updated items list and name mappings for NMS version 2.61.
- Added missing procedural freighter tech.

## 1.6.13 - Update (19 July 2020)

- Updated items list and name mappings for NMS version 2.6 (Desolation).
- Added support for procedural freighter tech.

## 1.6.12 - Update (12 April 2020)

- Updated items list and name mappings for NMS version 2.41 (Exo Mech).
- Added support for minotaur exo mech.

## 1.6.11 - Update (26 February 2020)

- Fixed issue when changing a ship type involving living ships.
- Added 3 missing procedural products added in the Living Ship update.

## 1.6.10 - Update (23 February 2020)

- Added the ability to import/export ships and multitools.
- Fixed issue where normal ship technologies were not displaying in Add Item dialog.

## 1.6.9 - Update (22 February 2020)

- Updated items list and name mappings for NMS version 2.31 (Living Ship).
- Added support for living ships.

## 1.6.8 - Update (2 December 2019)

- Updated items list and name mappings for NMS version 2.2 (Synthesis).
- Added support for additional multitools.
- Internal improvements to the saved file structure.

## 1.6.7 - Update (17 November 2019)

- Updated items list for NMS version 2.13.
- Updated name mappings to include a few more missing items.
- Updated type and strength indicator for frigate traits to show real in-game values.
- Added last save date/time to save slot dropdown.

## 1.6.6 - Update (6 October 2019)

- Updated name mappings to include a few more missing items.
- Added type and strength indicator to frigate traits.
- Updated items list for current Experimental branch.

## 1.6.5 - Update (30 August 2019)

- Updated name mappings to include a few more missing items.
- Added ingredient-only restriction to Ingredient Storage container.

## 1.6.4 - Update (25 August 2019)

- Added Ingredient Storage to base chests list.
- Fixed minor issue when repairing new technologies.

## 1.6.3 - Update (24 August 2019)

- Updated items database for NMS 1.09.
- Fixed NullPointerException in inventory panel that affected some users.
- Fixed issue where partially-built technology was being reset when moved to another inventory (ie: ships).

## 1.6.2 - Update (21 August 2019)

- Fixed issue with bases not showing up.
- Updated name mappings to include new base info fields.

## 1.6.1 - Update (18 August 2019)

- Updated words discovery UI for changes made in BEYOND.
- Disabled change stack size feature, as it is no longer possible to do this due to in-game restrictions.
- Updated procedural products in the items database.

## 1.6.0 - First release for BEYOND

- Updated items database for No Man's Sky 2.0 (BEYOND).
- Increased default stack size for substances in creative/normal saves.
