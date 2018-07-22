# No Man's Sky - Save Editor (for Atlas Rises)

## Introduction

Since No Man's Sky first came out, I was always annoyed that I couldn't just link up my jetpack mods in my exosuit. After many tedious searches, I came across a save editor that allowed me to do just that, but for some reason I couldn't get it to load my permadeath saves. So I decided to rewrite it in Java for fun and as I dug deeper and added more functionality, I think it has become a pretty useful tool.

### Features

- Easy to use UI.
- Ability to organize inventory (exosuit, multitool, ships, freighter, vehicles, and base storage)
  - Move items and technology around (drag & drop, right-click menu)
  - Add items and technology (right-click menu, CTRL-drag & drop)
  - Repair items and slots (right-click menu)
  - Unlock additional slots (right click menu), and resize inventories (to maximum 8x6)
- Ability to change data values, such as number of units, classes, seeds, and base stats, etc.
- Ability to view more information about each of the items in your inventory, such as in-game description, names, etc.
- Ability to edit the known technology, products lists, words, and glyphs.
- Ability to recharge all technologies, refill all item stacks, expand all inventories to 8x6, and enable all inventory slots using a simple menu option.
- Ability to edit the game stats that are used for milestones and faction reputation.
- Ability to edit the raw JSON in the save file (for advanced users only).
- Automatic backup and recovery of all saves (in case you screw up something).
- Backup/Restore of planet / freighter base structures, usable across different systems or saves.

### Screenshots

<img src="screenshots/exosuit.png" width="32%"/> <img src="screenshots/multitool.png" width="32%"/> <img src="screenshots/freighter.png" width="32%"/>
<img src="screenshots/base.png" width="32%"/> <img src="screenshots/discovery.png" width="32%"/> <img src="screenshots/milestones.png" width="32%"/>
<img src="screenshots/jsoneditor.png" width="56%"/> More screenshots can be found [here](screenshots).

## Compatibility

Requirements:
- No Man's Sky - Atlas Rises (PC)
- <a href="https://java.com/en/download/manual.jsp" target="_blank">Java Runtime Environment 8</a>

## Installation

1. Download the [latest version](../../raw/atlasRises/NMSSaveEditor.zip).
2. Extract the contents of the zip file to an empty folder somewhere.
3. Run the bat file (or the jar file if the file extension is associated to java).
4. When the main window opens, locate the folder that your saves are in, and choose the most recent.
5. Start tinkering!
