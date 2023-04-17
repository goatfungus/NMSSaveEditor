# No Man's Sky - Save Editor (for INTERCEPTOR)

## Introduction

Since No Man's Sky first came out, there have been many notable game-breaking bugs as well as many parts of the game that seemed too grindy and not much fun. Some of the bugs had workarounds or later patches to fix them, but others simply stopped your progress. Either way, I just want to enjoy the game!

After many tedious searches trying to find a solution, I came across a save editor that allowed me to make a change to the save file, but it was very limited in what it could do, and unless you were very careful you could screw up your save file completely. So I decided to rewrite it in Java for fun, with a simpler user interface, and as I dug deeper and added more functionality I decided to release it publicly. It has grown to become a pretty useful tool.

### Features

- Easy to use UI.
- Change data values:
  - Currencies (Units, Nanites and Quicksilver)
  - Base stats for Exosuit, Multitools, Ships and Freighter (Health, Shield, Type, Class, Seed, etc.)
  - Squadron Wingmans (NPC Race, NPC Seed, Ship Type, Ship Seed, Pilot Rank, etc.)
  - Frigates Info and Stats
  - Companions / Pets (Name, Seed, Biome, Type, etc.)
  - Settlements (Population, Happiness, Production, Upkeep, Debt, etc.)
  - Milestones / Reputation
- Organize and manage inventories (Exosuit, Multitools, Ships, Freighter, Vehicles, and Base Storages)
  - Move items and technology around.
    - Drag & drop to move in the same inventory
    - Right-click menu to move to another inventory
  - Add items and technology.
    - CTRL + Drag & drop to clone same item / technology
    - Right-click menu to choose specific item / technology
  - View more information about each of the items in your inventory, such as in-game description, names, etc.
  - Repair, Recharge and Refill items / technologies (right-click menu)
  - Resize inventories (top button), Enable or Enable All additional slots (right-click menu)
  - Vanilla inventory limits (Cargo - 10x12 / Technology - 10x6 / Base Storage - 10x5) (**WARNING! You CAN go above this, but the game might BREAK!**)
- Edit the raw JSON in the save file (for advanced users only).
- Automatic backup and recovery of all saves (in case you screw up something).
- Backup/Restore of Base/Freighter Structures (Usable across different systems or saves)
- Delete or Export/Import Multitools, Ships and Frigates.
- Edit and toggle:
  - Known Technologies, Products, Words and Glyphs.
  - Your account data and unlocks.
- Currently supports Steam/GOG, PS4 (via Save Wizard), and MS Game Pass (Xbox).

### Screenshots

<img src="screenshots/exosuit.png" width="32%"/> <img src="screenshots/multitool.png" width="32%"/> <img src="screenshots/ships.png" width="32%"/>
<img src="screenshots/freighter.png" width="32%"/> <img src="screenshots/frigates.png" width="32%"/> <img src="screenshots/vehicles.png" width="32%"/>
<img src="screenshots/companions.png" width="32%"/> <img src="screenshots/base.png" width="32%"/> <img src="screenshots/settlements.png" width="32%"/>
<img src="screenshots/discovery.png" width="32%"/> <img src="screenshots/milestones.png" width="32%"/> <img src="screenshots/account.png" width="32%"/>
<img src="screenshots/jsoneditor.png" width="56%"/> More screenshots can be found [here](screenshots).

## Compatibility

Requirements:
- No Man's Sky - INTERCEPTOR (PC/Xbox/PS4)
- <a href="https://www.savewizard.net/" target="_blank">Save Wizard</a> (PS4 only)
- <a href="https://java.com/en/download/manual.jsp" target="_blank">Java Runtime Environment 8</a>

## Installation

1. Download the [latest version](../../raw/master/NMSSaveEditor.exe).
2. Run the exe and extract the contents of the zip file to an empty folder somewhere.
3. 
   1. Windows, Run the bat file (or the jar file if the file extension is associated to java).
   2. Linux, With the terminal go inside the ffolder extracted and run `java -jar ./NMSSaveEditor.jar`
5. When the main window opens, locate the folder that your saves are in, and choose the most recent.
6. Start tinkering!

## Frequently Asked Questions

Frequently asked questions can be found [here](FAQ.md).

## Contribution

This tool will always be released publicly for free, and I intend to continue maintaining it for as long as there is interest in the game. If this tool has been useful and you want to contribute to it's further development, feel free to visit me on Patreon:
https://www.patreon.com/goatfungus

## Previous Releases

- [Atlas Rises (1.3)](../atlasRises/README.md)
- [Next / Visions (1.5)](../nextVisions/README.md)
- [Beyond (2.0)](../expeditionsPrisms/README.md)
