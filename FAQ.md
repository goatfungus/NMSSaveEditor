# Frequently Asked Questions

## Exosuit

**Why can't I change the stack size on General inventory?**

In the game itself a number of bugs occurred when this was tried, so it was disabled in the editor. It only works on some types of inventory where the game doesn't do a validity check.

**Why can't I move my Jetpack to the Technology inventory?**

The game itself checks if your Jetpack exists (because it is required to play the game), but it only checks the General inventory section. If the Jetpack doesn't exist there, it will automatically create a new Jetpack. You can move it to other slots in the General section without issues though.

## Ships

**Why doesn't the ship seed from \[some site\] work?**

New ship models were added in the NEXT update, and many websites that hosted ship seeds have not been updated. There is a way to make the game use the older models, but you would need to use the JSON editor to do this.

## Bases

**Why does the terrain appear inside my base buildings when I restore from a backup?**

The game itself doesn't store all terrain modifications indefinately, and over time even unedited saves with underground bases can fill up with dirt. This is a known bug in the game which needs to be fixed, and when it is eventually fixed it would likely solve the issue with restores at the same time. We will just need to wait and see.

**How do I use the "Move Base Computer" function?**

In the game itself, you must place a Signal Booster in the position where you want your base computer to be. The save editor will swap the positions of the Base Computer and Signal Booster.

## Freighter

**Why do my freighter colours/NPCs remain the same when I change the seed?**

The freighter model is controlled by the Model Seed value, and the colours / NPCs are determined by the Home Seed (which is the system where you acquired the freighter). Unfortunately, there is no way to determine exactly which colours / NPCs are used anymore (like you could in Atlas Rises), but I think the goal of the game developers was always to create a game which relied on procedural generation for everything, not hard-coded values.

## Frigates

**How do I change the frigate class?**

Frigate class is determined by the number of beneficial traits that it has.

- C-class frigates have a primary trait, and 0-1 secondary traits.
- B-class frigates have a primary trait, and 2 secondary traits.
- A-class frigates have a primary trait, and 3 secondary traits.
- S-class frigates have a primary trait, and 4 secondary traits.

NOTE: Only beneficial traits are counted, so it is possible to fill all of the frigate traits with purely negative ones and it will show as a C-class (not that you'd want to).

**Is there a list of traits somewhere so I can see which is best?**

Not yet. Coming soon.

## Milestones

**Why doesn't the Extreme Survival milestone work?**

It does work. The problem is that the game needs to tick over the counter to grant you the achievement. You can do this in-game by simply landing on an extreme planet and waiting a few seconds.
